FROM php:apache

RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
RUN pecl install apcu && docker-php-ext-enable apcu