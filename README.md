# Task 5: Kubernetes with Minikube

This project demonstrates deploying and managing an application using Kubernetes on Minikube. It includes creating a Deployment and a NodePort Service, scaling the Deployment, and accessing the application.

## Prerequisites

- Docker Desktop installed and running
- Minikube installed
- kubectl installed

## Steps to Run

1. **Start Docker Desktop**  
   Ensure Docker is running on your system.

2. **Start Minikube**  
   ```bash
   minikube start --driver=docker
# Apply Deployment
kubectl apply -f deployment.yaml

# Apply Service
kubectl apply -f service.yaml

# Verify Pods
kubectl get pods -o wide

