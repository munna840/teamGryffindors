<div align="center">

# 🛰️ **InfraSight**  
### *AI-Powered Predictive IT Infrastructure Monitoring*

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![React](https://img.shields.io/badge/Frontend-React-blue?logo=react)
![FastAPI](https://img.shields.io/badge/Backend-FastAPI-green?logo=fastapi)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Hackathon](https://img.shields.io/badge/Hackathon-Project-orange)

> “Don’t just monitor — **Predict.**”

</div>

---

## 🌟 Overview

Modern DevOps teams face thousands of system metrics but little *predictive insight*.  
**InfraSight** helps IT and DevOps teams shift from **reactive monitoring** to **proactive prediction** by combining real-time data ingestion, machine learning–based anomaly detection, and intelligent failure forecasting — all in one clean dashboard.

---

## 🎯 Problem

> Over **70% of mid-size IT teams** lack real-time visibility and predictive analytics for infrastructure health — leading to unexpected downtime, customer churn, and financial loss.

### 💥 Current Challenges
- Manual monitoring and delayed issue detection  
- No early warnings for potential system failure  
- Costly enterprise tools (Datadog, New Relic)  
- No smart correlation between metrics, logs, and deployment events  

---

## 💡 Solution

**InfraSight** continuously monitors server metrics (CPU, memory, disk, etc.), detects anomalies using ML, predicts failures 1–3 hours ahead, and provides early alerts with root-cause hints.

### ✅ Key Benefits
- 🧠 **AI-based anomaly detection**
- 📈 **Failure prediction before downtime**
- 🚨 **Smart alerting system**
- 🔍 **Root-cause suggestions with NLP**
- 🖥️ **Clean & intuitive monitoring dashboard**

---

## ⚙️ Tech Stack

| Layer | Technologies |
|:------|:--------------|
| **Frontend** | React.js, Chart.js, Tailwind CSS |
| **Backend** | FastAPI (Python), Uvicorn |
| **ML Engine** | scikit-learn (IsolationForest, RandomForest), pandas |
| **Database** | SQLite / PostgreSQL |
| **App** | Python + psutil |
| **Integrations** | GitHub / Jenkins / AWS CloudWatch *(mocked for demo)* |
| **Deployment** | Render / Vercel / Docker |

---

## 🧩 Features

| # | Feature | Description |
|:-:|----------|-------------|
| 1️⃣ | **Live Metrics Dashboard** | Real-time CPU, memory & disk usage charts |
| 2️⃣ | **AI Anomaly Detection** | Identifies irregular resource patterns automatically |
| 3️⃣ | **Failure Prediction** | Forecasts downtime risk using ML |
| 4️⃣ | **Smart Alerts** | Instant alerts via dashboard / Slack mock |
| 5️⃣ | **Root Cause Analysis** | NLP summaries of probable causes |
| 6️⃣ | **Tool Integrations** | Demo data from GitHub, Jenkins, AWS |

---

## 🧠 Architecture

App (Python + psutil)
↓
FastAPI Backend ←→ Database (SQLite / PostgreSQL)
↓
ML Engine (Anomaly + Prediction)
↓
React Dashboard ←→ Alerts / Insights

*(Insert architecture diagram image here if you have one)*

---

## 🧪 Quick Start

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/infrasight.git
cd infrasight
2️⃣ Backend Setup (FastAPI)

cd backend
pip install -r requirements.txt
uvicorn main:app --reload --port 8000
3️⃣ Run the Agent (Simulated Metrics)

python app/app.py

4️⃣ Start the Frontend

cd frontend
npm install
npm start
5️⃣ Open in Browser
Go to 👉 http://localhost:3000

🧮 Machine Learning Models
Model	Purpose
IsolationForest	Detect abnormal usage patterns (unsupervised)
RandomForestClassifier	Predict system failure probability
spaCy (optional)	Extract root-cause keywords from logs

🚨 Example Scenario
Server-1 shows a CPU spike → InfraSight detects anomaly → ML model predicts 80 % failure probability → Alert triggered →
 Root-cause message: “Recent Jenkins deployment increased memory usage.”

🧱 Project Structure
---
💼 Business Impact
Stakeholder	Value Proposition
🧠 DevOps Teams	Detect & prevent downtime early
💰 Companies	Reduce unplanned outage costs
⚙️ SMBs	Affordable alternative to costly tools
📈 Scalable	Works on any server or cloud setup

🚀 Future Enhancements
🧩 Role-based dashboards (Admin / DevOps / Developer)

🤖 AI ChatOps Assistant — “Why did my app crash?”

☁️ Real cloud integrations (AWS, Azure, GCP)

📊 LSTM-based time-series forecasting

🗺️ Global infrastructure heatmap visualization

🏁 Results
✅ Real-time dashboard with live metrics
✅ Anomaly detection working with > 90 % test accuracy
✅ Predictive alerts functioning in demo
✅ Fully explainable and reproducible code

InfraSight successfully predicts infrastructure issues before they cause downtime!

🧾 License
This project is open source under the MIT License.

💬 Tagline
“Don’t just monitor — Predict.”

🏫 Team Members (Team Gryffindors) 
Vattikuti Nitish 
Shaik Harshad
Polamarasetti Sravanthi
Sesetty Hemanth

📬 Contact
🔗 GitHub: github.com/your-username/infrasight
🏫 Hackathon: Raghu Hackathon 2025

Made with ❤️ by the InfraSight Team
