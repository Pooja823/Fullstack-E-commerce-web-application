# Fullstack E-Commerce Microservices Application

## 📌 Project Overview
This project is a **Fullstack E-Commerce Web Application** built using a **Microservices Architecture**.  
It includes a **React frontend**, multiple **Spring Boot microservices**, and **MongoDB** databases.  
The application is containerized using **Docker**, deployed using **Render & Kubernetes**, and monitored using **Prometheus and Grafana**.

---

## 🏗 Architecture Overview

- **Frontend**: ReactJS
- **Backend**: Spring Boot Microservices
- **Database**: MongoDB Atlas
- **Service Discovery**: Eureka Server
- **API Gateway**: Spring Cloud Gateway
- **Containerization**: Docker
- **Orchestration**: Kubernetes
- **Monitoring**: Prometheus & Grafana
- **Automation**: Ansible
- **Cloud Platform**: Render / AWS

---

## 🧩 Microservices Used (Minimum 5)

1. **Eureka Server** – Service Registry
2. **API Gateway** – Central entry point
3. **User Service** – User authentication and management
4. **Product Service** – Product catalog management
5. **Order Service** – Order processing
6. **Cart Service** – Shopping cart management
7. **Notification Service** – Order notifications

Each microservice has:
- Independent Spring Boot application
- Separate MongoDB database
- Individual Dockerfile

---

## ☁️ Cloud Service Models Implemented

| Model | Description |
|-----|------------|
| **SaaS** | E-Commerce web application |
| **PaaS** | Render cloud platform |
| **DBaaS** | MongoDB Atlas |

---

## 🚀 Deployment on Render

### Backend Services
- Each microservice is deployed as a **separate Render Web Service**
- Docker-based deployment
- Environment variables used for configuration

### Frontend
- Deployed as **Render Static Site**
- Communicates with backend via API Gateway

---

## 📦 Docker Containerization

- Dockerfile for each microservice
- Images built and deployed via Render
- Docker Desktop used for local testing

### Sample Docker Commands
```bash
docker build -t user-service .
docker run -p 8081:8081 user-service
