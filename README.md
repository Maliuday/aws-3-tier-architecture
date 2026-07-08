# 🚀 AWS 3-Tier Architecture

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazonaws)
![EC2](https://img.shields.io/badge/EC2-Running-yellow?style=for-the-badge&logo=amazonec2)
![VPC](https://img.shields.io/badge/VPC-Network-blue?style=for-the-badge)
![Auto Scaling](https://img.shields.io/badge/Auto%20Scaling-Enabled-success?style=for-the-badge)
![RDS](https://img.shields.io/badge/Amazon-RDS-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

# 📌 Project Overview

This project demonstrates the deployment of a secure, scalable, and highly available **AWS 3-Tier Architecture** using Amazon Web Services.

The architecture separates the application into three independent layers:

- 🌐 Web Tier
- ⚙️ Application Tier
- 🗄️ Database Tier

The project follows AWS best practices by using **Public & Private Subnets**, **Application Load Balancers**, **Auto Scaling Groups**, and **Amazon RDS**.

---

# 🏗 Architecture

```
                     Internet
                         │
                         ▼
            Public Application Load Balancer
                         │
        ┌────────────────┴────────────────┐
        ▼                                 ▼
   Web Server 1                     Web Server 2
     (ASG)                            (ASG)
        │
        ▼
      Internal ALB
        │
   ┌────┴────┐
   ▼         ▼
 App Server 1   App Server 2
    (ASG)          (ASG)
        │
        ▼
   Amazon RDS (MySQL)
```

---

# 📸 Project Screenshots

## 🔹 VPC Resource Map

> Upload your VPC Resource Map screenshot here.

```
architecture/vpc-resource-map.png
```

---

## 🔹 Auto Scaling Groups

> Upload your Auto Scaling screenshot here.

```
architecture/auto-scaling-group.png
```

---

## 🔹 GitHub Repository

> Upload your GitHub Repository screenshot here.

```
architecture/github-repository.png
```

---

# ☁ AWS Services Used

- Amazon VPC
- Public Subnets
- Private Subnets
- Route Tables
- Internet Gateway
- NAT Gateway
- EC2
- Nginx
- Application Load Balancer
- Internal Application Load Balancer
- Auto Scaling Groups
- Amazon RDS
- Security Groups

---

# ⚙ Infrastructure Components

| Layer | Service |
|--------|---------|
| Web Layer | EC2 + Nginx |
| Load Balancer | Application Load Balancer |
| Application Layer | EC2 |
| Database Layer | Amazon RDS |
| Scaling | Auto Scaling Group |
| Networking | VPC |
| Security | Security Groups |

---

# 🔐 Security Features

- Private Application Servers
- Private Database
- Security Groups
- Public & Private Route Tables
- Multi Availability Zone Deployment
- Internet Gateway
- NAT Gateway

---

# 📈 High Availability

✅ Multi-AZ Deployment

✅ Application Load Balancer

✅ Auto Scaling Groups

✅ Highly Available Web Tier

✅ Private Database Layer

---

# 📂 Repository Structure

```
aws-3-tier-architecture/
│
├── architecture/
│   ├── vpc-resource-map.png
│   ├── auto-scaling-group.png
│   └── github-repository.png
│
├── README.md
└── .gitignore
```

---

# 📚 Learning Outcomes

- Designing AWS VPC
- Creating Public & Private Subnets
- Configuring Route Tables
- Deploying EC2 Instances
- Installing Nginx
- Configuring Load Balancers
- Configuring Auto Scaling Groups
- Connecting Amazon RDS
- Secure Network Design
- High Availability Architecture

---

# 💰 Cost Optimization

After completing the project, all AWS resources including:

- EC2 Instances
- Load Balancers
- Auto Scaling Groups
- NAT Gateway

were deleted to avoid unnecessary AWS charges.

---

# 👨‍💻 Author

## Uday Mali

🎓 MCA Student | AWS & DevOps Enthusiast | Cloud Learner

[![GitHub](https://img.shields.io/badge/GitHub-Maliuday-181717?style=for-the-badge&logo=github)](https://github.com/Maliuday)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Uday%20Mali-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/uday-mali-7aa1b7286/)

---

## 🤝 Connect With Me

- 🔗 GitHub: https://github.com/Maliuday
- 💼 LinkedIn: https://www.linkedin.com/in/uday-mali-7aa1b7286/ :contentReference[oaicite:0]{index=0}

---

## ⭐ Support

If you found this project useful, please consider giving this repository a **⭐ Star**.

It motivates me to build more real-world **AWS & DevOps** projects and share them with the community.

---

**Thank you for visiting this repository! 🚀**
