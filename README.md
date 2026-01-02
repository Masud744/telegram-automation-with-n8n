# Telegram Automation with n8n

This repository demonstrates a simple but practical **Telegram automation workflow built using n8n**.
The automation sends a Telegram message when the workflow is manually triggered.

---

## 🚀 What This Automation Does
- Manual trigger based execution
- Sends message to Telegram via Bot API
- Secure credential handling
- Shareable n8n workflow JSON

---

## 🛠️ Tech Stack
- n8n
- Telegram Bot API
- Docker

---

## 📂 Repository Structure
telegram-automation-with-n8n/
├── README.md
├── workflows/
│   └── manual-to-telegram.json
└── screenshots/
    └── telegram-message-success.png

---

## ⚙️ How to Run

### 1️⃣ Prerequisite
n8n must be running locally.
Setup guide:
https://github.com/Masud744/docker-n8n-local-setup

---

### 2️⃣ Import Workflow
Settings → Import workflow → Upload `manual-to-telegram.json`

---

### 3️⃣ Configure Telegram
- Add Bot Token in n8n Credentials
- Replace `YOUR_TELEGRAM_CHAT_ID`

---

### 4️⃣ Execute
Click **Execute workflow** to send message.

---

## 🔐 Security
No secrets are stored in this repository.

---

## 👤 Author
Masud – IoT & Automation Enthusiast
