FROM php:7.0-apache

# symlink htdocs to html
RUN cd .. \ && ln -s html htdocs
RUN docker-php-ext-install pdo_mysql