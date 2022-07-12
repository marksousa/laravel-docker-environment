# Laravel 9 Docker Environment

Nginx, php, mysql, composer, npm, artisan.

## Requirements

    Docker
    Docker Compose

## Commands

    docker-compose up -d --build api
    cd src
    docker-compose run --rm composer install
    docker-compose run --rm artisan key:generate
    docker-compose run --rm artisan migrate
