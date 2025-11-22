# 🛡️ CyberSecure — AI/ML Intrusion Detection & Real-Time Threat Triage  
📍 Built in 24 Hours during **REDACT Cybersecurity Hackathon (2025)**

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Streamlit](https://img.shields.io/badge/UI-Streamlit-FF4B4B.svg)
![ML Model](https://img.shields.io/badge/Model-XGBoost-orange.svg)

CyberSecure is a **real-time Intrusion Detection System (IDS)** that classifies network traffic as **Benign** or **Intrusion**, assigns a **confidence score**, and automatically recommends **security response actions**.  
Built using a **high-recall ML model**, this system ensures **no intrusion goes undetected**, enabling fast and intelligent SOC triage.

> ❗ In cybersecurity, missing a single attack can be catastrophic.  
> That’s why **Intrusion Recall** is our top priority metric.

---

## 🎯 Hackathon Problem Statement — REDACT (PS-02)

**Goal:** Build an ML-based IDS using tabular network flow features to detect malicious behavior and automate action-based triage.

Implemented requirements:
- ✔ Binary classification: Intrusion vs Benign  
- ✔ Confidence Score + Automated Security Actions  
- ✔ Live Dashboard for SOC triage  
- ✔ High Recall optimization  
- ✔ Tamper-proof Blockchain Logging *(Bonus)*  
- ✔ Explainable AI *(Bonus)*  

**100% features + bonuses delivered 🎯🔥**

---

## 🚀 Key Features

| Feature | Description |
|--------|-------------|
| 🤖 High-Recall XGBoost Classifier | Prioritizes detecting all attacks |
| ⚠️ Automated Triage Responses | Block / Throttle / Quarantine / Allow |
| 📊 Streamlit SOC Dashboard | Live threat feed, alerts, metrics |
| 🔐 Blockchain-Backed Logging | SHA-256 chained incident records |
| 🧠 Explainable AI | Feature importance for trust |
| 🧪 Offline Batch Prediction | Large dataset support |
| 📁 Metrics Export | Excel + CSV reporting for evaluation |

---

## 📈 Model Performance Highlights  
*(Based on CIC-IDS2017 test flows)*

| Metric | Status |
|--------|--------|
| Recall (Intrusion Class) | ⭐ Optimized (Primary Success Metric) |
| Precision | Logged |
| F1 Score | Logged |
| ROC-AUC | Computed |
| PR-AUC | Computed |

Complete results stored as:  
`data/xgb_high_recall_full_metrics.xlsx`  

Includes:
- Confusion Matrix  
- ROC Curve Data  
- PR Curve Data  
- Full Classification Report  

---

## 🔐 Automated Security Action Logic

| Confidence % | Classification | Security Action |
|-------------|----------------|----------------|
| > 90% | Intrusion | 🚫 Block Source IP |
| 60–90% | Intrusion | ⚠️ Throttle Traffic |
| < 60% | Intrusion | 🕵️ Quarantine Endpoint |
| Any | Benign | ☑ Allow |

Mimics SOC Tier-1 triage decisions.

---

## 🖥️ Streamlit Dashboard

Includes:
- **Live Threat Feed**
- **Blockchain Ledger Viewer**
- **Metrics Dashboard**
- **Explainability Insights**

### ▶️ Run Command

```bash
pip install -r requirements.txt
streamlit run app.py
Open UI in browser:
👉 http://localhost:8501/
⛓️ Blockchain-Based Intrusion Ledger (Bonus)

Each detected intrusion is:

Hashed using SHA-256

Linked with previous block hash

Stored in chain.json

Tampering = Immediate integrity break
→ Supports cyber forensics

##📂 Repository Structure
