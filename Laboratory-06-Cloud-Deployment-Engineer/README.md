# Laboratory 06: Cloud Deployment Engineer

## Mission Overview

In this laboratory activity, I deployed a private cloud storage system using Nextcloud and MariaDB. Instead of deploying the containers manually one by one, I used Docker Compose to define the application and database in a YAML configuration file.

The project uses a two-tier architecture. The Nextcloud application acts as the web tier, while MariaDB acts as the database tier.

## Objectives

The objectives of this laboratory activity are:

* Understand multi-tier application architecture.
* Understand the purpose and structure of a `docker-compose.yml` file.
* Use the Linux `nano` text editor to create configuration files.
* Deploy Nextcloud and MariaDB using Docker Compose.
* Access the Nextcloud web interface through port 8080.
* Document the deployment process using Markdown.
* Practice Infrastructure as Code principles.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
```

## Skills Learned

Through this activity, I learned how to create a Docker Compose configuration and use it to deploy multiple containers. I also learned how a web application and database can work together in a two-tier architecture.

I learned how environment variables can be used to configure the connection between Nextcloud and MariaDB. I also practiced using Linux commands, editing YAML files with nano, checking running containers, and shutting down a complete container stack.

This activity also helped me understand Infrastructure as Code because the deployment configuration is written in a file instead of relying only on manual commands.
