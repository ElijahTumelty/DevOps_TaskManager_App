# System Architecture

TaskManager follows a **containerised, cloud-hosted three-tier architecture** designed to reflect modern DevOps and cloud-native practices.

---

## High-Level Architecture

Client (Browser)
↓
NGINX Reverse Proxy
↓
Flask Application (Docker Container)
↓
Azure Database for MySQL (Managed Service)

---

## Core Components

### Client
Users interact with the system via a web browser using HTTP(S).

### Web Server
NGINX acts as a reverse proxy, improving security and separating request handling from application logic.

### Application Container
- Flask application runs inside a Docker container
- Stateless by design
- Enables redeployment and horizontal scaling

### Database
- Azure Database for MySQL (Flexible Server)
- Persistent storage external to containers
- Automated backups and SSL-enforced connections

---

## Architectural Benefits

- Clear separation of concerns
- Improved scalability and maintainability
- Reduced operational overhead
- Production-aligned cloud deployment model
