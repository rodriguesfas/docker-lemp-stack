# Cheat Sheet

Cheat Sheet Docker

## Commands Docker

### Docker Up

    docker-compose up -d

## Docker Down

    docker-compose down -v

## Docker Restart

    docker-compose restart

### View containers current running.

    docker-compose ps

### Stop containers

    docker-compose stop

### Open php container in terminal

    docker-compose exec php bash

### Exit container

    exit

### View Logs

    docker-compose logs -f

    docker-compose logs -f nginx

### Delete images

    docker rmi <image> -f

### Delete all images

    docker rmi -f $(docker images -aq)