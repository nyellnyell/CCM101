# Technical Documentation: Docker Compose

## The `services:` Block
The `services:` block defines the distinct containers that constitute the application stack. In our `docker-compose.yml` file, two services were configured: `database` (MariaDB) and `app` (Nextcloud).

## Service Discovery (`MYSQL_HOST`)
The Nextcloud app container connects to the database using the environment variable `MYSQL_HOST=database`. Docker Compose creates a private network where service names act as DNS hostnames, allowing `app` to resolve `database` directly without needing static IP addresses.

## `docker run` vs. `docker-compose up -d`
`docker run` is used to launch individual containers manually using long command-line arguments. `docker-compose up -d` uses Infrastructure as Code (IaC) via a YAML file to configure, network, and launch an entire multi-container application stack in the background with a single command.
