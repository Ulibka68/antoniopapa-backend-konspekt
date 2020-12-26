Composer не запуститься если не дать прав на директорию
wsl:
cd /root/_prj/antoniopapa/admin-backend/
chmod -R 777 sites
chmod -R 777 data

команда из под wsl
docker-compose up -d --build
docker-compose down

NGINX натсроен на хостинг hello.loc  
Не забываем в файле HOSTS добавить:
127.0.0.1 hello.loc


docker exec -it php bash

=====================  
composer create-project laravel/laravel hello

http://hello.loc:8080/ 

### Работа с Laravel
docker exec -it php bash
cd hello
php artisan migrate