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

- EC2 instance provisioned using Launch Template  
- CloudWatch collects and monitors CPU metrics  
- Alarm evaluates threshold breach conditions  
- SNS triggers notification upon state change
  
---

## 🧪 Testing

Simulated high CPU usage using:

```bash
stress --cpu 2 --timeout 180

```

## 📈 Outcome

Successfully implemented an end-to-end monitoring pipeline capable of detecting system stress and triggering real-time alerts.

##  🔗 Connect with Me www.linkedin.com/in/anasbinesa

If you found this useful or have suggestions, feel free to connect with me on LinkedIn.
