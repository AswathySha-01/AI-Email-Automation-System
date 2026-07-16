# 📧 AI Email Automation System

An AI-powered email automation workflow built with **n8n**, **OpenAI GPT-5 Mini**, **Gmail**, **Google Sheets**, and **Telegram**. It automatically reads incoming emails, classifies them using AI, sends appropriate replies, logs email details, and notifies administrators about high-priority messages.

## 🚀 Features

- 📧 Monitors unread Gmail emails
- 🤖 AI-based email classification
- ✉️ Automatic email replies
- 😊 Sentiment & language detection
- ⭐ Priority detection
- 📊 Google Sheets logging
- 📲 Telegram notifications for high-priority emails
- ⚠️ Error handling and alerts

## 🛠️ Technologies

- n8n
- OpenAI GPT-5 Mini
- Gmail API
- Google Sheets API
- Telegram Bot API

## 📂 Workflow

```
Gmail Trigger
      ↓
Extract Email Data
      ↓
AI Classification
      ↓
Route by Category
      ↓
Send Reply
      ↓
Log to Google Sheets
      ↓
Telegram Notification (High Priority)
```

## 📦 Installation

1. Import the workflow JSON into **n8n**.
2. Configure credentials for:
   - Gmail
   - OpenAI
   - Google Sheets
   - Telegram
3. Activate the workflow.

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, please give it a **Star** on GitHub!
