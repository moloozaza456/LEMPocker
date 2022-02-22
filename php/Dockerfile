# Base Image PHP 7 with FPM Alpine
# if you want  PHP 8 use 8.0-fpm-alpine
FROM php:7.4-fpm-alpine
# ติดตั้ง extension mysqli สำหรับไว้เชื่อมต่อกับฐานข้อมูล mysql/mariadb
RUN docker-php-ext-install mysqli
RUN docker-php-ext-install pdo_mysql