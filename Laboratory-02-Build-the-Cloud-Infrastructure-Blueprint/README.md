# Laboratory 02 - Build the Cloud Infrastructure Blueprint

## Mission Overview

This laboratory activity focuses on understanding the basic components of cloud infrastructure. It investigates a Linux cloud server, identifies compute, storage, networking, and operating system resources, compares major cloud providers, and designs a simple cloud infrastructure.

## Objectives

- Investigate a Linux server running in a cloud environment.
- Identify the major components of cloud infrastructure.
- Understand compute, storage, networking, and operating system resources.
- Compare AWS, Microsoft Azure, and Google Cloud Platform.
- Design a simple cloud infrastructure diagram.
- Document the investigation using Markdown.

## Cloud Infrastructure Components

The basic cloud architecture used in this laboratory is:

*User → Internet → Cloud Server → Storage*

The user connects to the cloud through the Internet. The cloud server provides computing resources for applications and services, while storage is used to save and manage data.

## Tools Used

- KillerCoda Playground
- Linux Terminal
- GitHub
- Markdown
- Web Browser
- Canva / Draw.io / PowerPoint for the cloud architecture diagram

## Linux Commands Executed

```bash
uname -a
cat /etc/os-release
lscpu
nproc
free -h
df -h
findmnt
hostname
hostname -I
