# Azure Docker Compose Project

## Overview

This project demonstrates the deployment of a multi-container web application on Microsoft Azure using Docker, Docker Compose, Flask, and NGINX.

The application was deployed on an Ubuntu Linux Virtual Machine hosted in Azure and utilizes Docker containerization, container networking, reverse proxy configuration, persistent storage, and container monitoring concepts commonly used in cloud operations and DevOps environments.

---

## Technologies Used

* Microsoft Azure
* Azure Virtual Machines
* Ubuntu Linux
* Docker
* Docker Compose
* Python
* Flask
* NGINX
* Docker Volumes
* Git & GitHub

---

## Architecture

Internet
↓
Azure Public IP
↓
NGINX Container
↓
Flask Container

Docker Compose manages both containers and provides internal container networking.

---

## Features

### Containerized Flask Application

* Developed a Python Flask web application
* Built a custom Docker image using a Dockerfile
* Deployed the application in a Docker container

### Docker Compose Deployment

* Automated multi-container deployment
* Managed application services through docker-compose.yml
* Simplified container lifecycle management

### NGINX Reverse Proxy

* Configured NGINX as a reverse proxy
* Routed incoming traffic to the Flask application
* Implemented container-to-container communication

### Docker Volumes

* Created persistent storage using Docker volumes
* Verified data survives container deletion and recreation

### Monitoring & Troubleshooting

* Monitored container resource utilization using docker stats
* Investigated application activity using docker logs
* Troubleshot networking, port conflicts, and container issues

---

## Skills Demonstrated

* Linux Administration
* Docker Containerization
* Docker Compose
* Container Networking
* Reverse Proxy Configuration
* Persistent Storage Management
* Azure Infrastructure Management
* Application Deployment
* Cloud Operations Troubleshooting

---



## Lessons Learned

This project provided hands-on experience deploying and managing containerized applications in Microsoft Azure. Through building custom Docker images, configuring Docker Compose, implementing NGINX reverse proxy services, and troubleshooting networking and storage issues, I gained practical experience with technologies commonly used in Cloud Operations, Cloud Support, and DevOps environments.
