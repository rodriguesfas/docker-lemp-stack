# Docker LEMP Stack

- Linux
- Ngnix
- MySQL
- PHP

Architecture 2 layers: application (monolith) and database.

## Install Docker Ubuntu

    https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04

## Run

    docker-compose up -d

- open localhost in browser.

- open phpmyadmin in browser: localhost:8080


>>> Warning, edite hosts file

    sudo nano /etc/hosts

    127.0.0.1  realm.test
    127.0.0.1  phpmyadmin.test

edit files ```.docker/nginx/conf.d/php.conf``` and ```.docker/nginx/conf.d/phpmyadmin.conf```

user: root
password: root

## Tutorial

- [https://tech.osteel.me/posts/docker-for-local-web-development-part-1-a-basic-lemp-stack](https://tech.osteel.me/posts/docker-for-local-web-development-part-1-a-basic-lemp-stack)
