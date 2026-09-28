# AWS CloudWatch & Grafana Monitoring Dashboard

## 📌 Project Overview

A hands-on AWS monitoring project focused on tracking the performance of EC2 instances and an Application Load Balancer (ALB) using **AWS CloudWatch and Grafana**.

The project demonstrates how cloud metrics can be collected, connected to a monitoring dashboard, visualized in real time, and validated through load testing and debugging.

### 🎯 Objective

The main objective was to build a centralized monitoring dashboard that makes it easier to observe:

- EC2 instance performance
- Network activity
- Load balancer traffic
- Successful HTTP requests
- Application latency
- Request patterns

This project provided practical experience with **AWS observability, CloudWatch metrics, Grafana dashboards, IAM configuration, dynamic monitoring, and troubleshooting**.

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Cloud Platform | AWS |
| Compute | EC2 |
| Load Balancing | Application Load Balancer (ALB) |
| Monitoring | AWS CloudWatch |
| Visualization | Grafana |
| Access Management | AWS IAM |
| Scripting | Python, Bash |
| Other AWS Services | S3, RDS, Glue |

---

## 🏗️ Architecture

```text
              AWS EC2 Instance
                    │
                    │
             Application Traffic
                    │
                    ▼
          Application Load Balancer
                    │
                    │
                    ▼
             AWS CloudWatch
                    │
             Metrics & Logs
                    │
                    ▼
               Grafana
                    │
                    ▼
          Monitoring Dashboard

This project helped me gain hands-on experience in cloud monitoring, AWS observability, and real-time dashboarding! 🎯
