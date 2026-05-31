# Student Academic Dropout Prediction (IT9201)
Master of Science in Artificial Intelligence (ICT9010) — Bahrain Polytechnic  
**Lecturer:** Dr. Shomona Gracia Jacob  
**Student:** Aishwarya

---

## 📌 Project Overview
This project develops an advanced predictive early-warning system to identify at-risk student records in higher education using the public benchmark UCI dataset (Realinho et al., 2022). By engineering a domain-informed **Academic Risk Index (ARI)** and implementing robust data-balancing methodologies, the framework allows academic advisors to deploy targeted interventions to maximize student retention.

## 🛠️ Tech Stack & Ecosystem
- **Programmatic Stream:** Python 3.11, Scikit-Learn, XGBoost, Imbalanced-Learn (SMOTE), SHAP (TreeSHAP Interpretability), Jupyter Notebook.
- **No-Code Verification:** Orange Data Mining v3.40.0 (Supervised classification & Unsupervised K-Means workflows).
- **Design Tools:** Napkin AI (System architecture design), Google Notebook.

## 📊 Core Performance Summary
- **Top Model:** Optimized XGBoost Classifier
- **Key Metrics:** F1-Score: `0.8329` | ROC-AUC: `0.9357`
- **Decision Calibration:** Decision thresholds optimized down to `0.40` to push True Positive **Minority Class Recall to 87.97%**, ensuring critical at-risk student cases are caught early.

## 🚀 How to Reproduce this Project
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/IT9201-Student-Dropout-Prediction.git](https://github.com/YOUR_USERNAME/IT9201-Student-Dropout-Prediction.git)
