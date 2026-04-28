# App Deployment using Kubernetes, Docker, CI CD on AWS

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![Docker](https://img.shields.io/badge/Docker-Container-blue)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-blueviolet)
![CI/CD](https://img.shields.io/badge/CI/CD-Automation-success)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## Project Overview

This project shows end to end deployment of a containerized web application using Kubernetes on AWS with a fully automated CI CD pipeline.

You push code. Pipeline builds Docker image. Image goes to AWS ECR. Kubernetes pulls and deploys automatically.

Focus on real DevOps workflow used in production systems.

---

## Key Impact

* Reduced manual deployment effort to zero
* Automated build and deployment on every push
* Consistent environment using Docker containers
* Scalable deployment using Kubernetes
* Faster rollback using image versioning

---

## Architecture

```
Developer → GitHub → CI Pipeline → Docker Build → Docker Registry → Kubernetes Cluster → Users
```

---

## Tech Stack

* AWS EC2 / EKS
* Docker
* Kubernetes
* Jenkins
* Linux

---

## CI CD Workflow

1. Push code to GitHub
2. GitHub Actions pipeline triggers
3. Build Docker image
4. Push image to Registry
5. Kubernetes pulls latest image
6. Deployment updates automatically

---

## Project Structure

```
.
├── Dockerfile
├── k8s/
│   ├── deployment.yaml
│   └── service.yaml
├── .github/workflows/
│   └── ci-cd.yml
├── app/
└── README.md
```

---

## Future Improvements

* Add Helm charts
* Add monitoring with Prometheus and Grafana
* Add auto scaling
* Add blue green deployment

---


