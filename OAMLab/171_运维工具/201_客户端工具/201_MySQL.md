# MySQL

## HeidiSQL:
- https://www.heidisql.com/download.php

## phpMyAdmin:
- https://docs.phpmyadmin.net/en/latest/setup.html#quick-install
````
docker run --name phpmyadmin-2022xxxx-xxxx -d -e PMA_HOSTS=192.168.xxx.1,192.168.xxx.2 -p 8080:80 phpmyadmin/phpmyadmin
````