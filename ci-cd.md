# Continuous Integration & Deployment

This project uses a **container-based CI deployment model** to ensure consistency, reliability, and automation.

---

## CI Pipeline Overview

1. Code pushed to GitHub repository
2. GitHub Actions workflow triggers
3. Docker image is built automatically
4. Image is pushed to Docker Hub
5. Azure Web App pulls and runs the image

---

## Why This Approach?

- Ensures reproducible builds
- Reduces manual deployment errors
- Supports easy rollbacks via image versions
- Aligns with modern DevOps automation practices

---

## Tools Used

- GitHub Actions
- Docker
- Docker Hub
- Azure Web App for Containers

---

## Limitations & Improvements

- Automated tests are not currently part of the pipeline
- Deployment is not fully gated
- Future improvements:
  - Add test stages
  - Add deployment approval gates
  - Integrate automated redeployment
