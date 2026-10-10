# Docker Compose Guide

## The Services Block

The `services:` block is used to define the containers needed for the application. In this project, there are two services. The `database` service uses MariaDB, while the `app` service uses Nextcloud.

## How Nextcloud Finds the Database

The Nextcloud container connects to the database through the `MYSQL_HOST` environment variable. The value `MYSQL_HOST=database` tells Nextcloud to connect to the MariaDB container using the service name `database`.

## Docker Run vs Docker Compose Up -d

The `docker run` command is used to create and run a single Docker container. On the other hand, `docker-compose up -d` uses the Compose file to create and run multiple containers at the same time. In this activity, Docker Compose is used to run both Nextcloud and MariaDB as one multi-container application.
