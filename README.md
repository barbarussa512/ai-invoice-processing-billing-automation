# 🧾 AI Invoice Processing & Billing Automation

An AI-powered invoice processing workflow built with **n8n** that automatically detects new invoices uploaded to Google Drive, extracts structured data using AI, stores billing information in Google Sheets, and sends automated billing emails.

---

## 🚀 Features

- 📂 Detects newly uploaded invoices in Google Drive
- 📄 Extracts text from PDF invoices
- 🤖 AI-powered invoice understanding using LLMs
- 💰 Extracts invoice details automatically
- 📊 Stores invoice data in Google Sheets
- 📧 Sends automated billing emails
- ⚡ Fully automated workflow with n8n
- ❌ Built-in error notification workflow

---

## 🛠 Tech Stack

- n8n
- OpenRouter LLM
- Google Drive API
- Google Sheets API
- Gmail API
- PDF Extraction
- AI Automation

---

## 📷 Workflow

![Workflow](screenshots/ai-invoice-processing.png)

---

## 🏗 Workflow Architecture

```text
Google Drive Trigger
        │
        ▼
Download Invoice
        │
        ▼
Extract Text From PDF
        │
        ▼
AI Invoice Analysis
        │
        ▼
Extract Invoice Fields
        │
        ▼
Store Data in Google Sheets
        │
        ▼
Generate Billing Summary
        │
        ▼
Send Billing Email
```

---

## 📂 Project Structure

```text
.
├── workflow
│   └── AI-Powered Invoice Processing & Billing Automation.json
│
├── screenshots
│   └── ai-invoice-processing.png
│
└── README.md
```

---

## ⚙ Installation

1. Import the workflow JSON into n8n.
2. Configure your Google credentials.
3. Configure your OpenRouter API key.
4. Configure Google Sheets.
5. Configure Gmail.
6. Activate the workflow.

---

## 📌 Workflow Overview

1. Detect a newly uploaded invoice in Google Drive.
2. Download the invoice automatically.
3. Extract text from the PDF.
4. Send extracted content to an LLM.
5. Extract structured invoice information.
6. Save invoice data into Google Sheets.
7. Generate a billing summary.
8. Send the billing email automatically.
9. Trigger error notification if the workflow fails.

---

## 🎯 Use Cases

- Invoice Processing
- Billing Automation
- Finance Automation
- Accounting Workflows
- AI Document Processing
- Back-office Automation

---

## 👨‍💻 Author

Mahmoud Al-Durayni

AI Automation Developer

- AI Agents
- Workflow Automation
- n8n
- Retrieval-Augmented Generation (RAG)
- LLM Integrations

