# 🚀 AWS 3-Tier Architecture

## 📌 Project Overview

This project demonstrates the deployment of a secure, scalable, and highly available AWS 3-Tier Architecture using Amazon Web Services.

The architecture separates the application into three independent layers:

- Web Tier
- Application Tier
- Database Tier

This improves scalability, security, and high availability.

---

# 🏗️ Architecture

```
                     Internet
                         │
                         ▼
           Internet Facing Load Balancer
                         │
              Auto Scaling Group (Web Tier)
                         │
              Internal Load Balancer
                         │
        Auto Scaling Group (Application Tier)
                         │
                    Amazon RDS
```

---

# ☁️ AWS Services Used

- Amazon EC2
- Amazon VPC
- Public Subnets
- Private Subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Bastion Host
- Application Load Balancer (Public)
- Application Load Balancer (Internal)
- Target Groups
- Auto Scaling Groups
- Amazon RDS
- Nginx
- Linux

---

# 📁 Architecture Components

## Web Tier

- Internet Facing Application Load Balancer
- Auto Scaling Group
- Nginx Web Server

## Application Tier

- Internal Application Load Balancer
- Auto Scaling Group
- PHP Application

## Database Tier

- Amazon RDS MySQL

---

# 🔒 Security

- Public and Private Subnets
- Security Groups
- Bastion Host for secure SSH access
- Internal Load Balancer for Application Tier
- Database deployed in Private Subnet

---

# 🚀 Features

- Highly Available Architecture
- Multi-AZ Deployment
- Auto Scaling
- Load Balancing
- Secure Network Design
- Production Style Architecture
- Scalable Infrastructure

---

# 📚 Skills Demonstrated

- AWS Networking
- Linux
- EC2
- VPC
- Auto Scaling
- Application Load Balancer
- Target Groups
- Security Groups
- Route Tables
- NAT Gateway
- Internet Gateway
- Nginx
- Cloud Architecture

---

# 🎯 Outcome

Successfully deployed a production-style AWS 3-Tier Architecture using core AWS services while implementing networking, load balancing, auto scaling, and secure communication between application layers.

---

## 👨‍💻 Author

**Uday Mali**

Learning AWS | DevOps | Cloud Computing
