#Apache HTTP сервер для установки 1С v8.3 на CentOS 7.1

1С не поддерживает Apache HTTP 2.4, который по умолчанию ставится в современных дистрибутивах. Попытка запуска завершается с ошибкой: `wsap22.so: undefined symbol: ap_rputs`
Поэтому пришлось собрать пакет с Apache HTTP 2.2. Пакет замещает собой "родную" версию Apache в RHEL7 и наследованных от него дистрибутивах, и не удаляется при установке обновлений.

PS. Немного позже я выложу собранный бинарный пакет.
