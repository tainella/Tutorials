### Собрать из исходников (текущая папка) колесо в другую папку

pip wheel --wheel-dir=/folder/ -r requirements.txt .

Удобно, можно указывать флаги для сборки.

### Собрать колесо из уже собранного пакета на локальной машине

pip wheel --wheel-dir=/folder/ packagename

### Установить пакет из колеса, которое лежит в папке

pip install --find-links /folder/ packagename