# Kubernetes Local Deployment Project 

This project demonstrates how to containerize a simple Python web application using Docker, and deploy it to a local Kubernetes cluster using Minikube.

##  Tools Used

- Python 
- Flask (a Python web framework) 
- Docker 
- Kubernetes 
- Minikube (runs Kubernetes locally) 

## Project Structure

k8s-local-cluster-deploy/
├── app/                  # My Flask app files and Dockerfile
├── kubernetes/           # All My Kubernetes YAML files
├── docker-compose.yml    # For running locally with Docker only
└── README.md             # This file you're reading right now

##  Run Locally with Docker Compose

1. Make sure Docker is running on your computer.
2. Clone the repo:
   ```bash
   git clone https://github.com/YOUR-USERNAME/k8s-web-app.git
   cd k8s-web-app
