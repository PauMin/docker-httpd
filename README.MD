# Docker httpd

Simple docker development sever with wildcard subdomains.
___

## How it works

Simply add each project to separate directory inside `www`. `public` directory is obligatory. After that new project will be awailable at projects-name.dev.local .

## Features

* Nginx server
* PHP-FPM with PHP 8
* MySQL server

> To add new services just edit `docker-compose.yml`

## Prerequsites

* Docker need to be installed on your development machine
* Set up DNS proxy to accept wildcard domains. (example: [Acrylic DNS Proxy](http://mayakron.altervista.org/support/acrylic/Home.htm))

## Instalation

1. Clone this repository
2. Configure `.env` file inside `services/mysql`
3. Run `docker-compose.yml`
4. Add new project to www directory and you ready to go!
