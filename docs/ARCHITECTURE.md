# CloudVault - System Architecture

## 1. Project Overview

CloudVault is a cloud engineering learning and infrastructure
management platform. It combines practical engineering labs,
infrastructure monitoring, security features and an intelligent
engineering assistant.

## 2. Core Components

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS

### Backend
- Python
- FastAPI
- REST APIs

### Database
- PostgreSQL

### Web Server
- Nginx

### Infrastructure
- Ubuntu / Rocky Linux
- Docker
- AWS
- Terraform
- Kubernetes

### DevOps and Monitoring
- GitHub Actions
- Prometheus
- Grafana

## 3. A.E.G.I.S.

A.E.G.I.S. stands for Adaptive Engineering & Guidance Intelligence System.

It will provide:
- Basic engineering tutor
- Voice interaction
- Deep, calm, sophisticated male voice
- A.E.G.I.S. wake word
- Professional JARVIS-style personality
- AI-powered assistance in a later development stage
- Authorised infrastructure monitoring
- Permission-controlled operational actions

## 4. Initial Architecture

Browser
   |
   v
React Frontend
   |
   v
Nginx Web Server
   |
   v
FastAPI Backend
   |
   +---- PostgreSQL
   |
   +---- A.E.G.I.S.
   |
   +---- Infrastructure Services

## 5. Deployment Strategy

Stage 1: Local development using Windows, WSL and VS Code.

Stage 2: Docker containerisation.

Stage 3: AWS deployment.

Stage 4: Infrastructure automation and advanced monitoring.

## 6. Development Principles

- Build incrementally.
- Understand every technology used.
- Follow secure coding practices.
- Never expose credentials.
- Document architectural decisions.
- Test before advancing.
