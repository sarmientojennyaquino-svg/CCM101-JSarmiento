# Laboratory 06 - Cloud Deployment Engineer

## Mission Overview

In this laboratory, I learned how to deploy a two-tier cloud application using Docker Compose. I used Nextcloud as the web application and MariaDB as the database. The goal was to understand how containers work together to provide a cloud storage service.

## Objectives

* Understand the concept of two-tier architecture.
* Learn how to write a `docker-compose.yml` file.
* Deploy Nextcloud and MariaDB using Docker Compose.
* Configure environment variables for database connectivity.
* Understand how containers communicate with each other.
* Document the deployment process and reflect on what I learned.

## Commands Executed

The following are the main commands used during the laboratory:

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose logs
docker-compose down
```

Note: These are the main commands for the workflow. Include only the commands you actually executed in your final submission.

## Skills Learned

* Creating and editing configuration files using Nano.
* Writing YAML files with proper indentation.
* Deploying multi-container applications with Docker Compose.
* Using environment variables to configure containers.
* Understanding communication between application and database services.
* Troubleshooting deployment problems and documenting technical work.
