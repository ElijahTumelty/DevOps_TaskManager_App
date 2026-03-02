# Observability & Scalability

---

## Observability

The system supports observability through:
- Flask logging
- Database-backed audit logs
- Azure App Service logs
- Custom error pages for improved visibility

### Limitations
- No metrics dashboards
- No distributed tracing

Future improvements include Azure Application Insights integration.

---

## Scalability

Scalability is achieved by:
- Keeping the application container stateless
- Externalising persistent storage
- Leveraging Azure’s built-in scaling features

Future scalability could be enhanced using:
- Azure Kubernetes Service (AKS)
