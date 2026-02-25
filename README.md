# RFQ-Automation-System

# AI-Powered RFQ Automation & Quotation System

An end-to-end AI automation system that automatically processes RFQ (Request for Quotation) emails, extracts structured data using AI, stores records, manages attachments, notifies teams, and prepares quotation workflows.

---

##  Project Overview

This project automates the complete RFQ handling process typically performed manually by sales teams.

When a client sends an RFQ email:

✅ Email is detected automatically  
✅ AI extracts structured RFQ data  
✅ Data stored in Google Sheets (CRM log)  
✅ Attachments uploaded to Google Drive  
✅ Auto acknowledgement email sent to client  
✅ Sales team notified instantly via Slack  
✅ Ready for quotation generation API

---

## System Architecture

Client Email → Gmail Trigger
        ↓
AI Data Extraction
        ↓
Google Sheets Storage
        ↓
Google Drive Upload
        ↓
Auto Reply Email
        ↓
Slack Notification


---

## 🤖 AI Extraction

AI automatically extracts:

- Client Name
- Email
- Phone Number
- Product SKU
- Quantity
- Delivery Location
- Delivery Timeline
- Language
- Email Subject

Example AI Output:

```json
{
  "client_name": "Gulf Engineering",
  "email": "omar@client.com",
  "phone": "+966500000",
  "item_sku": "ALR-SL-90W",
  "quantity": 120,
  "location": "Riyadh",
  "delivery_time": "4 weeks",
  "language": "EN"
}```

---
### Automation Workflow (Zapier)
Step 1 — Gmail Trigger

Detect new RFQ emails automatically.

Step 2 — AI by Zapier

Extract structured RFQ information from email body.

Step 3 — Formatter

Clean and standardize extracted values.

Step 4 — Google Sheets

Create RFQ record database.

Step 5 — Google Drive

Upload client attachments automatically.

Step 6 — Auto Email Reply

Send confirmation email to client.

Step 7 — Slack Notification

Notify internal sales team instantly.


## ✅ Key Features

AI-powered document understanding

Zero manual RFQ processing

Automated sales workflow

Scalable microservice architecture

Production-style automation design


