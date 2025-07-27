# 📊 PowerBI Dashboard with AI Insights

This repository contains a **PowerBI-based data analytics dashboard** integrated with an **AI-powered insights engine**.  
The dashboard visualizes key metrics using **PowerBI reports** while the backend generates **plain-language summaries and trends** using **OpenAI or Hugging Face models**.

---

## 🚀 Features
- **Interactive PowerBI Dashboards** – Embedded directly in the web interface.
- **AI Insights Generation** – Summarizes key trends and anomalies from data.
- **REST API for Analytics** – Backend endpoints to fetch data and generate insights.
- **Responsive UI** – Built using **Next.js (React)** for a modern and fast experience.
- **Secure Token-Based Access** – Integration with **PowerBI REST API and Embed tokens**.

---

## 🛠️ Tech Stack
- **Frontend:** Next.js (React + TypeScript), PowerBI Client SDK
- **Backend:** FastAPI (Python)
- **AI Engine:** OpenAI API / Hugging Face Transformers
- **Visualization:** PowerBI Embedded Reports
- **Styling:** Tailwind CSS (or your preferred UI framework)

---

## 📂 Project Structure


---

## ⚙️ Setup Instructions

### **1. Backend (FastAPI)**
```bash
cd backend
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload


## ⚙️ Setup Instructions

### **1. Backend (FastAPI)**
```bash
cd backend
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload


cd frontend
npm install
npm run dev
<PowerBIEmbed
  embedUrl="YOUR_EMBED_URL"
  accessToken="YOUR_EMBED_TOKEN"
  reportId="YOUR_REPORT_ID"
/>
{
  "metrics": {
    "total_sales": 120000,
    "qoq_growth": 15,
    "top_region": "North America"
  }
}

---

### **Would you like me to create a "starter GitHub project" (Next.js + FastAPI + PowerBI Embed) with this README and sample code in one ZIP?**

