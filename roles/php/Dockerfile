FROM php:fpm

WORKDIR /var/www/html

COPY ./html /var/www/html

RUN chown -R www-data:www-data /var/www/html

RUN docker-php-ext-install pdo pdo_mysql

