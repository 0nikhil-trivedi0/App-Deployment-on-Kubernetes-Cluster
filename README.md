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

2. **Push Docker Image to Docker Hub**
   ```sh
   docker push my-dockerhub-username/my-app:latest

3. **Deploy on Kubernetes Cluster**
   ```sh
   kubectl apply -f deployment.yaml
   kubectl apply -f service.yaml

4. **Check the Status**
   ```sh
   kubectl get pods
   kubectl get services
