# LEMP Server

Simple Nginx and PHP-FPM server for PHP applications.

### Configuration
---
* Nginx latest (Port 8080)
* PHP FPM 7.3
* MySQL 5.7
* Adminer Latest (Port 8081)
* Redis Latest

### How To Use:
---
Defualt configred document root is "/usr/shar/nginx/html", however you can configure it as per your needs in "config/nginx/default.conf file".

Simply run 
```
docker-compose up -d
```
to run your Lempp server

