# CloudForge – Production-Style AWS EKS Platform

A production-style Kubernetes platform on AWS, provisioned using
Terraform and managed through GitOps.

## Project Overview

CloudForge demonstrates infrastructure automation, secure CI/CD,
progressive delivery, observability, autoscaling and reliability
engineering using AWS and Kubernetes.

## Technology Stack

- AWS: VPC, EKS, IAM, S3, DynamoDB, ECR, Secrets Manager
- Infrastructure as Code: Terraform
- Containerization: Docker
- CI/CD: GitHub Actions
- Authentication: GitHub OIDC
- GitOps: Argo CD
- Progressive Delivery: Argo Rollouts
- Autoscaling: HPA and Karpenter
- Monitoring: Prometheus and Grafana
- Logging: Grafana Loki
- Security: Kyverno, Falco, Trivy
- Secrets: External Secrets Operator
- Disaster Recovery: Velero
- Chaos Engineering: Chaos Mesh
- Cost Analysis: Infracost

## Architecture

Architecture documentation will be added under `docs/architecture/`.

## Implementation Roadmap

1. Environment preparation
2. Terraform foundation
3. AWS networking and EKS
4. Kubernetes add-ons and GitOps
5. Secrets management and security
6. Progressive delivery
7. Intelligent autoscaling
8. Observability and SRE
9. Disaster recovery and chaos engineering
10. CI/CD automation and documentation

## Project Status

Currently in Phase 0 – Environment and AWS preparation.

## Cost Notice

AWS resources may incur charges. Infrastructure will be
provisioned selectively and destroyed when not required.

## License

MIT License
