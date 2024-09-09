# **Simple E-Commerce Platform**

A full-stack, microservices-based e-commerce platform built with **Node.js**, **Express**, **MongoDB**, **React.js**, **Docker**, **Nginx**, and **Flask**. This project demonstrates a scalable and modular architecture, leveraging multiple technologies to handle various aspects of an e-commerce system like user management, product catalog, order processing, payment handling, and notifications.

## **Table of Contents**

- [Features](#features)
- [Architecture](#architecture)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [API Gateway Configuration](#api-gateway-configuration)
- [Contributing](#contributing)
- [License](#license)

## **Features**

- **Microservices Architecture**: Each service (User, Product, Order, Payment, Notification) runs independently for better scalability and maintainability.
- **API Gateway (Nginx)**: Manages routing between services and provides a single entry point for the frontend.
- **Dockerized Deployment**: All services are containerized for easy deployment and environment consistency.
- **React.js Frontend**: User-friendly interface to interact with backend services.
- **MongoDB Database**: Efficient data management with optimized schemas and indexing.

## **Architecture**

The project follows a microservices architecture with the following key components:

1. **User Service**: Handles user registration, login, and profile management.
2. **Product Service**: Manages product details, inventory, and CRUD operations.
3. **Order Service**: Handles order creation, tracking, and management.
4. **Payment Service**: Processes payments and manages payment gateways.
5. **Notification Service**: Sends notifications for order status, payment confirmation, etc.
6. **API Gateway (Nginx)**: Routes requests to the appropriate microservice.

## **Tech Stack**

- **Backend**: Node.js, Express, Flask
- **Frontend**: React.js
- **Database**: MongoDB
- **API Gateway**: Nginx
- **Containerization**: Docker, Docker Compose

## **Getting Started**

### **Prerequisites**

- **Docker** and **Docker Compose** installed on your machine
- **Node.js** and **npm** (for frontend development)
- **Python 3** (for backend services using Flask)

### **Installation**

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/simple-ecommerce-platform.git
   cd simple-ecommerce-platform
