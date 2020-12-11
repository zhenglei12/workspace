FROM php:7.4-fpm
RUN apt-get update && apt-get install -y \
    && docker-php-ext-install pdo_mysql && docker-php-ext-enable pdo_mysql \
    && docker-php-ext-install mysqli && docker-php-ext-enable mysqli

