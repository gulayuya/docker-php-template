FROM php:7.4-fpm
RUN apt-get update && apt-get install -y \
    vim \
    unzip \
    zip \
    iputils-ping \
    git
RUN docker-php-ext-install pdo_mysql