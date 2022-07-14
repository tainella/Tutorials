### Получить docker image

sudo docker pull [image_name]

### Сбилдить свой докерфайл

sudo docker build -t [name] .

### Собрать контейнер

sudo docker run --name [new_name] -it [old_name] bash

### Запустить контейнер по названию image

sudo docker run -it [image_name] bash

### Для запуска контейнера с jupyter-notebook пробросить порты

sudo docker run -p 8888:8888 -it [image_name] bash

Чтобы открыть из контейнера сам юпитер ноутбук, перейти по предлагаемой ссылке и поменять хост на localhost:8888

### Запустить ранее собранный контейнер

sudo docker start [name]

### Перейти в запущенный контейнер

sudo docker exec -it [name] /bin/bash
