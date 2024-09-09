# To-Do Microservices Application

This repository contains a to-do application built using a microservices architecture. The application is composed of two microservices: User Service and To-Do Service. The services communicate using RabbitMQ, and the app is containerized using Docker.

## Microservices Overview

- **User Service**: Manages user registration, login, logout, and account management.
- **To-Do Service**: Manages creation, retrieval, updating, and deletion of to-do items.

## Architecture

![Architecture Diagram](docs/architecture-diagram.png)

### Technologies Used

- **Nest.js**: Framework for building microservices.
- **JWT with RSA**: For authentication and refresh tokens.
- **RabbitMQ**: Message broker for communication between services.
- **PostgreSQL**: Database for persisting data.
- **TypeORM**: ORM for interacting with PostgreSQL.
- **Docker**: Containerization of services.
- **Kubernetes**: Orchestration for deployment and scaling (optional).

## Directory Structure

- **`/user-service`**: Contains code and configurations for the User Service.
- **`/todo-service`**: Contains code and configurations for the To-Do Service.
- **`/infrastructure`**: Contains Docker Compose and Kubernetes configurations.
- **`/docs`**: Contains architecture diagrams and documentation.

## Getting Started

### Prerequisites

- Docker
- Docker Compose
- Node.js (for development)
- Kubernetes (optional for production)

### Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/todo-microservices-app.git
   cd todo-microservices-app
   ```
