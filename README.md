### Описание Play

Предназначен для установки `clickhouse`, `vector`, `nginx` и `lighthouse` на 3 VM в yandex cloud.

### GROUP VARS

`lighthouse_vcs` - git репозиторий lighthouse

`lighthouse_location_dir` - локальная директория lighthouse
 
`clickhouse_version` - версия clickhouse

`clickhouse_packages` - необходимые для установки пакеты clickhouse

`vector_version` - версия vector

`vector_home` - домашняя директория vector

### Install Vector

__Установлены теги:__

`vector_dir` - создание домашней директории

`vector` - распаковка установочного архива в домашнюю директорию

`vector_template` - копирование файла конфигурации
  
`install nginx` - установлен nginx

`install lighthouse` - установлен lighthouse

### Template

`lighthouse.conf` - конфигурация lighthouse

`nginx.conf` - конфигурация nginx

`vector.cfg` - конфигурация vector