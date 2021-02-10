.env file
-------------------------------
#!/usr/bin/env bash

# See https://docs.docker.com/compose/environment-variables/#the-env-file

# Nginx
NGINX_HOST=localhost

# PHP

# See https://hub.docker.com/r/nanoninja/php-fpm/tags/
PHP_VERSION=7.4.10

# MySQL
MYSQL_VERSION=8.0.21
MYSQL_HOST=mysql
MYSQL_DATABASE=test
MYSQL_ROOT_USER=root
MYSQL_ROOT_PASSWORD=root
MYSQL_USER=dev
MYSQL_PASSWORD=dev
-------------------------------