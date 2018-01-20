# Dockerised LNMP

PHP 7.1 + Nginx + MySQL

## Get started

```bash
$ docker-compose up --build

# View the start page at http://localhost:8081
# Connect to MySQL at localhost:3037
```

## Useful command
```
# List all container
$ docker ps -a

# Enter PHP-FPM container
$ docker exec -i -t app_fpm /bin/bash

# Restart PHP-FPM inside container
$ kill -USR2 1
```


## Uninstall

```bash
$ docker-compose stop
$ docker-compose rm -f
```

## Authors

- [Andrew Mok](https://andrewmmc.com) (@andrewmmc)