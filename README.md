# AWS EKS Production Reference Architecture

This repository contains reference architecture patterns for running production workloads on Amazon EKS.

## Objectives

* High Availability
* Scalability
* Security
* Observability
* Disaster Recovery

## Architecture Components

### Networking

* VPC
* Public Subnets
* Private Subnets
* NAT Gateway
* Route Tables

### Kubernetes

* Amazon EKS
* Managed Node Groups
* Ingress Controller
* Cluster Autoscaler

### Security

* IAM Roles
* Security Groups
* Secrets Management

### Observability

* Prometheus
* Grafana
* Centralized Logging

## Deployment Model

Internet

↓

Application Load Balancer

↓

Amazon EKS

↓

Microservices

↓

RDS / Databases

## Future Enhancements

* Multi-Region Architecture
* Service Mesh
* GitOps Integration
