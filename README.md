# My local mysql container

easy instalation for testing and studies

first create a `.env` file:

```shell
MYSQL_ROOT_PASSWORD=YOUR_CREDENTIAL_HERE
MYSQL_DATABASE=YOUR_CREDENTIAL_HERE
MYSQL_USER=YOUR_CREDENTIAL_HERE
MYSQL_PASSWORD=YOUR_CREDENTIAL_HERE
```

*e.g*:

```shell
MYSQL_ROOT_PASSWORD=1234
MYSQL_DATABASE=test
MYSQL_USER=testuser
MYSQL_PASSWORD=1234
```

then run:

```shell
docker compose up -d --build
```
