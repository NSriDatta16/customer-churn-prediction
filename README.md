# Customer Churn Prediction

An end-to-end **Customer Churn Prediction System** that predicts whether a customer is likely to leave a service and provides a **beautiful, emoji-driven Streamlit UI** to display results.  
This project demonstrates **data science, machine learning, and deployment** skills together in a professional, production-style structure.

---

## Overview
This project analyzes customer behavior and subscription data to predict churn probability.  
The model is trained using **XGBoost** within a Scikit-Learn pipeline and deployed via a **Streamlit app** that shows:
- ✅ **“Eligible / Low Risk”** 
- ❌ **“At Risk”** 

---

## 📁 Repository Structure
```plaintext
customer-churn-prediction/
├── app/
│   └── streamlit_app.py           
│
├── data/
│   ├── data_raw/                  
│   ├── data_processed/            
│   └── README.md
│
├── models/
│   └── churn_xgb.joblib           
│
├── reports/                       
│
├── src/
│   └── churn/
│       ├── __init__.py
│       └── train.py               
│
├── .env                           
├── .env.example                   
├── requirements.txt               
├── .gitignore                     
└── README.md                      