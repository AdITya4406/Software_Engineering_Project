# Cyber Incident Reporting Portal (CIRP)

## 📌 Overview

The **Cyber Incident Reporting Portal (CIRP)** is a web-based application designed to provide organizations with a centralized and secure platform for reporting, tracking, investigating, and resolving cybersecurity incidents.

The system supports incident classification, evidence management, status tracking, notifications, SLA monitoring, audit trails, and AI-assisted features.

## 🎯 Objectives

- Provide a simple platform for reporting cyber incidents.
- Generate a unique tracking ID for each incident.
- Allow users to track incident status.
- Support incident classification and severity management.
- Enable analysts to investigate and assign incidents.
- Securely manage incident evidence.
- Maintain audit trails and SLA tracking.
- Provide dashboards and reports.
- Support AI-assisted classification, severity prediction, and duplicate detection.

## 👥 User Roles

- **Reporter:** Submit and track incidents.
- **Security Analyst:** Verify, classify, prioritize, and assign incidents.
- **IR Team Member:** Investigate and resolve assigned incidents.
- **Administrator:** Manage users, categories, settings, and audit logs.

## 🛠️ Technology Stack

- **Frontend:** React.js
- **Backend:** Node.js + Express.js
- **Database:** MongoDB
- **Authentication:** JWT / SSO
- **File Upload:** Multer
- **Charts:** Recharts
- **API Testing:** Postman
- **Version Control:** Git + GitHub

## 🔄 Incident Lifecycle

```text
Reported → Under Triage → Verified → Assigned
→ Investigating → Contained → Resolved → Closed
