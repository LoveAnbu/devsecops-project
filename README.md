# DevSecOps + GitHub Actions + EKS

This project demonstrates a production-grade DevSecOps pipeline using:

- GitHub Actions (CI/CD)
- Docker (Containerization)
- AWS ECR (Image Registry)
- AWS EKS (Kubernetes)
- SonarQube (Code Quality)
- Trivy (Security Scanning)
- OPA (Policy Enforcement)
- Prometheus + Grafana (Monitoring)

## App

Simple Node.js app with health endpoint.

## Endpoints

- `/` → App info
- `/health` → Health check
