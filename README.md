

# 💰 AR Priority Engine — Enterprise Receivables Dashboard

[![Streamlit](https://img.shields.io/badge/Live_Demo-FF6B35?logo=streamlit&logoColor=white)](https://ar-priority-engine-79rxtptbghzcpwfbelvygr.streamlit.app/)

A fast, interactive Streamlit app that transforms messy AR files into clear priorities, risk insights, and ready‑to‑send collection emails.  
Built for finance teams who need speed, automation, and accuracy.

---

## 🚀 What It Does (Quick Overview)
- Upload CSV/Excel AR exports  
- Auto‑map Customer / Amount / Date columns  
- Clean 25+ date formats + Excel serials  
- Compute DSO, CEI, AR Turnover, 90+% exposure 
- Rank customers using a vectorized priority scoring model 
- Classify invoices into 6 risk tiers 
- Visualize customer concentration risk  
- Generate professional/urgent email templates 
- Export a clean priority list for collections teams  

---

## 📊 Why It’s Useful
Most AR teams spend hours manually:
- Cleaning files  
- Rebuilding aging buckets  
- Prioritizing follow‑ups  
- Writing collection emails  

This app automates all of it — consistently and instantly.

---

## 🧠 Key Features
- Enterprise KPIs: DSO, CEI, AR Turnover, 90+ %, Median Days Late  
- Risk Ladder: 🛑 120+ → 🔴 91–120 → 🟡 61–90 → 🟠 31–60 → 🟢 0–30 → ✅ Current  
- Priority Engine: Amount × Days Overdue × Weighted urgency  
- Customer Concentration Dashboard (Plotly)  
- Email Generator: Professional, Friendly, or Urgent tone  
- AI‑style Collections Strategy

---

## 🏗 Tech Stack
- Python, Pandas, NumPy 
- Streamlit (UI)  
- Plotly (visuals)  
- OpenPyXL (Excel ingestion)  

Handles 50,000+ rows with fully vectorized operations.

---

## 🛠 Run Locally
```bash
pip install -r requirements.txt
streamlit run ar_priority_engine.py
```

---

## ⭐ What This Project Demonstrates
- Strong Python + data engineering skills  
- Finance domain expertise (AR, aging, KPIs)  
- Ability to build and deploy real products  
- Clean UI/UX and workflow design  
- Production‑ready logic and error handling  

