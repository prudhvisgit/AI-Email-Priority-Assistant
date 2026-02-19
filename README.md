<img width="1372" height="531" alt="image" src="https://github.com/user-attachments/assets/ee3a11a7-7abc-4914-ae56-edb76f9bfa56" />

#  AI Email Priority Assistant  
### Smart Gmail → Telegram Agent (Powered by Google Gemini & n8n)

An automated workflow built with **n8n** that monitors incoming Gmail messages, intelligently processes them using **Google Gemini AI**, filters out noise, and sends **only important, actionable notifications** to **Telegram**.

---

##  Overview

Inbox overload is real. This project transforms a cluttered Gmail inbox into **clean, meaningful Telegram alerts**.

Instead of receiving notifications for every email, this assistant:
- Reads emails using an LLM
- Understands their intent and priority
- Filters out spam or low-value messages
- Sends concise summaries or categorized alerts to Telegram

Perfect for professionals, students, and developers who want **focus over noise**.

---

##  Key Features

-  **Gmail Trigger**  
  Real-time monitoring of new emails (supports labels, senders, or custom filters)

-  **AI Agent (Google Gemini)**  
  Context-aware email understanding and summarization

-  **Structured Output**  
  Uses a structured output parser (e.g., JSON) for predictable, clean results

-  **Intelligent Filtering**  
  Prevents spam, promotions, or irrelevant emails from reaching Telegram

-  **Instant Telegram Delivery**  
  Sends only high-priority messages directly to your phone

---

##  Workflow Architecture

```text
Gmail Trigger
     ↓
Edit Fields (Pre-processing)
     ↓
Google Gemini AI Agent
     ↓
Structured Output Parser (JSON)
     ↓
Conditional Filter (Priority Check)
     ↓
Telegram Bot Notification
