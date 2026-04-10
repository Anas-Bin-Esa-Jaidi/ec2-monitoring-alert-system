# 🚀 EC2 Monitoring & Alerting System (AWS)

## 📌 Overview
This project demonstrates a simple monitoring and alerting system built on AWS using EC2, CloudWatch, and SNS.

The goal was to simulate how real-world systems monitor performance and trigger alerts based on defined thresholds.

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
2. CloudWatch monitors CPU utilization  
3. Alarm triggers when CPU exceeds threshold  
4. SNS sends real-time email notification  

---

## 🧪 Testing

To simulate high CPU usage:

```bash
stress --cpu 2 --timeout 180
