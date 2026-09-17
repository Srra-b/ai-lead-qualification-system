# 🚀 AI Lead Qualification & Automated Routing System (n8n)

An automated AI-driven lead scoring and qualification system built with **n8n**, **Google Gemini AI**, **Google Sheets**, and **Gmail**.

## 🎬 Live Project Demo

Watch the video walk-through to see the AI Lead Qualification System processing leads, updating Google Sheets, and sending emails in real-time:

[![Watch the Demo](https://cdn.loom.com/sessions/thumbnails/1546c5ac7fcb422f988ed8e1fba2d669-with-play-3000.gif)](https://www.loom.com/share/1546c5ac7fcb422f988ed8e1fba2d669)

👉 **[Click here to watch the full demo on Loom](https://www.loom.com/share/1546c5ac7fcb422f988ed8e1fba2d669)**

---

## 📌 Features

- **Automated Lead Capture**: Receives incoming submissions dynamically via Form Webhooks.
- **AI-Powered Qualification**: Uses Google Gemini to analyze budget, company size, and business goals to compute a dynamic `Lead Score` (0-100).
- **Structured Data Logging**: Saves lead information, AI status, and reasoning directly into Google Sheets.
- **Smart Conditional Routing**: Uses an `If` branching node to evaluate lead thresholds (>=70).
- **Automated Email Messaging**: Sends acceptance emails to high-value leads and low-priority emails to non-qualifying responses.

---

## 🛠️ Tech Stack

- **Automation Engine**: n8n
- **AI Model**: Google Gemini (Basic LLM Chain)
- **Database**: Google Sheets API
- **Email Delivery**: Gmail API

---

## 📂 Repository Contents

- `AI Lead Qualification System.json` - Complete exported n8n workflow.
- Screenshots of Form submission, Google Sheets output, and Gmail delivery.
