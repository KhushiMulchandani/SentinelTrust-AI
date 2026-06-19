# SentinelTrust AI

**An Intelligent, Privacy-First Risk-Scoring Middleware for Digital Banking Channels.**  

---

## 🚀 Project Overview
SentinelTrust AI is a dynamic, "Zero Trust" continuous identity validation framework designed to prevent **Account Takeover (ATO)** and digital banking fraud. Instead of constantly interrupting legitimate users with static MFA challenges, SentinelTrust AI silently monitors non-invasive behavioral telemetry and device background signals. It triggers step-up authentication *only* when an anomaly pushes the calculated risk score beyond a safe threshold.

### Key Features
* **Continuous Behavioral Telemetry:** Tracks session navigation pace, device type, network parameters, and access time anomalies.
* **Real-Time Risk Scoring Engine:** Processes user footprint data against historical baselines to generate a risk score (0-100).
* **Friction-Optimized Adaptive Auth:** Delivers a seamless experience for low-risk actions while dynamically step-up verifying elevated risks.

---

## 🛠️ Technology Stack
* **Backend Framework:** Python, Django (REST API Architecture)
* **Data Analysis & ML:** NumPy (for mathematical matrix operations and analytical array processing), Scikit-Learn (for anomaly detection algorithms)
* **Frontend Interface:** HTML5, CSS3, JavaScript (ES6+), Bootstrap
* **Database:** PostgreSQL / SQLite (for secure session log storage and relational user profiles)

---

## 📐 Architecture & Workflow
1. **Telemetry Capture:** Client-side scripts collect device and behavioral metrics.
2. **Secure Ingestion:** Data is transmitted via secure API endpoints to the Django backend.
3. **Risk Evaluation:** The Python ML module processes features against historical baselines using NumPy.
4. **Decision Matrix Execution:**
   * **Score < 30 (Low Risk):** Allow Transaction seamlessly.
   * **Score 30 - 70 (Medium Risk):** Trigger Dynamic Step-Up Verification (MFA/Biometrics).
   * **Score > 70 (High Risk):** Block Session & Flag for Bank Fraud Team.

---

## 👥 Team Members
* **Khushi Mulchandani** - Frontend, Backend & ML Integration (LJ Institute of Engineering & Technology)
---
*Note: This repository is currently hosting the initial architecture design, proposal configuration, and workflow blueprints for the PSB Hackathon screening phase. Active prototype development is underway.*
