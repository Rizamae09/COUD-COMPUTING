# Laboratory 04 - Cloud-Native Engineer

## Mission Overview

This laboratory activity focuses on cloud-native technologies, especially containers and Docker. The activity compares Virtual Machines and Containers and demonstrates how to deploy and manage a containerized Nginx web server.

## Objectives

- Differentiate Virtual Machines and Containers.
- Access a Docker-enabled cloud environment using KillerCoda.
- Execute basic Docker commands.
- Pull, run, manage, and remove an Nginx container.
- Create technical documentation using Markdown.
- Update and organize the GitHub Cloud Computing Portfolio.

## Docker Commands Executed

```bash
docker --version
docker info
docker pull nginx
docker run -d -p 8080:80 --name nginx-server nginx
curl http://localhost:8080
docker ps
docker stop nginx-server
docker ps -a
docker rm nginx-server
docker ps -a
