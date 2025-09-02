# AWS Scalable E-Commerce Infrastructure

## 📌 Project Overview
This project demonstrates how to build a highly available, secure, and cost-optimized e-commerce infrastructure on AWS using EC2, RDS, S3, IAM, and CloudWatch.

## ❗ Problem Statement
A retail company’s online store experienced downtime and performance issues during seasonal traffic spikes. They also lacked secure storage for media assets and proper access control.

## 🏗️ Architecture
- Custom VPC with public and private subnets
- Auto Scaling Group of EC2 instances behind an Application Load Balancer
- RDS PostgreSQL database in a private subnet
- S3 buckets for product images with lifecycle rules
- IAM roles and groups for secure access management
- CloudWatch dashboards and alarms for monitoring

## ✨ Features
- Auto-scaling to handle peak loads
- Database security in private subnets
- Cost-optimized storage with lifecycle rules
- Monitoring and alerts for system health

## 🚀 Setup Instructions
1. Clone this repo  
2. Provision infrastructure using Terraform
3. Deploy app code to EC2 or Elastic Beanstalk  
4. Configure IAM policies for developers and admins  

## 🛠 AWS Services Used
EC2, RDS, S3, IAM, CloudWatch, VPC, ELB, Auto Scaling

## ✅ Outcomes
- 99.9% uptime during traffic surges
- Secure data management with IAM and VPC isolation
- Reduced storage costs by ~20% with lifecycle policies
