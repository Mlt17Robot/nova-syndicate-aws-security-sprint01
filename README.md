# Nova Syndicate — AWS Cloud Security Architecture

## Overview
![Nova Syndicate Architecture](architecture/SPRINT_1_NOVA_V6.png)
Nova Syndicate is a fictional logistics company handling sensitive medical, aerospace, and defense-related components.

This project demonstrates the design and deployment of a secure AWS cloud infrastructure following security best practices and enterprise-grade architecture principles.

The infrastructure focuses on:

- Network segmentation
- Multi-AZ resilience
- Secure private workloads
- Centralized logging & monitoring
- Zero Trust principles
- AWS-native security services

---

# Sprint 1 — Secure Foundation

## Implemented Components

### Networking
- Multi-AZ VPC architecture
- Public / Private App / Private DB subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- NACL protection

### Security
- AWS KMS encryption
- Security Hub
- GuardDuty
- CloudTrail
- VPC Flow Logs
- CloudWatch monitoring
- Secure S3 audit logs bucket

### Private AWS Access
- S3 Gateway Endpoint
- SSM Endpoint
- EC2 Messages Endpoint
- CloudWatch Logs Endpoint

---

# Security Architecture Goals

- No direct internet access to workloads
- Private database isolation
- Centralized audit logging
- Monitoring & threat detection
- Encrypted storage and logs
- Reduced attack surface

---

# Architecture Diagram

(Add your architecture PNG here)

---

# Upcoming Sprint

## Sprint 2 — Compute Layer

- Application Load Balancer
- Private EC2 instances
- RDS PostgreSQL
- SSM Session Manager
- Auto Scaling
- Hardened IAM roles
- Secure application deployment

---

# Technologies Used

- AWS CloudFormation
- Amazon VPC
- EC2
- RDS PostgreSQL
- CloudTrail
- GuardDuty
- Security Hub
- CloudWatch
- KMS
- S3
- IAM
- VPC Endpoints

---

# Author

Lionel Mpata
AWS Certified Solutions Architect – Associate
Cloud Security & AWS Architecture Enthusiast