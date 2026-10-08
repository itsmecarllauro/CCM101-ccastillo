# Docker Compose Guide

## What does the services: block do?

The `services:` block defines the containers that will be created and used by Docker Compose. In this project, there are two services: `database` and `app`. The `database` service uses MariaDB, while the `app` service uses Nextcloud.

## How does the Nextcloud app find the database?

The Nextcloud container finds the database container through the `MYSQL_HOST` environment variable.

The Compose file contains:

```yaml
- MYSQL_HOST=database
```

The value `database` matches the name of the MariaDB service. This allows the Nextcloud application to connect to the database container.

## Difference between docker run and docker-compose up -d

`docker run` is normally used to create and start an individual Docker container by manually providing its settings.

`docker-compose up -d` uses a YAML configuration file to create and start multiple containers and their settings together. In this activity, Docker Compose starts both the Nextcloud application and MariaDB database at the same time.

The `-d` option means that the containers run in the background, allowing the terminal to be used for other commands.
