# **Advanced Microservices-based Airline Booking System**

A highly scalable airline booking system designed using microservices architecture. This project emphasizes modularity, scalability, and security, ensuring seamless performance and reliable functionality.

---

## **Table of Contents**
1. [About the Project](#about-the-project)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Microservices](#microservices)
5. [Getting Started](#getting-started)
6. [Project Repositories](#project-repositories)

---

## **About the Project**
This system is built to manage airline operations, including flight management, bookings, and notifications. By leveraging a microservices-based architecture, the project ensures:
- **Scalability**: Handles growing user demand with ease.
- **High Availability**: Ensures reliable operations through distributed architecture.
- **Data Integrity**: Maintains transactional consistency, especially during critical operations like seat booking.
- **Security**: Incorporates JWT-based authentication and encrypted user credentials.

---

## **Tech Stack**
### **Backend**
- **Node.js**: Runtime for building scalable, event-driven services.
- **Express.js**: Lightweight framework for building APIs.
- **Sequelize ORM**: Simplified database management and migrations.
- **RabbitMQ**: Efficient messaging system for asynchronous communication.
- **Redis**: Used for caching and rate limiting.

### **Database**
- **MySQL**: Relational database for structured data storage.
- **SQL Migrations**: Ensures version control for database schema.

### **Security**
- **JWT**: Token-based authentication for secure access.
- **bcrypt**: Password hashing to enhance security.

---

## **Features**
1. **Flight Management**:
   - Manage CRUD operations for flights with a user-friendly API.
   - Robust SQL migrations for seamless schema updates.
2. **Flight Search**:
   - Efficient search functionality for flights based on user requirements.
3. **Flight Booking**:
   - Sophisticated seat selection mechanism.
   - Concurrency control to handle simultaneous bookings effectively.
4. **Notification Service**:
   - Asynchronous messaging for booking confirmations and alerts.
5. **API Gateway**:
   - Centralized routing with rate limiting and reverse proxy functionality.

---

## **Microservices**
### 1. **Airline Search Service**
- Handles search functionality for flights based on user preferences.
- Repository: [Airline Search Service](https://github.com/abhijeetGupta7/AIrplane_Search_Service)

### 2. **Booking Service**
- Core service for handling bookings with data integrity using transactions and locks.
- Repository: [Booking Service](https://github.com/abhijeetGupta7/Airline_Booking_Service)

### 3. **Notification Service**
- Sends notifications using RabbitMQ for asynchronous message queuing.
- Repository: [Notification Service](https://github.com/abhijeetGupta7/Airline_Notification_Service)

### 4. **API Gateway**
- Routes requests to appropriate microservices and ensures rate-limited access.
- Repository: [API Gateway](https://github.com/abhijeetGupta7/Airline_API_GATEWAY)

---

## **Getting Started**
### **Prerequisites**
- **Node.js**: v14.x or above.
- **MySQL**: 8.0 or above.
- **RabbitMQ**: Latest stable version.

### **Setup**
1. Clone the repositories listed in the [Project Repositories](#project-repositories) section.
2. Follow setup instructions in each repository's README.

---

## **Project Repositories**
| Service                | Description                                                  | Link                                                                 |
|------------------------|--------------------------------------------------------------|----------------------------------------------------------------------|
| API Gateway            | Centralized request routing and rate limiting                | [API Gateway](https://github.com/abhijeetGupta7/Airline_API_GATEWAY) |
| Flight Service         | Manages CRUD operations for flights                          | [Flight Service](https://github.com/abhijeetGupta7/AIrplane_Search_Service) |
| Booking Service        | Handles seat selection, reservations, and concurrency        | [Booking Service](https://github.com/abhijeetGupta7/Airline_Booking_Service) |
| Notification Service   | Sends booking notifications using RabbitMQ                  | [Notification Service](https://github.com/abhijeetGupta7/Airline_Notification_Service) |

---
