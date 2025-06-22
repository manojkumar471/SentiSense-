# 🤖🧠 SentiSense - Multi-Lingual Customer Feedback Analyzer

🔗 **Live Demo**: [Click Here](https://sensational-beignet-30ff32.netlify.app/)

---

## 💡 Overview

**SentiSense** is an intelligent AI-powered web application that processes customer feedback written in multiple languages.  
It automatically detects language, analyzes sentiment and emotion, extracts keywords, and presents all this in a clean real-time dashboard for e-commerce platforms.

🎯 Built for **CSI Anvesis 2025 Hackathon**, under Problem Statement PS2:  
*"Multi-Lingual Customer Feedback Analysis for E-Commerce."*

---

## 🚀 Features

- 🌍 Multi-language support (via `franc` + `compromise`)
- 💬 Sentiment and emotion analysis of each review
- ☁️ Keyword cloud generation
- 📊 Feature-wise sentiment breakdown charts
- 🚨 Alerts for high negative sentiment trends
- 🖥️ Real-time interactive dashboard
- 🔗 Fully deployed on Netlify for public access

---

## 🛠️ Tech Stack

| Layer        | Technology                             |
|--------------|------------------------------------------|
| Frontend     | React + TypeScript + Vite                |
| Styling      | Tailwind CSS                             |
| NLP Logic    | `franc`, `compromise`, `stopword`, `sentiment` |
| Charting     | Chart.js                                 |
| Deployment   | Netlify                                  |

---

## 📁 Folder Structure

\`\`\`

SentiSense/
│
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.ts
├── tsconfig.json
├── postcss.config.js
├── .gitignore
│
└── src/
├── App.tsx
├── main.tsx
├── index.css
├── vite-env.d.ts
│
├── data/
│   └── mockData.ts
│
├── types/
│   └── feedback.ts
│
├── services/
│   └── nlpProcessor.ts
│
└── components/
├── Dashboard.tsx
├── ReviewCard.tsx
├── AlertsPanel.tsx
├── KeywordCloud.tsx
├── SentimentChart.tsx
└── EmotionAnalysis.tsx

\`\`\`

---

## 🧪 How to Run Locally

\`\`\`bash
# 1. Clone the repository
git clone https://github.com/YOUR-USERNAME/SentiSense.git

# 2. Navigate to project folder
cd SentiSense

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
\`\`\`

---

## 📦 Deployment (Netlify)

This app is fully deployed using **Netlify**.

### Deployment Steps:

1. Connected GitHub repo to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `dist`
4. Automatic deployment from main branch 🚀

🔗 **Deployed Link:**
[https://sensational-beignet-30ff32.netlify.app/](https://sensational-beignet-30ff32.netlify.app/)

---

## 🔮 Future Scope

* 🧠 Use advanced LLMs (like mBERT/XLM-R) for backend sentiment
* 🗣️ Accept voice reviews → transcribe + analyze
* 📧 Auto-generate weekly sentiment reports for sellers
* 🧩 Plugin version for Shopify, WooCommerce
* 🌐 Backend support using Express + PostgreSQL

---

## 🛡️ License

Licensed under the **MIT License**.
