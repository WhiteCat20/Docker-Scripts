# 🐳 Personalized Docker Scripts

This repository contains a collection of Docker Compose scripts to easily spin up commonly used services like databases, message brokers, and more. These scripts are designed for development and testing purposes, and can be customized to fit various project needs.

## 📁 Directory Structure

Each folder in this repository represents a separate service or stack, such as:

- `postgresql-docker/` – PostgreSQL database container
- `mysql-docker/` – MySQL database container
- `mongodb-docker/` – MongoDB container (coming soon)
- `redis-docker/` – Redis in-memory store (coming soon)
- `rabbitmq-docker/` – RabbitMQ message broker (coming soon)
- `elasticsearch-docker/` – Elasticsearch container (coming soon)

## 🚀 Quick Start

1. Clone the repository:

   ```bash
   git clone https://github.com/WhiteCat20/docker-scripts.git
   cd docker-scripts
2. Navigate to the desired service folder:

    ```bash
    cd postgresql-docker
3. Start the Container:

    ```bash
    docker-compose up -d
