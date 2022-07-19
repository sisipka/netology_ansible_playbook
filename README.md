### GROUP VARS

`clickhouse_version` - версия clickhouse

`clickhouse_packages` - необходимые для установки пакеты clickhouse

`vector_version` - версия vector

`vector_home` - домашняя директория vector

### Описание Play

Предназначен для установки `clickhouse` и `vector` на 2 docker контейнера(centos): clickhouse-01 и vector-01.

### Install Vector

__Установлены теги:__

- `vector_dir` - создание домашней директории

- `vector` - распаковка установочного архива в домашнюю директорию

- `vector_template` - копирование файла конфигурации
  