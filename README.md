Microservices-Based Notification & Account Management System
📌 Abstract

This project is a microservices-based distributed system designed to manage user authentication, account services, and notification delivery in a scalable and modular way. Each functionality is implemented as an independent service, enabling better fault isolation, scalability, and maintainability. The system follows modern cloud-native design principles and demonstrates how microservices communicate through a centralized gateway and service registry.

🎯 Objectives

To understand and implement microservices architecture

To design independent and loosely coupled services

To implement service discovery and API gateway

To demonstrate inter-service communication

To deploy services using Docker and containerization

🧩 System Architecture

The application is built using multiple independent services, each responsible for a specific business function:

Authentication Service – Handles user login and authentication

Account Service – Manages user account information

Notification Service – Sends notifications to users

Gateway Service – Acts as a single entry point for all services

Service Registry – Enables service discovery and load balancing

Configuration Service – Centralized configuration management

Monitoring Services – Helps track system health and performance

Each service runs independently and communicates using REST APIs.

🛠️ Tech Stack

Backend: Java, Spring Boot

Architecture: Microservices

Service Discovery: Eureka Registry

API Gateway: Spring Cloud Gateway

Containerization: Docker & Docker Compose

Database: MongoDB

Build Tool: Maven

⚙️ Features

Modular microservices architecture

Centralized API gateway

Service discovery using registry

Secure authentication handling

Notification delivery system

Docker-based deployment

Scalable and fault-tolerant design

🚀 How to Run the Project
Prerequisites

Java (JDK 8 or above)

Maven

Docker & Docker Compose

MongoDB

Steps to Run

Clone the repository

Navigate to the project root directory

Build the services:

mvn clean install


Start the application using Docker:

docker-compose up


Access services through the API Gateway

📂 Project Structure
├── account-service
├── auth-service
├── notification-service
├── gateway
├── registry
├── config
├── monitoring
├── docker-compose.yml
└── pom.xml

📈 Future Enhancements

Implement role-based access control

Add message queue for async communication

Improve monitoring and logging

Deploy on cloud platforms

Add frontend interface

🎓 Academic Use

This project is developed for educational purposes to understand distributed systems and microservices architecture. Open-source resources were referred to for learning and implementation guidance.

👤 Author

Aditi Maindola
Department of Computer Science
