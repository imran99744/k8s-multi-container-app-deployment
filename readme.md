# Dockerized React and Node app with Postgres database, deployed on Kubernetes with Ingress and Nginx

## Introduction
This project is a web application that consists of a React frontend, a Node.js backend, and a Postgres database. The app is Dockerized and can be easily deployed on a Kubernetes cluster. In addition, the app uses an Ingress service and Nginx as a reverse proxy to provide external access to the app.


## Technologies Used
- React - frontend framework
- Node.js - backend framework
- PostgreSQL - database
- Docker - containerization technology
- Kubernetes - container orchestration platform
- Nginx - reverse proxy server
- Ingress - Kubernetes API object that manages external access to the app

## Project Structure
This project is a web application consisting of a React frontend, a Node.js backend, and a Postgres database. Each component is Dockerized and deployed on a Kubernetes cluster. The frontend, backend, and database are each deployed as a separate Kubernetes deployment, and are connected to each other through Kubernetes services. To provide external access to the application, an Ingress service is used with an Nginx server as a reverse proxy. This architecture provides flexibility, scalability, and reliability.


## Setup Instructions
### Docker
- Clone the repository: git clone `https://github.com/imran99744/k8s-multi-container-app-deployment.git`
- Change directory: cd `k8s-multi-container-app-deployment`
- Build the Docker images and pushed it to dockerhub repository

### Kubernetes
- Clone the repository: git clone `https://github.com/imran99744/k8s-multi-container-app-deployment.git`
- Change directory: cd `k8s-multi-container-app-deployment`
- Deploy the app on Kubernetes: `kubectl apply -f k8s`

## Deployment Architecture
The app consists of three containers: frontend, backend, and database. These containers are orchestrated by Kubernetes, which runs them on a cluster of machines.

The Kubernetes deployment consists of two main components: a frontend deployment and a Postgres deployment. The frontend deployment runs the React frontend and the Node.js backend containers, while the Postgres deployment runs the Postgres database container.

To provide external access to the app, the Kubernetes cluster uses an Ingress service and Nginx as a reverse proxy. The Ingress service manages external access to the app by mapping incoming requests to the appropriate backend service. Nginx serves as the reverse proxy server, handling incoming requests and forwarding them to the appropriate backend service.

## Conclusion
This project demonstrates how to Dockerize a web application consisting of a React frontend, a Node.js backend, and a Postgres database, and deploy it on a Kubernetes cluster with Ingress and Nginx. The architecture provides flexibility and scalability, and the use of Docker and Kubernetes makes deployment and scaling easy. The Ingress service and Nginx allow external access to the app while ensuring the security and reliability of the app.
