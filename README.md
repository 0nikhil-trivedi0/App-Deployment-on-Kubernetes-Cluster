# My Kubernetes Project

## Description
This project demonstrates how to deploy an application on a Kubernetes cluster.

## Files
- `Dockerfile`: Docker image definition for the application.
- `deployment.yaml`: Kubernetes deployment configuration.
- `service.yaml`: Kubernetes service configuration.

## Steps to Deploy

1. **Build Docker Image**
   ```sh
   docker build -t my-dockerhub-username/my-app:latest .

