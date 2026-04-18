# 🚀 Customer Churn Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

🔗 **Live Notebook (Colab)**  
Customer Retention Analysis & Prediction_using_ml.ipynb - Colab https://share.google/eEH9sfAAxsTUMU62a

---

## 📌 Overview

Customer churn prediction is crucial for businesses to retain valuable customers.  
This project uses **machine learning models** to predict whether a customer will churn based on their behavior and subscription details.

💡 **Goal:** Identify high-risk customers and help businesses take proactive actions.

---

## 🧠 Problem Statement

Predict whether a customer will:

👉 **Stay (0) or Churn (1)**

Based on:
- Customer demographics  
- Subscription services  
- Billing & payment data  

---

## 📊 Dataset Details

- 📁 Records: **7043**
- 📌 Features: **21**
- 🎯 Target: **Churn**

### Important Features:
- Tenure  
- MonthlyCharges  
- TotalCharges  
- Contract Type  
- Internet Service  
- Payment Method  
- TechSupport, OnlineSecurity  

---

## ⚙️ Tech Stack

| Category        | Tools Used |
|----------------|----------|
| Language       | Python |
| Data Handling  | Pandas, NumPy |
| Visualization  | Matplotlib, Seaborn |
| ML Models      | Scikit-learn, XGBoost |
| Imbalance Fix  | SMOTE |

---

## 🔄 Workflow

### 🧹 Data Preprocessing
- Handled missing values  
- Converted categorical features using Label Encoding  
- Cleaned dataset  

### ⚖️ Handling Imbalance
- Applied **SMOTE** to balance churn classes  

### 🤖 Model Training
- Decision Tree  
- Random Forest  
- XGBoost  

### 📊 Evaluation Metrics
- Accuracy Score  
- Confusion Matrix  
- Classification Report  

---

## 🤖 Models Comparison

| Model          | Description |
|----------------|------------|
| Decision Tree  | Baseline model |
| Random Forest  | Reduced overfitting |
| XGBoost        | Best performance |

---

## 📈 Key Insights

✔ Customers with **month-to-month contracts** are more likely to churn  
✔ Higher **monthly charges** increase churn risk  
✔ Lack of **tech support/security** leads to higher churn  
✔ Long-term customers are more loyal  

---

## 🏆 Results

- Achieved strong performance using ensemble models  
- **XGBoost gave the best results**  

---

## 👩‍💻 Author

-CHINKI RAJ
