FROM php:7.4-apache
RUN docker-php-ext-install mysqli
RUN pecl install xdebug-3.0.1
RUN docker-php-ext-enable xdebug
COPY ./php.ini /usr/local/etc/php/conf.d/template-php.ini
