# AWS VPC Design & Bastion Host Access

## 📅 Date
June 2025

## 🧰 Technologies Used
- **Amazon VPC**
- **Amazon EC2 (Ubuntu)**
- **Internet Gateway (IGW)**
- **NAT Gateway**
- **Security Groups & Network ACLs**
- **Key Pairs (SSH Access)**

## 📌 Project Overview

This project demonstrates how to **manually design and deploy** a secure and highly available AWS Virtual Private Cloud (VPC) using the **AWS Management Console**. The architecture includes public and private subnets across multiple Availability Zones. It uses a **bastion host** approach to securely SSH into private EC2 instances and verify internet access.

All configuration steps — from initial VPC creation to final connectivity tests — were done manually through the AWS Console. Screenshots for each major step are included in the `/screenshots` directory.

## 🛠️ Key Features

- ✅ **Manual VPC Setup (via AWS Console):**
  - Created a custom VPC with **public** and **private subnets** across multiple AZs.
- ✅ **Routing and Internet Configuration:**
  - Configured **route tables**, an **Internet Gateway**, and a **NAT Gateway**.
- ✅ **Bastion Host Access:**
  - Deployed **Ubuntu EC2 instances** in each subnet.
  - Used a **bastion host** in the public subnet for secure SSH access to the private EC2 instance via **key pair authentication**.
- ✅ **Security Hardening:**
  - Applied best practices using **Security Groups** and **Network ACLs**.
- ✅ **Connectivity Testing:**
  - Verified routing and connectivity by pinging `www.google.com` from both EC2 instances.

## 🖼️ Screenshots

Screenshots of each key step — from VPC creation, subnet setup, route configuration, EC2 launch, bastion access, and successful ping response — are available in the `/screenshots` directory.

## 📚 Learning Objectives

- Gain hands-on experience designing a secure VPC architecture in AWS Console
- Understand routing mechanisms using IGW and NAT
- Learn how to configure secure SSH access via a bastion host
- Apply traffic control using security groups and network ACLs
- Perform internet connectivity testing from EC2 instances


## 📬 Author

**Mohaned Mohamed**  
📍 Glasgow, United Kingdom  
📧 m.gorashi282@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/mohaned-mohamed-64674a45/) | [GitHub](https://github.com/Mohaned282?tab=repositories)
