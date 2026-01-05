# 🏨 Hotel Booking Cancellation Prediction

This project builds and evaluates predictive models to **identify hotel bookings that are likely to be canceled**. Using historical reservation data, the analysis focuses on understanding customer behavior, key risk factors for cancellation, and building a classification model that can support revenue management and overbooking strategies.

---

## 📌 Project Overview

- **Dataset:** Hotel booking demand dataset  
- **Format:** Jupyter Notebook (`.ipynb`)  
- **Target Variable:** `is_canceled` (binary classification)  
- **Domain:** Hospitality analytics, customer behavior, revenue optimization  

### Objectives
- Analyze patterns behind booking cancellations
- Identify high-impact predictors of cancellation
- Build and evaluate machine learning models for cancellation prediction
- Translate model insights into actionable business recommendations

---

## 📊 Dataset Description

The dataset contains hotel reservation records with information on booking details, customer profiles, and stay characteristics.

Key features include:
- Lead time
- Hotel type (City vs. Resort)
- Average Daily Rate (ADR)
- Deposit type
- Number of special requests
- Previous cancellations
- Customer type
- Stay duration (weekend vs weekday nights)
- Booking changes and distribution channels

---

## 🧹 Data Cleaning & Preprocessing

- Removed or handled missing values
- Encoded categorical variables
- Treated outliers in pricing variables (ADR)
- Performed train-test split
- Scaled numerical features where required

---

## 🔍 Exploratory Data Analysis (EDA)

- Cancellation rates by hotel type
- Impact of lead time and deposit type on cancellations
- Relationship between price (ADR) and cancellation likelihood
- Visualization of class imbalance
- Correlation analysis among predictors

---

## 🤖 Modeling & Evaluation

Models explored include:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

Evaluation metrics:
- Accuracy
- Precision & Recall
- Confusion matrix
- ROC / AUC (if included)

Model interpretation focuses on identifying **business-relevant drivers** of cancellation risk.

---

## 📈 Business Applications

- Dynamic overbooking strategies
- Targeted customer incentives to reduce cancellations
- Improved demand forecasting and revenue management
- Risk-based booking policy design

---

## 🚀 Possible Extensions

- Handling class imbalance with SMOTE
- Feature importance and SHAP analysis
- Model deployment as a booking risk API or dashboard

---

## 🎓 Learning Outcomes

- End-to-end classification pipeline
- Translating ML outputs into business insights
- Working with real-world, imbalanced datasets
- Applying analytics to revenue optimization problems

---

## 📚 Reference

- Hotel Booking Demand Dataset (public dataset)

---
