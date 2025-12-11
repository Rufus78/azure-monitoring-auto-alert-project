# 📘 Azure Monitoring & Auto-Alert System (Azure Portal Project)

This project demonstrates a **real-world Azure Monitoring and Alerting
setup** using the **Azure Portal only** --- no CLI or PowerShell. It
simulates a production-like environment with VM monitoring, diagnostics
logging, metric alerts, email notifications, snapshots, and cost
control.

------------------------------------------------------------------------

## 🚀 Architecture Overview

    Resource Group (rg-monitoring-project)
    │
    ├── Virtual Network (vnet-project)
    │     └── Subnet (subnet-web)
    │
    ├── Virtual Machine (vm-webserver)
    │     ├── Web Server (Apache/IIS)
    │     ├── Boot Diagnostics
    │     ├── Metrics & Logs → Storage Account
    │     └── Snapshot (Backup)
    │
    ├── Storage Account (monitorstore)
    │     └── Stores VM diagnostics & metrics
    │
    ├── Azure Monitor
    │     └── Metric Alert (CPU > 80%)
    │
    └── Action Group (Email Notification)

------------------------------------------------------------------------

## 🧱 Project Features

### 🔹 1. Azure Infrastructure Setup

-   Resource Group\
-   Virtual Network & Subnet\
-   Linux/Windows VM\
-   Network Security Basics (SSH/RDP allowed)

### 🔹 2. Web Server Deployment

-   Apache (Linux) or IIS (Windows) installed using Run Command

### 🔹 3. Monitoring & Alerting

-   Boot diagnostics enabled\
-   Diagnostics logs sent to Storage Account\
-   Metric Alert created (CPU \> 80%)\
-   Action Group configured (email notification)\
-   Alert successfully triggered and received

### 🔹 4. Backup & Recovery

-   VM OS Disk Snapshot created

### 🔹 5. Cost Management

-   Monthly Budget created\
-   80% usage alert configured

------------------------------------------------------------------------

## 📄 Documentation

This repository contains:

📄 **Azure_Monitoring_Project_Documentation.docx**

------------------------------------------------------------------------

## 📸 Screenshots

Place your screenshots inside a folder named:

📁 **/screenshots**

Suggested screenshots: - Resource Group\
- VNet\
- VM Overview\
- Run Command (Apache/IIS setup)\
- Diagnostic Settings\
- Storage Logs\
- Alert Rule\
- Action Group\
- Alert Trigger Email\
- Snapshot\
- Budget Alert

------------------------------------------------------------------------

## 🧠 Skills Demonstrated

-   Azure VM Deployment\
-   Azure Networking\
-   Azure Storage\
-   Monitoring & Alerts\
-   Action Groups\
-   Diagnostics & Logging\
-   Backup (Snapshot)\
-   Cost Optimization\
-   Incident Monitoring\
-   Azure Portal Proficiency

------------------------------------------------------------------------

## 🎯 Resume-Ready Project Summary

Implemented an **end-to-end Azure Monitoring & Auto-Alert system** using
the Azure Portal.\
Configured VM diagnostics, storage logging, metric alerts, action
groups, and backup snapshots.\
Successfully tested the alert mechanism by creating artificial CPU
load.\
Demonstrated Azure administration, monitoring, backup, and incident
response skills.

------------------------------------------------------------------------

## ❓ Interview Questions (with Answers)

### **1. What triggered your alert?**

CPU usage exceeded the configured threshold (80%).

### **2. Why do we send diagnostics logs to a Storage Account?**

For long-term retention, auditing, alerting, and analysis.

### **3. What is an Action Group?**

Notification settings (email/SMS/webhook) that execute when an alert
fires.

### **4. Why take a Snapshot?**

For quick VM disk recovery or rollback.

### **5. How did you test the alert?**

Generated high CPU load using stress commands/Task Manager.

### **6. What's the importance of Budget Alerts?**

Prevent unexpected Azure costs by notifying when usage exceeds limits.

------------------------------------------------------------------------

## ⭐ Future Enhancements

-   Add Azure Log Analytics Workspaces\
-   Deploy multi-VM architecture\
-   Configure Azure Load Balancer\
-   Add Application Insights\
-   Automate backup using Recovery Services Vault

------------------------------------------------------------------------

## 📬 Contact

samuelrufusm@outlook.com
