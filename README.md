# TaskManager – DevOps Case Study

TaskManager is a containerised Python Flask web application developed as part of a DevOps-focused university project. The primary goal of this work was not feature complexity, but the **practical application of DevOps principles** across deployment, security, maintainability, observability, scalability, and continuous integration.

**Note:**  
The full source code and infrastructure configuration are kept private. This repository provides a **DevOps-focused technical overview** of the system design, deployment strategy, and engineering decisions.

---

## Project Summary

TaskManager is a simple task management application that allows users to securely create, update, and manage personal tasks. While the application logic is intentionally lightweight, the system is deployed using **production-aligned DevOps practices**, including containerisation, cloud hosting, CI automation, and secure configuration management.

---

## Core DevOps Focus Areas

- Containerised deployment with Docker
- Cloud hosting using Azure Web App for Containers
- Managed database with Azure Database for MySQL
- CI pipeline using GitHub Actions
- Secure authentication and configuration isolation
- Structured logging and observability
- Scalability through stateless application design

---

## Technology Stack

**Application**
- Python (Flask)
- SQLAlchemy ORM

**Infrastructure & DevOps**
- Docker & Docker Compose
- GitHub Actions (CI)
- Docker Hub (image registry)
- Azure Web App for Containers (PaaS)
- Azure Database for MySQL (Flexible Server)
- NGINX (reverse proxy)

---

## Documentation Contents

- [`architecture.md`](architecture.md) – system and deployment architecture
- [`ci-cd.md`](ci-cd.md) – CI pipeline and deployment model
- [`devops-principles.md`](devops-principles.md) – DevOps capabilities in practice
- [`security.md`](security.md) – security-focused DevOps decisions
- [`observability-scalability.md`](observability-scalability.md)
- [`lessons-learned.md`](lessons-learned.md)

---

## Why the Code Is Private

The project includes:
- authentication logic
- cloud-hosted infrastructure
- security-sensitive configuration
- academic constraints

This documentation reflects the **real implementation and reasoning** behind the system without exposing sensitive details.
