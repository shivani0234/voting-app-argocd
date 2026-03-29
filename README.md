
A complete guide and implementation for deploying a scalable voting application on **Kubernetes** using **Kind** and **Argo CD**. This project demonstrates GitOps, automated deployments, and container orchestration on a local Kubernetes cluster or cloud instance.

---

## Table of Contents

- [Overview](#overview)
- [Architecture](#architecture)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup Instructions](#setup-instructions)
- [Argo CD Deployment](#argo-cd-deployment)
- [Usage](#usage)
- [Observability](#observability)
- [Author](#author)


## Overview

This project showcases a simple voting application with multiple services deployed via Kubernetes. It uses **Kind** for local Kubernetes cluster, **Argo CD** for GitOps-style deployments, and containerized services like Redis, Postgres, Python, .NET, and Node.js apps.

---

## Architecture

<img width="1536" height="1024" alt="Live DevOps Kubernetes project diagram" src="https://github.com/user-attachments/assets/b79355fc-8fca-48d6-a27c-eda5e29f802d" />

## Observability

<img width="1536" height="1024" alt="Kubernetes monitoring dashboard view" src="https://github.com/user-attachments/assets/399707a0-1c9e-43c9-8aec-d228e43db204" />

## Setup Instructions

- Frontend: Python web app (vote between two options)  
- Backend: .NET worker for processing votes  
- Database: Postgres (Docker volume)  
- Cache: Redis  
- Results: Node.js app for live updates  

---

## Features

- Local Kubernetes cluster with **Kind**
- Automated deployment via **Argo CD**
- GitOps-based continuous delivery
- Live results dashboard
- Persistent storage with Docker volumes
- Observability via Prometheus & Grafana

---

## Tech Stack

| Component         | Technology/Tool         |
|------------------|------------------------|
| Containerization  | Docker                 |
| Kubernetes        | Kind                   |
| CI/CD             | Argo CD                |
| Frontend          | Python (Flask)         |
| Backend Worker    | .NET Core              |
| Results App       | Node.js                |
| Database          | Postgres               |
| Cache             | Redis                  |
| Monitoring        | Prometheus, Grafana    |

---

