# 🔐 Task 12: Log Monitoring & Analysis

## 📌 Overview
This repository demonstrates practical log monitoring and analysis to detect security incidents such as failed authentication attempts, anomalies, and suspicious behavior using system logs.

---

## 🛠 Tools Used
- Linux System Logs (`/var/log/auth.log`, `/var/log/syslog`)
- Windows Event Viewer (conceptual)
- SIEM Concepts (Splunk – Free)

---

## 🔍 What I Did
- Analyzed authentication and system logs
- Identified failed login attempts and suspicious patterns
- Detected anomalies based on time and frequency
- Correlated multiple events to identify potential incidents
- Learned SIEM alerting fundamentals

---

## 🚨 Key Security Indicators
- Multiple failed SSH login attempts
- Invalid user access attempts
- Repeated authentication failures from same IP
- Login anomalies during unusual hours

---

## 📊 Sample Commands
```bash
grep "Failed password" /var/log/auth.log
grep "Accepted password" /var/log/auth.log
```
---

📁 Repository Structure
Task-12-Log-Monitoring/

│── README.md

│── Log_Analysis_Report.docx / pdf

│── Screenshots/

---

🎯 **Learning Outcome**

- Developed incident detection and log analysis skills  
- Understood the importance of logs in security monitoring and investigations  
- Gained foundational knowledge of SOC operations and SIEM concepts 

---

👤 Author

Parijat Das

Cyber Security Intern

Blue Team | SOC Fundamentals
