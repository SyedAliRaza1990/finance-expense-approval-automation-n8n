# 📊 Finance Automation Workflow using n8n

This project demonstrates a finance automation workflow built with **n8n**. It automates reminder emails, updates records in Google Sheets, and eliminates repetitive manual tasks using a no-code automation platform.

---![n8n](https://img.shields.io/badge/n8n-Automation-orange)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-Connected-success)
![Gmail](https://img.shields.io/badge/Gmail-Automated-red)
![License](https://img.shields.io/badge/License-MIT-blue)

## 📖 Overview

The workflow reads financial records from Google Sheets, checks predefined conditions, sends automated email reminders, updates the sheet with the latest status, waits for a specified period, and sends a final notification. The automation improves efficiency, reduces manual effort, and ensures timely communication.

---

## 🖼️ Workflow Screenshot

![Finance Automation Workflow](workflow.png)

---

## 💼 Business Problem

Finance teams often spend hours checking spreadsheets, tracking pending records, and sending manual reminder emails. This repetitive work increases the risk of delays, missed follow-ups, and human error.

---

## ✅ Solution

This n8n workflow automates the complete reminder process by:

- Reading data from Google Sheets
- Checking conditions using IF logic
- Sending automated Gmail notifications
- Updating records automatically
- Waiting for a defined period
- Sending follow-up reminder emails

---

## 🏗️ Workflow Architecture

```text
Manual Trigger
      │
      ▼
Read Google Sheets
      │
      ▼
IF Condition
      │
      ▼
Send Gmail Reminder
      │
      ▼
Update Google Sheet
      │
      ▼
Wait
      │
      ▼
Send Final Email
```

---

## 🛠️ Tools Used

- n8n
- Google Sheets
- Gmail
- IF Node
- Wait Node

---

## ✨ Features

- Automated finance reminders
- Conditional workflow logic
- Google Sheets integration
- Gmail email automation
- Automatic status updates
- Scheduled follow-up emails
- No-code workflow automation

---

## ⚙️ How It Works

1. The workflow starts manually.
2. Records are retrieved from Google Sheets.
3. The IF node checks the required condition.
4. Eligible users receive an automated email.
5. Google Sheets is updated with the latest status.
6. The workflow waits for the configured time.
7. A final reminder email is sent automatically.

---

## 🚀 Future Improvements

- QuickBooks Integration
- Xero Integration
- AI-based Invoice Processing
- Slack Notifications
- Microsoft Teams Integration
- Power BI Dashboard
- ERP Integration

---

## 👤 Author

**Syed Ali Raza**

Finance & Accounts Professional | Business Analyst | AI Automation Enthusiast

- 💼 10+ Years of Experience in Finance & Accounts
- 🤖 Learning AI & Workflow Automation
- 🌍 Open to Remote Opportunities

