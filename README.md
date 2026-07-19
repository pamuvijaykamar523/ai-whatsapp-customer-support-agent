# ai-whatsapp-customer-support-agent
AI-powered WhatsApp Customer Support System built with n8n, Twilio, Google Sheets, and Gemini AI.
🤖 AI WhatsApp Customer Support Agent

An AI-powered WhatsApp Customer Support System built using n8n, Twilio, Google Sheets, and Google Gemini AI.

This project automates customer support by answering common questions, detecting customer intent, logging conversations, and escalating requests to a human support agent when necessary.

---

🚀 Features

- 💬 AI-powered WhatsApp replies
- 🧠 Intent Detection (Pricing, Services, FAQ, Human Support)
- 📚 Knowledge Base using Google Sheets
- 📋 Customer CRM Logging
- 📅 Automatic Date & Status Tracking
- 👨‍💼 Human Support Escalation
- 📲 WhatsApp Notification to Support Staff
- 🔄 End-to-End Workflow Automation with n8n

---

🛠️ Tech Stack

- n8n
- Google Gemini AI
- Twilio WhatsApp API
- Google Sheets
- JavaScript (Code Node)

---

📌 Workflow

1. Customer sends a WhatsApp message.
2. AI analyzes the message and identifies the customer's intent.
3. FAQ, Pricing, and Service-related questions are answered automatically.
4. Customer details are stored in Google Sheets.
5. If Human Support is requested:
   - Customer receives an escalation message.
   - Support staff receives a WhatsApp notification.
   - CRM status is updated to Escalated.

---

📂 Project Structure

Webhook
   ↓
AI Agent
   ↓
Intent Detection
   ↓
IF Condition
   ├── FAQ / Pricing / Services
   │      ↓
   │   AI Reply
   │
   └── Human Support
          ↓
      Update CRM
          ↓
      Notify Support Staff

---

📸 Screenshots

Add screenshots of:

- n8n Workflow
- WhatsApp Conversation
- Google Sheets CRM

---

🔒 Security

API keys, credentials, authentication tokens, and sensitive information have been removed before publishing this repository.

---

🎯 Learning Outcomes

- Workflow Automation
- AI Integration
- WhatsApp Business Automation
- CRM Automation
- Google Sheets Automation
- API Integration
- Real-world No-Code Development

---

🚀 Future Improvements

- Conversation Memory
- Appointment Booking
- Customer History
- Email Notifications
- Admin Dashboard
- Multi-Business Support

---

👨‍💻 Author

Nani

Currently learning AI Automation and building real-world automation projects using n8n.

Feel free to connect with me on LinkedIn and explore my projects.
