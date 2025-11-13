# Customer Churn Prediction

An end-to-end **Customer Churn Prediction System** that predicts whether a customer is likely to leave a service and provides a **beautiful, emoji-driven Streamlit UI** to display results.  
This project demonstrates **data science, machine learning, and deployment** skills together in a professional, production-style structure.

---

## Overview

This project analyzes customer behavior and subscription data to predict churn probability.  
The model is trained using **Logistic Regression**, **Random Forest**, and **XGBoost**, compared inside a Jupyter notebook, and the best model (**XGBoost**) is exported and used by the Streamlit app.

The UI shows:

- ✅ **“Eligible / Low Risk”**
- ❌ **“At Risk / High Churn”**  

---

## 📁 Repository Structure

```plaintext
customer-churn-prediction/
├── app/
│   └── streamlit_app.py                
│
├── data/
│   ├── data_raw/                       
│   │   ├── customer_churn_dataset-training-master.csv
│   │   ├── customer_churn_dataset-testing-master.csv
│   │   └── sample_customers.csv        
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
│       └── train.ipynb                 
│
├── .env                                
├── .env.example                        
├── requirements.txt                    
├── .gitignore                          
└── README.md                           