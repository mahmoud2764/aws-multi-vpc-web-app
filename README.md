# AWS Multi-VPC Web Application

## Project Overview

This project demonstrates the deployment of a highly available and scalable web application on Amazon Web Services (AWS) using a Multi-VPC architecture.

The infrastructure separates the application and database environments into two different Virtual Private Clouds (VPCs), connected securely through VPC Peering. The web application runs on Amazon EC2 instances behind an Application Load Balancer (ALB) with Auto Scaling, while user data is stored in an Amazon RDS MySQL database.

---

## Architecture

Internet
↓
Application Load Balancer (ALB)
↓
Auto Scaling Group
↓
Amazon EC2 Instances
↓
VPC Peering
↓
Amazon RDS MySQL

---

## Features

- Multi-VPC Architecture
- Secure VPC Peering
- Public and Private Subnets
- Amazon EC2 Web Servers
- Amazon RDS MySQL Database
- Application Load Balancer
- Auto Scaling Group
- Launch Template
- User Registration
- User Login Authentication
- Secure Database Connectivity
- High Availability

---

## AWS Services Used

- Amazon VPC
- VPC Peering
- Amazon EC2
- Amazon RDS (MySQL)
- Application Load Balancer (ALB)
- Auto Scaling Group (ASG)
- Launch Template
- Security Groups
- Route Tables
- Internet Gateway
- IAM
- CloudWatch

---

## Project Workflow

1. Created two separate VPCs for application and database environments.
2. Configured VPC Peering for secure communication.
3. Created route tables and security groups.
4. Launched Amazon RDS MySQL in the Database VPC.
5. Created a Launch Template for EC2 instances.
6. Configured an Auto Scaling Group.
7. Created an Application Load Balancer.
8. Deployed the web application.
9. Connected the application to Amazon RDS.
10. Tested user registration and login functionality.

---

## Application Functionality

The web application allows users to:

- Register using a username and password.
- Store user information in Amazon RDS MySQL.
- Log in using registered credentials.
- Retrieve user data securely from the database.

---

## Screenshots

### Project Architecture

*(Insert architecture diagram here)*

---

### Amazon EC2 Instances

*(Insert EC2 screenshot here)*

---

### Amazon RDS

*(Insert RDS screenshot here)*

---

### VPC Peering

*(Insert VPC Peering screenshot here)*

---

### Launch Template

*(Insert Launch Template screenshot here)*

---

### Application Load Balancer

*(Insert ALB screenshot here)*

---

### Auto Scaling Group

*(Insert Auto Scaling screenshot here)*

---

### Registration Page

*(Insert Registration Page screenshot here)*

---

### Login Page

*(Insert Login Page screenshot here)*

---

### Database Records

*(Insert Database screenshot here)*

---

## Skills Demonstrated

- AWS Cloud Infrastructure
- Amazon VPC Networking
- VPC Peering
- EC2 Deployment
- Load Balancing
- Auto Scaling
- Amazon RDS
- Linux Administration
- Web Application Deployment
- MySQL Database Management
- Cloud Security
- High Availability
- Infrastructure Design

---

## Project Outcome

Successfully deployed a highly available cloud-based web application using AWS services. The infrastructure provides secure communication between application and database layers through VPC Peering, automatic scaling with Auto Scaling Groups, traffic distribution using an Application Load Balancer, and persistent data storage with Amazon RDS MySQL.

---

## Author

**Mahmoud Elzaneer Jebreel Elgoni**

Cloud Engineer | AWS Certified | DevOps Enthusiast
