# 📥 AI Lead Qualification & Automated Routing System

An automated AI-driven lead scoring and qualification system built with **n8n**, **Google Gemini AI**, **Google Sheets API**, and **Gmail API**. It captures incoming sales leads, evaluates their qualification status using generative AI, logs structured data, and routes tailored response emails based on lead priority.

---

## 📽️ System Live Demo
📺 **[Click Here to Watch the Live Demo Video](https://www.loom.com/share/1546c5ac7fcb422f988ed8e1fba2d669)**

---

## 📸 System Screenshots & Visual Proof

| n8n Workflow Canvas | Google Sheets Database | Gmail Response |
| :---: | :---: | :---: |
| ![Workflow](./workflow-screenshot.png) | ![Database](./Sheets-screenshot.png) | ![Email](./email-screenshot.png) |

---

## 🔑 Key Features
* **Real-Time Webform Trigger**: Captures submissions instantaneously without manual intervention.
* **AI-Powered Lead Scoring**: Leverages Google Gemini AI to analyze budget, company size, and challenge context to generate a dynamic score (0-100).
* **Structured Data Logging**: Appends incoming lead details, dynamic AI scores, and qualification reasoning into a Google Sheets document.
* **Smart Conditional Branching**: Evaluates score thresholds ($\ge 70$) using an `If` routing node.
* **Automated Email Outreach**: Sends personalized outreach emails to qualified leads and polite follow-up messages to low-priority prospects via Gmail API.

---

## 🛠️ Tech Stack
* **Workflow Engine**: n8n
* **AI Engine**: Google Gemini (Basic LLM Chain)
* **Database / CRM**: Google Sheets API
* **Email Engine**: Gmail API (OAuth 2.0)

---

## 🎯 Business Impact & Value
* **Instant Response Time**: Eliminates manual delay by analyzing and responding to leads in seconds.
* **Higher Conversion**: Ensures high-priority prospects are flagged immediately for the sales team.
* **Data-Driven Insights**: Provides clear AI-generated reasoning for every qualified lead.
