# Управление базой данных

В модуле подключен liquibase. Также можно генерировать файл конфигурации текущей
локальной базы данных командой:

```
mvn clean liquibase:generateChangeLog
```

Эта команда создаст скрипт для установки ровно той конфигурации, которая есть сейчас в локальной БД,
которую можно развернуть через docker-compose.