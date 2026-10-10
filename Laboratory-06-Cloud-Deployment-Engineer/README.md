# Laboratory 06 - Cloud Deployment Engineer

## Mission Overview

In this mission, I learned how to deploy a multi-tier private cloud storage application using Docker Compose. The setup uses two containers: Nextcloud for the web application and MariaDB for the database. These two containers work together to create a simple two-tier system.

## Objectives

- Learn what a multi-tier application architecture is.
- Understand how a `docker-compose.yml` file works.
- Use Nano to create and edit configuration files.
- Deploy Nextcloud and MariaDB using Docker Compose.
- Learn how Infrastructure as Code (IaC) can be used to manage cloud applications.
- Document the steps and commands used during the deployment.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
cat docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
```
