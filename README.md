# 🏥 Patient Management Microservices System

This project is a modular and scalable microservices-based architecture for managing patient records, billing, authentication, and analytics. Designed with cloud-native principles and built using Java and Spring Boot, it demonstrates how to decouple healthcare services into independently deployable units with robust communication and service discovery.

## 📦 Overview

This system is currently under development. It is structured around independent microservices, each responsible for a specific functional domain. This architecture improves scalability, maintainability, and the ability to deploy services independently.

## 🧩 Core Microservices

- **API Gateway** – Acts as a single entry point for all clients, routing requests to appropriate services.
- **Auth Service** – Handles user authentication and authorization.
- **Patient Service** – Manages patient records, registration, and profile updates.
- **Billing Service** – Handles invoices, payment processing, and transaction logs.
- **Analytics Service** – Provides metrics, reporting, and usage statistics.
- **Infrastructure** – Common configurations and Docker-based orchestration setup.
- **Integration Tests** – Ensures consistent behavior across microservices.

## 🛠️ Tech Stack

| Component              | Technology                        |
|------------------------|------------------------------------|
| Language               | Java 17                            |
| Backend Framework      | Spring Boot, Spring Cloud          |
| Communication          | gRPC (internal service communication) |
| Service Discovery      | Spring Cloud Discovery (Eureka/Consul) |
| API Gateway            | Spring Cloud Gateway               |
| Security               | Spring Security, JWT               |
| Containerization       | Docker                             |
| Build Tool             | Maven                              |
| Testing                | JUnit, Integration Testing Suite   |

## 🚀 Features

- Microservice-based architecture with domain-driven design
- Secure and stateless authentication via JWT
- Scalable and loosely coupled components
- Dockerized environment for easy deployment
- gRPC communication for high-performance inter-service messaging
- Designed for future expansion (appointments, notifications, staff module)

## 🧪 Setup (WIP)

1. Clone the repository:
   ```bash
   git clone https://github.com/TheMajaveli/patient_management_microservices.git
