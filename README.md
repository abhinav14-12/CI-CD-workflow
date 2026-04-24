CI/CD Pipeline with GitHub Actions & Docker

This repository demonstrates a basic CI/CD pipeline using GitHub Actions to automate testing, building, and deploying a Dockerized Python application.

Overview

The pipeline performs the following steps:

Trigger on push to main branch or manual dispatch
Checkout repository code
Build a Docker image
Run tests inside the container using pytest
Authenticate with Docker Hub
Push the Docker image to Docker Hub
