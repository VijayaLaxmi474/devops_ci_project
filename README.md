# devops_ci_project
# CI/CD Pipeline Automation Using Jenkins and Docker

## Project Overview

This project demonstrates a complete CI/CD pipeline using GitHub, Jenkins, Docker, and Linux.

The pipeline automatically:

1. Pulls source code from GitHub.
2. Builds a Docker image.
3. Creates and runs a Docker container.
4. Deploys the application automatically.

## Architecture

Developer
↓
GitHub Repository
↓
Jenkins Pipeline
↓
Docker Build
↓
Docker Container Deployment

## Technologies Used

* Git
* GitHub
* Jenkins
* Docker
* Linux
* Python Flask

## Project Workflow

1. Developer pushes code to GitHub.
2. Jenkins fetches the latest code.
3. Jenkins builds a Docker image.
4. Jenkins deploys the Docker container.
5. Application becomes available on port 5000.

## Setup Instructions

### Clone Repository

git clone https://github.com/VijayaLaxmi474/devops_ci_project.git

### Navigate to Project

cd devops_ci_project

### Build Docker Image

docker build -t devops-app .

### Run Container

docker run -d -p 5000:5000 devops-app

### Access Application

http://localhost:5000

## Screenshots

### Jenkins Successful Build

![Jenkins Build](screenshots/jenkins-success.png)

### Docker Running Container

![Docker Container](screenshots/docker-ps.png)

### Application Running

![Application](screenshots/app-running.png)

## Outcome

Successfully automated application deployment using Jenkins and Docker, implementing CI/CD best practices.
