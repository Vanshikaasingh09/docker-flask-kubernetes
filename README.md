# Simple Flask App on Kubernetes (Minikube)

This project is a simple Flask application containerized with Docker and deployed to Kubernetes using Minikube.

## Project Structure
- `app.py` : Python Flask application
- `Dockerfile` : Dockerfile to containerize the app
- `deployment.yaml` : Kubernetes Deployment file
- `service.yaml` : Kubernetes Service file
- `hpa.yaml` : Kubernetes Horizontal Pod Autoscaler file (optional)

## Steps to run

1. Build Docker Image
```bash
docker build -t simple-web-app .


