# Docker Web Server Project

## Author
Vivek

## Project Overview
This project demonstrates deployment of an Nginx Web Server using Docker Containerization.

## Features

- Dockerized Nginx Web Server
- Static Project Showcase Website
- Container Lifecycle Management
- Monitoring and Troubleshooting
- Docker Compose Support

## Technologies

- Docker
- Nginx
- HTML
- CSS
- WSL2 Ubuntu

## Build Image

```bash
docker build -t docker-web-app .
```

## Run Container

```bash
docker run -d -p 8081:80 docker-web-app
```

## Using Docker Compose

```bash
docker compose up -d
```

## Access Application

http://localhost:8081

## Learning Outcomes

- Docker Images
- Docker Containers
- Container Monitoring
- Networking
- Troubleshooting
