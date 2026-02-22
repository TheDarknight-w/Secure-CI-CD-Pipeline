# Secure CI/CD Pipeline

## Overview
CI/CD pipeline with integrated vulnerability scanning.

## Tools Used
- GitHub Actions
- Docker
- Trivy

## Workflow
1. Push code
2. Build Docker image
3. Run vulnerability scan
4. Fail build on high severity

## Security Controls
- Automated image scanning
- Prevent insecure deployments
