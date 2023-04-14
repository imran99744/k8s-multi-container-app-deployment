# Dockerized React and Node app with Postgres database, And deployed this 3 tire application on Kubernetes Cluster

## Introduction
This project is a web application that consists of a React frontend, a Node.js backend, and a Postgres database. The app is Dockerized and can be easily deployed on a Kubernetes cluster.


## Technologies Used
- React - frontend framework
- Node.js - backend framework
- PostgreSQL - database
- Docker - containerization technology
- Kubernetes - container orchestration platform

## Project Structure
This project is a web application using a three-tier architecture. It consists of a React frontend, a Node.js backend, and a Postgres database. Each tier communicates through RESTful API endpoints. The app is Dockerized and can be deployed on Kubernetes. The architecture provides flexibility and scalability, and the use of Docker and Kubernetes makes deployment and scaling easy.


## Setup Instructions
### Docker
- Clone the repository: git clone `https://github.com/imran99744/k8s-multi-container-app-deployment.git`
- Change directory: cd `k8s-multi-container-app-deployment`
- Build the Docker images and pushed it to dockerhub repository

### Kubernetes
- Clone the repository: git clone `https://github.com/imran99744/k8s-multi-container-app-deployment.git`
- Change directory: cd `k8s-multi-container-app-deployment`
- Deploy the app on Kubernetes: kubectl apply -f k8s

## Deployment Architecture
The app consists of three containers: frontend, backend, and database. These containers are orchestrated by Kubernetes, which runs them on a cluster of machines.

The Kubernetes deployment consists of two main components: a frontend deployment and a Postgres deployment. The frontend deployment runs the React frontend and the Node.js backend containers, while the Postgres deployment runs the Postgres database container.

## Conclusion
This project demonstrates how to Dockerize a web application consisting of a React frontend, a Node.js backend, and a Postgres database. The app can be easily deployed on a Kubernetes cluster, making it highly scalable and easy to manage.
