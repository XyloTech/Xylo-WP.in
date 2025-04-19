
# Xylo-WP.in  
**AI-Powered WhatsApp Chatbot Using Web Automation – 100% Free, No API Required**

## 🚀 Overview

**Xylo-WP.in** is a smart, human-like chatbot for WhatsApp built using React + Node.js + Puppeteer + AI (ChatGPT or local model).  
It works directly with WhatsApp Web – **no official API, no 3rd-party apps**, and 100% free to run on your own VPS or local server.

---

## 🧠 How It Works

1. **Frontend (React)** shows a QR code from WhatsApp Web.
2. You scan the QR code with your phone to link WhatsApp.
3. **Backend (Node.js + Puppeteer)** automates WhatsApp Web:
   - Reads incoming messages.
   - Sends the message to an AI Agent.
   - AI generates a human-like reply.
   - Bot types and sends the reply back via WhatsApp Web.

---

## 📁 Project Structure


xylo-wp-bot/
├── client/              # React frontend (QR display, status UI)
├── server/              # Node.js backend
│   └── puppeteer/       # WhatsApp automation logic
│   └── ai/              # AI reply generation logic
├── .env                 # API keys and config
└── README.md


---

## ⚙ Technologies Used

- **Frontend**: React, Axios
- **Backend**: Node.js, Express, Puppeteer
- **AI**: OpenAI API or Local Model (LM Studio / Ollama)
- **Others**: QR Code handling, VPS/Cloud support

---

## ✨ Features

- Connect WhatsApp with just a **QR code**
- **Reads messages** and replies like a real human
- Fully **automated with AI**
- Runs on any **VPS or Local Machine**
- **No API costs**, no limitations
- 100% customizable and extendable

---

## 🛠 Installation Guide

> Clone the repo

bash
git clone https://github.com/yourusername/xylo-wp-bot.git
cd xylo-wp-bot


> Setup Backend

bash
cd server
npm install
touch .env   # Add your OpenAI Key if using OpenAI


> Setup Frontend

bash
cd ../client
npm install
npm start


---

## ☁ Deployment

To deploy 24/7:
- Use a **VPS like DigitalOcean, Contabo, or AWS**
- Make sure Chrome/Puppeteer dependencies are installed
- Use **PM2 or Docker** to keep the bot alive

---

## ⚠ Disclaimer

This bot uses **WhatsApp Web automation**, which is not officially supported by WhatsApp. Use it for personal projects, learning, or controlled use-cases.

---

## 📌 Roadmap

- [ ] Multi-user support
- [ ] Admin panel to manage chats
- [ ] WhatsApp group replies
- [ ] Local AI model integration

---



## 🤝 Credits
This project was developed by the team at XyloTech, a software development agency committed to building smart, scalable, and future-ready tech solutions.

Team Members:

Harshit – Project Lead & Full Stack Developer

Ekansh Prajapati – Backend Developer (Node.js & Puppeteer)

Chitransh – Frontend & UI Engineer (React)

Ritoshree Saha – UI/UX Designer

Special Thanks To:

OpenAI for the AI models

Puppeteer for browser automation

The open-source community for continuous inspiration



 *Your Vision, Our Code – Building Smart Solutions for a Digital Future.*

---

## 📬 Contact

For commercial use or help:  
**Website**: [https://xylo.dev](https://xylotech.in)  
**Email**: contact@xylotech.in


---

Want me to generate a full GitHub repo structure with files next?
