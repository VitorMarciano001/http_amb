FROM php:8.1-apache

RUN apk update \
    && apk add --no-cache libpq-dev \
    && docker-php-ext-install pdo pdo_mysql


