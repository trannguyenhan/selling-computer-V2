FROM php:7.4-apache

COPY my-apache2.conf /etc/apache2/apach2.conf
RUN a2enmod rewrite

RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
RUN apt-get update && apt-get upgrade -y
