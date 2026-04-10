# 🚀 EC2 Monitoring & Alerting System (AWS)

## 📌 Project Overview
Designed and implemented a monitoring and alerting workflow on AWS to simulate real-world cloud operations.

This project demonstrates how cloud systems detect performance issues and trigger automated notifications using AWS services.

---

## 🧱 Architecture

![Architecture](architecture.png)

---

## ⚙️ Services Used
- Amazon EC2 (Launch Template)
- Amazon CloudWatch (Metrics & Alarms)
- Amazon SNS (Notifications)

---

## 🔄 Workflow

1. EC2 instance launched using Launch Template  
2. CloudWatch continuously monitors CPU utilization  
3. Alarm triggers when threshold is exceeded  
4. SNS sends real-time email notification  

---

## 🧪 Testing

Simulated high CPU usage using:

```bash
stress --cpu 2 --timeout 180
