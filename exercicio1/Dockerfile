FROM php:7.3-apache

# Permite o modrewrite para arquivos .htaccess
RUN a2enmod rewrite

# Habilita o mysqli para manipulação do banco de dados
RUN docker-php-ext-install mysqli