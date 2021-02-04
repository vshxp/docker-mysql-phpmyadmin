# docker-compose MySQL + phpmyadmin



![banner](./media/banner.png)


Its a docker-compose dev environment that create a MySql 5.7 server

## Steps
1. Rename the file .env.sample to .env
2. Change the variables values from the file .env
3. deploy

## Deploy
```shell
docker-compose up -d
``` 

## Exposed ports
```shell
PORT       SERVICE
3306/tcp  - mySql
80/tpc    - phpMyAdmin
```

## Default
```shell
username: root
password: #123Mudar#
```