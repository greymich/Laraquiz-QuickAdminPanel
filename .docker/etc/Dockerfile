FROM php:7.4-fpm-alpine

RUN apk add iputils

RUN docker-php-ext-install sockets

RUN docker-php-ext-install pdo_mysql

RUN chmod 4755 /usr/bin/traceroute