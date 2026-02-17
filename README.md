# Dockerized Python Application

## Overview
This project demonstrates containerization of a simple Python application using Docker
to ensure consistent runtime environments and reproducible deployments.

## Tech Stack
- Python
- Flask
- Docker

## Build Docker Image

Run the following command to build the Docker image:

    docker build -t python-app .

## Run Docker Container

Run the container using the command below:

    docker run -p 5000:5000 python-app

## Application Endpoint

    GET /health

## Expected Response

    {
      "status": "ok"
    }

## Key Learnings
- Writing Dockerfiles for application packaging
- Building and running containers locally
- Understanding container-based deployment workflows


