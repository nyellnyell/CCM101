# Mission 6: The Cloud Deployment Engineer

## Mission Overview

In this mission, I deployed a multi-tier private cloud storage application using Docker Compose. The application uses Nextcloud as the web application and MariaDB as the database.

## Objectives

- Understand multi-tier application architecture.
- Create a `docker-compose.yml` configuration file.
- Deploy Nextcloud and MariaDB using Docker Compose.
- Verify that the containers are running.
- Access the Nextcloud web interface.
- Document the deployment process using Markdown.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
