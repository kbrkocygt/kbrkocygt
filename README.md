# 🛒 MultiShop – Microservice Based E-Commerce Backend

MultiShop is a distributed e-commerce backend system designed with a microservice architecture and API Gateway pattern.

This project focuses on scalability, service isolation and production-style backend engineering practices.

---

## 🏗 Architecture Overview

MultiShop is built using an API Gateway and independent microservices with isolated databases.

![MultiShop Microservice Diagram](images/multishop-diagram.png)

### 🔹 Architecture Highlights

- Ocelot API Gateway for routing & aggregation
- Identity Server for authentication & token management
- Independent microservices with separate databases
- Redis for basket management
- RabbitMQ for asynchronous communication
- Dockerized service infrastructure
- Service-to-service communication strategy
- Production-style layered architecture

---

## 🧩 Microservices

| Service      | Database        | Purpose |
|-------------|----------------|---------|
| Identity     | SQL Server     | Authentication & token management |
| Catalog      | MongoDB        | Product & category management |
| Basket       | Redis          | Cart operations |
| Cargo        | SQL Server     | Shipping management |
| Order        | SQL Server     | Order processing |
| Discount     | SQL Server     | Discount logic |
| Comment      | SQL Server     | Product reviews |
| Message      | PostgreSQL     | User messaging |
| Images       | Google Cloud   | Image storage |

---

## 🛠 Tech Stack

### Backend
- ASP.NET Core
- C#
- Ocelot API Gateway
- Entity Framework Core
- Dapper
- JWT Authentication
- SignalR

### Databases
- SQL Server
- MongoDB
- PostgreSQL
- Redis

### Infrastructure
- Docker
- RabbitMQ
- Portainer
- Postman

---

## 🎯 Design Goals

- Service isolation with independent databases
- Loose coupling via messaging
- API Gateway pattern implementation
- Scalable distributed architecture
- Maintainable layered structure
- Production-like environment simulation

---

## 🔐 Security

- JWT-based authentication
- Role-based authorization
- Identity service token validation
- Secure service communication patterns

---

## 🚀 Key Engineering Practices

- Clean separation of concerns
- Dependency Injection
- Middleware-based global exception handling
- Structured logging
- Configuration management
- Dockerized microservice environment

---

## 📌 Why This Project Matters

MultiShop demonstrates how to design and structure a distributed backend system beyond a simple CRUD API.

It reflects real-world backend engineering concerns such as:

- Scalability
- Fault isolation
- Asynchronous communication
- Service orchestration
- Maintainability

---

## 📫 Contact

📧 kubraooktay@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/kübra-koçyiğit/
