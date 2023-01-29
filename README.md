# docker-demo

## First step ##

Run this repo in codespaces

## Run the mariadb and php my admin ##

```bash
cd mariadb-php-myadmin/
docker-compose up -d # -d means detached
```

You will see a pop up, offering opening the browser for port 3030 (phpmyadmin)

login with
Server: db
user: mariadb
password: mariadb


##Stop the contaiers and removes them ##

```bash
docker compose down
```

## Prune the unused images ##

```bash
docker system prune -a
```