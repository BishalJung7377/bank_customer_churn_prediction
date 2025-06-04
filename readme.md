# 🏦 Bank Customer Churn Prediction

Understanding customer churn is critical for banks to retain valuable clients and design better customer experience strategies. This project aims to build a predictive machine learning model that classifies whether a customer will exit the bank, based on features like their credit score, balance, and engagement metrics.

---

## 📌 Problem Statement

Customer retention is a top priority in the banking industry. Losing a long-term customer often costs more than acquiring a new one. Predicting churn early allows banks to take proactive steps to improve customer satisfaction and reduce attrition.

---

## 📊 Data Overview

The dataset includes **10,000 bank customers** with the following features:

### Demographics:

- **Age**
- **Gender**
- **Geography**

### Financial Data:

- **Credit Score**
- **Balance**
- **Estimated Salary**

### Account Activity:

- **Tenure** (years with the bank)
- **Number of Products** (e.g., credit card, mortgage)
- **Card Type** (standard, gold, etc.)

### Engagement Metrics:

- **Satisfaction Score**
- **Number of Complaints**
- **Points Earned**

### Target Variable:

- **Exited**:
  - `1` = Customer churned
  - `0` = Customer stayed

---

## 🎯 Goal

Given customer data, we want to:

> Predict whether a customer will **churn** (`Exited = 1`) or **stay** (`Exited = 0`).

This is a **supervised binary classification** problem.

---

## 🔍 Project Pipeline

1. **Data Loading and Preprocessing**

   - Handle missing values
   - Encode categorical variables
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**

   - Understand feature distributions
   - Visualize churn patterns

3. **Model Building**

   - Train-Test split
   - Try different ML algorithms (Logistic Regression, Random Forest, XGBoost, etc.)
   - Evaluate using metrics like Accuracy, Precision, Recall, F1 Score, AUC-ROC

4. **Model Tuning and Feature Importance**

   - Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
   - Identify key features driving churn

5. **Insights & Recommendations**
   - Interpret model results
   - Provide actionable business recommendations

---

## 🧠 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost / LightGBM
- Jupyter Notebook / Streamlit (optional dashboard)

---

## 📈 Results & Insights

- High accuracy achieved with ensemble models
- Key factors influencing churn:
  - Low satisfaction score
  - High balance with low product usage
  - High number of complaints
- Actionable insight: Target high-risk customers with personalized offers and improve complaint resolution processes.

---
