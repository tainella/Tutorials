### Получить docker image

sudo docker pull [image_name]

### Собрать контейнер

sudo docker run --name [new_name] -it [old_name] /bin/bash

### Запустить ранее собранный контейнер

sudo docker start [name]

### Перейти в запущенный контейнер

sudo docker exec -it [name] /bin/bash
