# AWS VPC Web Application Architecture

## 📌 Project Overview
This project demonstrates the design and implementation of a secure and highly
available AWS VPC architecture for hosting a web application.

The architecture is built using public and private subnets distributed across
multiple Availability Zones following AWS best practices.

---

## 🏗 Architecture Diagram
![VPC Architecture](diagrams/vpc-architecture.png)

---

## 📋 Current Scope
- VPC (10.0.0.0/16)
- 2 Public Subnets (Multi-AZ)
- 2 Private Subnets (Multi-AZ)
- Internet Gateway
- Route Tables
- S3 VPC Endpoint

> 🚧 This project is under continuous development and will be extended to include
> EC2, Load Balancer, and security enhancements.

---

## ☁️ AWS Services Used
- Amazon VPC
- Subnets
- Route Tables
- Internet Gateway
- VPC Endpoint (S3)

---

## 📚 What I Learned (So Far)
- Designing multi-AZ VPC architectures
- Difference between public and private subnets
- Secure routing and internet access control
- Applying AWS networking best practices

