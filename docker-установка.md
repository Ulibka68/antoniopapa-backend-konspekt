Не забываем в файле HOSTS добавить:

127.0.0.1 hello.loc

пересобрать сборку:
docker-compose up -d --build

Переходим по адресу http://hello.loc/ и видим, что все работает.

docker exec -it php bash
docker exec -it mysql bash

docker inspect mysql
mysql -u root -p

Завершаем работу командой:
docker-compose down

Перечислить образы Docker на вашем компьютере
docker image ls --all

Перечислите контейнеры на компьютере с помощью:  
docker container ls --all  
или  
docker ps -a

