# Advanced Java Assessments (Week 4)

# Week 4 – BookStore Microservices System

## Description
The **BookStore System** is implemented using **Spring Cloud Microservices architecture**.  
The system consists of multiple services that communicate with each other using **Feign Client and Service Discovery**.

## Technologies Used
- Spring Boot
- Spring Cloud
- Eureka Server
- API Gateway
- OpenFeign
- Spring Data JPA
- PostgreSQL
- Maven

## Microservices Architecture

| Service | Port | Responsibility |
|------|------|------|
| Eureka Server | 8761 | Service registry |
| API Gateway | 8080 | Entry point for all client requests |
| Book Service | 8081 | Manage book catalog |
| Order Service | 8082 | Manage customer orders |

## Book Entity
- id
- title
- author
- isbn
- price
- quantity
- category

## Order Entity
- id
- bookId
- customerName
- quantity
- totalPrice
- status
- orderDate

## Key Features
- Service discovery using Eureka
- API Gateway for centralized routing
- Inter-service communication using Feign Client
- Separate databases for each service
- Full CRUD operations for books and orders
- Microservice architecture implementation

---

# How to Run the Projects

## Clone the Repository
```bash
git clone https://github.com/your-username/repository-name.git
```

## Navigate to the Project
```
cd repository-name
```

## Build the Project
```
mvn clean install
```

## Run the Application
```
mvn spring-boot:run
```

---

# Learning Outcomes after 4 weeks

These assessments demonstrate practical knowledge of:

- Spring Framework
- Spring Boot application development
- REST API design
- Database integration with JPA
- File upload and handling
- Security implementation with Spring Security
- Pagination and caching
- Microservices architecture using Spring Cloud
- Service discovery and API gateway configuration

---
