# Multi-Tier Architecture

## The Web/Application Tier

The Web/Application Tier is responsible for providing the user interface and handling HTTP requests. In this activity, the Nextcloud application works as the web application that users access through a browser.

## The Database Tier

The Database Tier is responsible for storing persistent data. In this activity, MariaDB stores information such as user accounts and file metadata needed by Nextcloud.

## Why Separate Them?

Separating the web application and database into two containers makes the system easier to manage and organize. Each container has its own role, so changes or problems in one container do not directly affect the other. This also makes the application easier to maintain and deploy.
