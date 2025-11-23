# 📊 Bank Marketing Campaign Analysis & Term Deposit Subscription Prediction  
### Modern EDA • Machine Learning • Model Explainability • Power BI Dashboard

This project analyzes the **Bank Marketing Dataset** from a Portuguese bank to identify which clients are most likely to subscribe to a term deposit.  
It simulates an **end-to-end data analytics pipeline** used by real data analysts and data scientists.

---

## Project Overview

This project demonstrates:

- Modern **Exploratory Data Analysis (EDA)** with clear business insights  
- Clean **data preprocessing pipeline**  
- **Six machine learning classification models**  
- Full evaluation using industry-standard metrics  
- **Confusion matrices, ROC curves, AUC scores**  
- **Feature importance (RF/XGB) & SHAP explainability**  
- A professional **Power BI dashboard** for business stakeholders  
- GitHub-ready notebook structure  
- End-to-end deliverable like a real analytics project  

---

## 📁 Repository Structure
├── data/
│ └── bank-additional-full.csv # Raw dataset
├── notebook/
│ └── bank_marketing_pipeline.ipynb # Full analysis & ML workflow
├── powerbi/
│ └── bank_marketing_dashboard.pbix # Power BI Dashboard
├── images/
│ ├── dashboard_page1.png
│ ├── dashboard_page2.png
│ └── model_results.png
└── README.md

---

## 📊 Dataset Summary

- **Bank Marketing Dataset**  
- 45,211 records  
- 20+ demographic + economic + campaign features  
- Target variable:  
  - `y = yes` → client subscribed to term deposit  
  - `y = no` → did not subscribe  

---

## EDA Highlights (Key Insights)

- **Cellular contact consistently outperforms telephone**
- **Call duration is the strongest positive driver of subscription**
- **Older age groups show higher subscription interest**
- **Months like March, September show peak conversion**
- **Certain professions (retired, students) convert at much higher rates**

---

## Machine Learning Models Used

1. Logistic Regression  
2. Naive Bayes  
3. K-Nearest Neighbors  
4. Decision Tree  
5. Random Forest  
6. XGBoost  

Each model is evaluated on:

- Accuracy  
- Precision  
- Recall  
- F1  
- ROC-AUC  

---

## Model Evaluation Summary

The best performing models were:

- **XGBoost**  
- **Random Forest**

Both achieved the highest **AUC**, strong precision/recall, and stable performance.

---

## Explainability

### Feature Importance  
- Duration  
- Contact method  
- Month  
- Campaign count  

### SHAP Values  
Used to identify how individual features impact predictions.

---

## 📊 Power BI Dashboard

A professional two-page business dashboard was built:

### **Page 1 — Marketing Campaign Insights**
- KPIs: Subscription rate, total customers, total subscribed  
- Subscription rate by:  
  - Job  
  - Contact type  
  - Month  
- Age distribution  
- Duration distribution  
- Campaign performance overview  

### **Page 2 — ML Model Performance**
- Model comparison table  
- AUC comparison  
- ROC curve visual  
- Confusion matrices  
- Feature importance bar charts  

---

## 🛠 Tools Used

- Python (Pandas, NumPy, Scikit-learn, XGBoost, SHAP)
- Seaborn & Matplotlib  
- Power BI  
- Google Colab / Jupyter  
- GitHub  

---
