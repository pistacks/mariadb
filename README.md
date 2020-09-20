# mariadb
MariaDB for ARM

## Usage

```
$ docker run --rm -it -p 3307:3306 \
  -v /var/lib/mysql:/var/lib/mysql \
  -e MYSQL_DATABASE=testdb \
  -e MYSQL_USER=test \
  -e MYSQL_PASSWORD=pass \
  -e MYSQL_ROOT_PASSWORD=rootpass \
  pistacks/mariadb
```

For more options look at [github.com/yobasystems/alpine-mariadb](https://github.com/yobasystems/alpine-mariadb)
