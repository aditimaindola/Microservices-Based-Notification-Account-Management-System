# Microservices-Based Notification & Account Management System

## 📌 Abstract
This minor project demonstrates the implementation of a **microservices-based distributed system** for managing user authentication, account services, and notification delivery. Each functionality is developed as an independent service, allowing the system to be modular, scalable, and easier to maintain. The project highlights the use of modern cloud-native concepts such as service discovery, API gateway, and containerization.

---

## 🎯 Objectives
- To understand the fundamentals of **microservices architecture**
- To design **independent and loosely coupled services**
- To implement **service discovery** and an **API gateway**
- To demonstrate **inter-service communication**
- To deploy services using **Docker and containerization**

---

## 🧩 System Architecture
The system is composed of multiple independent services, each responsible for a specific business operation:

- **Authentication Service** – Handles user login and authentication  
- **Account Service** – Manages user account details  
- **Notification Service** – Sends notifications to users  
- **Gateway Service** – Acts as a single entry point for all client requests  
- **Service Registry** – Enables service discovery and load balancing  
- **Configuration Service** – Provides centralized configuration management  

Each service runs independently and communicates with other services using **RESTful APIs**.

---

## 🛠️ Tech Stack
- **Backend:** Java, Spring Boot  
- **Architecture:** Microservices  
- **Service Discovery:** Eureka Registry  
- **API Gateway:** Spring Cloud Gateway  
- **Containerization:** Docker, Docker Compose  
- **Database:** MongoDB  
- **Build Tool:** Maven  

---

## ⚙️ Features
- Modular microservices architecture  
- Centralized API gateway  
- Service discovery using a registry  
- Secure authentication handling  
- Notification delivery mechanism  
- Docker-based deployment  
- Scalable and fault-tolerant design  

---

## 🚀 How to Run the Project

### Prerequisites
- Java (JDK 8 or above)
- Maven
- Docker & Docker Compose
- MongoDB

---
### Steps to Run
```bash
git clone <repository-url>
cd project-folder-name
mvn clean install
docker-compose up


