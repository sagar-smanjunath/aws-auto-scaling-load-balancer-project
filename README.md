# aws-auto-scaling-load-balancer-project
AWS high availability infrastructure using Auto Scaling Group, Application Load Balancer, EC2, and CloudWatch monitoring.

# AWS Auto Scaling and Load Balancer Configuration

## Project Overview

This project demonstrates the implementation of a highly available and scalable AWS infrastructure using Auto Scaling Groups and Application Load Balancer.

The setup automatically adjusts EC2 instance capacity based on workload demand and distributes incoming traffic across multiple servers to improve performance, scalability, and fault tolerance.

---

# Architecture

The architecture consists of:

* EC2 Instances
* Auto Scaling Group
* Launch Template
* Application Load Balancer
* Target Group
* CloudWatch Monitoring
* Security Groups

The infrastructure is designed to automatically scale resources and maintain high availability during varying traffic conditions.

---

# AWS Services Used

* Amazon EC2
* Auto Scaling Group
* Application Load Balancer (ALB)
* Launch Template
* CloudWatch
* Security Groups
* Target Groups

---

# Steps Performed

## 1. Created EC2 Launch Template

* Configured Amazon Linux EC2 template
* Defined instance type, AMI, key pair, and security group
* Added user data for automated instance configuration

## 2. Configured Application Load Balancer

* Created internet-facing Load Balancer
* Configured listener rules for HTTP traffic
* Attached Target Group for traffic distribution

## 3. Created Target Group

* Registered EC2 instances
* Configured health checks for availability monitoring

## 4. Configured Auto Scaling Group

* Attached Launch Template
* Configured minimum, desired, and maximum instance capacity
* Integrated Load Balancer with Auto Scaling Group

## 5. Configured Scaling Policies

* Enabled dynamic scaling based on CPU utilization
* Configured automatic scale-out and scale-in policies

## 6. Configured CloudWatch Monitoring

* Monitored CPU usage and instance performance
* Triggered scaling actions using CloudWatch alarms

## 7. Tested High Availability

* Verified automatic instance launch during high load
* Confirmed traffic distribution through Load Balancer
* Validated automatic scaling behavior

---

# Key Concepts Demonstrated

* High Availability Architecture
* Dynamic Infrastructure Scaling
* Load Balancing
* Cloud Monitoring
* Automated Resource Management
* Fault Tolerance
* AWS Compute Services

---

# Project Outcome

Successfully implemented a scalable and highly available AWS infrastructure capable of handling changing workloads automatically using Auto Scaling and Load Balancer services.

---

# Screenshots

Add all project screenshots inside the `screenshots` folder.

Example screenshots:

* Launch Template
* Auto Scaling Group
* Load Balancer
* Target Group
* CloudWatch Alarm
* EC2 Instances
* Scaling Policies
* Health Checks

---

# Author

Sagar S M

LinkedIn:
https://linkedin.com/in/sagar-sm

GitHub:
https://github.com/sagar-smanjunath
