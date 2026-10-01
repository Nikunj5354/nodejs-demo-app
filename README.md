# Node.js CI/CD Pipeline using GitHub Actions and Docker

## Project Overview

This project demonstrates a complete CI/CD pipeline for a Node.js web application using GitHub Actions and Docker.

Whenever code is pushed to the `main` branch, GitHub Actions automatically:

1. Installs Node.js dependencies
2. Tests the application
3. Builds a Docker image
4. Logs in to Docker Hub
5. Pushes the Docker image to Docker Hub

## Technologies Used

- Node.js
- Express.js
- Docker
- Docker Hub
- GitHub
- GitHub Actions

## Project Structure

```text
nodejs-demo-app/
│
├── .github/
│   └── workflows/
│       └── main.yml
├── .dockerignore
├── Dockerfile
├── package.json
├── package-lock.json
├── server.js
└── README.md
