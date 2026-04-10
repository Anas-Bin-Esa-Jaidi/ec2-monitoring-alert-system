![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![CloudWatch](https://img.shields.io/badge/Monitoring-CloudWatch-blue)
![SNS](https://img.shields.io/badge/Alerts-SNS-green)

# 🚀 EC2 Monitoring & Alerting System (AWS)

## 📌 Project Overview
Designed and implemented a monitoring and alerting workflow on AWS to simulate production-level observability and incident response.

This project demonstrates how cloud systems detect performance issues and trigger automated notifications using AWS services.

---

## 🎯 Why This Project Matters

In real-world cloud environments, monitoring is critical for ensuring system reliability and performance. 
Amazon CloudWatch enables tracking of system metrics, while alarms can trigger automated actions such as notifications via SNS. :contentReference[oaicite:0]{index=0}

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

## Connect with Me 🔗 www.linkedin.com/in/anasbinesa

If you found this useful or have suggestions, feel free to connect with me on LinkedIn.
