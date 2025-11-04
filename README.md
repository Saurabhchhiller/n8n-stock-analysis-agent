# 🧠 n8n Stock Analysis Agent

An **AI-powered automation** built in [n8n](https://n8n.io/) that performs **technical stock analysis**, **chart generation**, and **Telegram-based interactions** using **OpenAI GPT-4o**, **Airtable**, and **Chart-img.com API**.

---

## 📘 Project Guide

[![View the Full PDF Guide](https://img.shields.io/badge/View%20Guide-PDF-blue?style=for-the-badge&logo=adobeacrobatreader)](./Building%20an%20n8n%20Stock%20Analysis%20Automation_%20Step-by-Step%20Guide.pdf)

You can read the full **step-by-step implementation guide** (includes screenshots and setup instructions) in the PDF above.

---

## 🚀 Features

✅ Real-time Telegram interaction (text + voice)  
✅ AI-driven stock chart interpretation using GPT-4o  
✅ Automatic chart generation via Chart-img API  
✅ Airtable integration for saving favorite tickers  
✅ Daily scheduled technical reports  
✅ Modular design with reusable sub-workflows

---

## ⚙️ Tech Stack

| Component | Purpose |
|------------|----------|
| **n8n** | Workflow automation |
| **OpenAI GPT-4o** | Technical analysis engine |
| **Telegram Bot API** | Chat-based interaction |
| **Airtable** | Ticker storage |
| **Chart-img.com API** | Chart visualization |

---

## 🧩 Architecture Overview

Telegram → n8n Trigger
│
├── Voice/Text Processing → OpenAI GPT-4o Agent
│ ├── Get Chart Tool → Chart-img API
│ ├── Save Ticker Tool → Airtable
│ └── Send Results → Telegram
│
└── Schedule Trigger → Airtable Tickers → Automated Analysis


---

## 💡 Future Enhancements

- Multi-timeframe (1D, 1W, 1M) analysis  
- Market news integration  
- Email alerts for RSI/MACD thresholds  
- Integration with Google Sheets or Notion  

---

## 👨‍💻 Author

**Saurabh Chhiller**  
Product Manager | Business Analyst | AI Automation Builder  
📍 San Francisco Bay Area  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/saurabhbusinessanalyst/)
