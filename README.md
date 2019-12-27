# docker-lamp

Docker example with Apache, MySql 8.0, PhpMyAdmin and Php

- You can use MariaDB 10.1 if you checkout branch `mariadb-10.1` - contribution made by [luca-vercelli](https://github.com/luca-vercelli)
- You can use MySql 5.7 if you checkout branch `mysql5.7`
- You can use php 5.6 and mysql 8 if you checkout branch `php-5.6`

I use docker-compose as an orchestrator. To run these containers:

```
docker-compose up -d
```

Open phpmyadmin at [http://localhost:8000](http://localhost:8000)
Open web browser to look at a simple php example at [http://localhost:8001](http://localhost:8001)

Run mysql client:

- `docker-compose exec db mysql -u root -p` 

Enjoy !
