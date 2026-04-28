# Zomato Clone with Kubernetes Deployment | CI CD on AWS

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![Docker](https://img.shields.io/badge/Docker-Container-blue)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-blueviolet)
![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-red)
![Security](https://img.shields.io/badge/Security-Scanned-success)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## Project Overview

Built a Zomato clone and deployed using Kubernetes on AWS EC2 with a complete CI CD pipeline.

The pipeline automates build, testing, security scanning, and deployment.

Focused on real DevOps workflow used in production systems.

---

## Key Impact

* Automated full deployment pipeline using Jenkins
* Integrated code quality checks with SonarQube
* Performed security scans using OWASP Dependency Check and Trivy
* Reduced deployment failures by fixing dependency mismatch issues
* Enabled consistent deployments using Docker multi stage builds
* Deployed scalable application using Kubernetes

---

## Architecture

```id="2q9kxp"
Developer → GitHub → Jenkins → SonarQube → OWASP Scan → Trivy → Docker Build → Docker Hub → Kubernetes (AWS EC2) → Users
```

---

## Tech Stack

* AWS EC2
* Docker
* Kubernetes
* Jenkins
* SonarQube
* OWASP Dependency Check
* Trivy
* Docker Hub
* Linux

---

## CI CD Workflow

1. Push code to GitHub
2. Jenkins pipeline triggers
3. Build application
4. Run SonarQube analysis
5. Perform OWASP dependency scan
6. Run Trivy security scan
7. Build Docker image using multi stage build
8. Push image to Docker Hub
9. Deploy to Kubernetes on AWS EC2

---

## Project Structure

```id="k7b3vz"
.
├── Dockerfile
├── Jenkinsfile
├── k8s/
│   ├── deployment.yaml
│   └── service.yaml
├── app/
└── README.md
```

---


## You can Learn

* CI CD pipeline with Jenkins
* Code quality analysis with SonarQube
* Security scanning using OWASP and Trivy
* Docker multi stage builds
* Kubernetes deployment on AWS
* Debugging real deployment failures

---

## Challenges Solved

* Fixed dependency mismatch causing deployment failure
* Improved pipeline reliability
* Ensured secure and stable container builds

---

## Future Improvements

* Add Helm charts
* Add monitoring with Prometheus and Grafana
* Add auto scaling
* Add blue green deployment

---
