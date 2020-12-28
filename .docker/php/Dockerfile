FROM php:7.3-fpm-stretch

COPY .docker/php/php.ini /usr/local/etc/php/php.ini
COPY . /srv/app

WORKDIR /srv/app

RUN chown -R www-data:www-data /srv/app