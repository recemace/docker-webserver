FROM php:7.0-fpm
RUN docker-php-ext-install mysqli
RUN apt-get update && apt-get install -y libpq-dev && docker-php-ext-install pdo pdo_pgsql