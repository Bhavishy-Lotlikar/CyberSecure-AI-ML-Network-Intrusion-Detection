# 🛡️ CyberSecure — AI/ML Intrusion Detection & Real-Time Threat Triage  
📍 Built in 24 Hours during **REDACT Cybersecurity Hackathon (2025)**

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Streamlit](https://img.shields.io/badge/UI-Streamlit-FF4B4B.svg)
![ML Model](https://img.shields.io/badge/Model-XGBoost-orange.svg)

CyberSecure is a **real-time Intrusion Detection System (IDS)** powered by **Machine Learning** and designed for **SOC-level threat response automation**.

It classifies network traffic as **Benign** or **Intrusion**, assigns a **confidence score**, and instantly recommends **security actions** based on the severity of detected malicious activity.

> ❗ In cybersecurity, **missing an attack is never acceptable** —  
> so this system prioritizes **High Recall** over everything else.

---

## 🎯 Hackathon Problem Statement (REDACT 2025)

Develop an ML-based IDS using tabular network flow features  
to detect cyber intrusions in real time and automate first-level triage.

Key Requirements:

- Binary classification: Benign vs Intrusion  
- **High Recall** for malicious class  
- Security action logic based on model confidence  
- Live dashboard to monitor threats  
- Bonus: Blockchain logging & XAI

This project successfully implements **all** requirements + bonuses ✔️

---

## 🚀 Key Features

| Feature | Description |
|--------|-------------|
| 🤖 AI-based Intrusion Detection | High-recall optimized XGBoost model |
| 🎯 Confidence-Aware Triage | Block / Throttle / Quarantine / Allow actions |
| 📊 Live Dashboard | SOC-style Streamlit UI with threat feed |
| 🔐 Blockchain-Backed Logging | Tamper-proof forensic evidence chain |
| 🧠 Explainability | Global feature importance + flow-level reasoning |
| 📈 Exportable Metrics | One-click CSV/Excel reports for judges |
| 🧪 Offline Evaluation | Batch inference support with large datasets |

---

## 🧠 Model Performance (Focus: Intrusion Recall)

| Metric | Tracked |
|--------|:------:|
| Recall (Class 1) | ✔ Optimized |
| Precision | ✔ Reported |
| Accuracy | ✔ Reported |
| F1 Score | ✔ Reported |
| ROC AUC | ✔ Logged |
| PR AUC | ✔ Logged |

Complete results are exported to:

📁 `data/xgb_high_recall_full_metrics.xlsx`  
📁 metric CSVs also included in `data/` folder  

---

## 🔥 Automated Security Actions

| Condition | Assigned Action |
|---------|----------------|
| Intrusion & Confidence > 90% | 🚫 Block Source IP |
| Intrusion & Confidence 60–90% | ⚠️ Throttle Port Traffic |
| Intrusion & Confidence < 60% | 🕵️ Quarantine Endpoint |
| Benign | ☑ Allow & Monitor |

Mimics automated SOC decision-making.

---

## 🖥️ Streamlit Dashboard Views

- **Live Threat Feed** → flow logs + confidence + recommended action  
- **Blockchain Ledger** → hashed and linked intrusion records  
- **Metrics Dashboard** → KPIs, Confusion Matrix, ROC & PR curves  
- **Explainability** → Feature importance and flow inspection  
