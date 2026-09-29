# Wanderlust Infrastructure 🚀

A hands-on DevOps project built around the open-source **Wanderlust** full-stack travel blog application.

## Project Origin

This project is based on the open-source Wanderlust application:

🔗 Original Repository: https://github.com/krishnaacharyaa/wanderlust

The application itself was **cloned from the original repository** and is not built from scratch here.

The goal of this repository is to progressively take the existing application and build a complete DevOps workflow around it.

## Project Goal

This project is focused on turning DevOps theory into practical experience by progressively implementing:

- Linux and system administration
- Docker and containerization
- CI/CD
- AWS cloud infrastructure
- Terraform / Infrastructure as Code
- Kubernetes
- Helm
- DevSecOps and security
- Jenkins
- GitOps with Argo CD
- Prometheus and Grafana monitoring
- Production-oriented deployment practices

The technologies will be introduced gradually as the application evolves.

## Current Application Stack

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS

### Backend
- Node.js
- Express
- TypeScript
- Mongoose

### Data & Services
- MongoDB Atlas
- Redis

## Current Local Architecture

```text
Browser
   │
   ▼
React + Vite
localhost:5173
   │
   │ HTTP / Axios
   ▼
Node.js + Express
localhost:8080
   │
   ├── MongoDB Atlas
   │
   └── Redis
       localhost:6379