# php-web-symfony-template

## Description
A POC for php web framework, symfony.

This only sets up symfony, it doesn't
creates any application.

## Tech stack
- php
  - symfony
- nginx
- mariadb

## Docker stack
- nginx:latest
- php:fpm
- bitnami/symfony:4.4

## To run
`sudo ./install.sh -u`
Available localhost:80

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Example code](https://www.therelicans.com/anthonygilbertt/setting-up-a-php-docker-container-then-adding-symfony-part-2-2-59f1)
