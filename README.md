# 📈 CRM Analytics – Customer Lifetime Value (CLTV) Prediction

This project focuses on predicting **Customer Lifetime Value (CLTV)** by combining CRM analytics techniques with advanced probabilistic models.  
The goal is to help businesses understand long-term customer value, optimize marketing spend, and build data-driven retention strategies.

---

## 🚀 Project Overview

In this notebook, I built a complete analytical and predictive pipeline that estimates each customer’s expected lifetime revenue.  
The workflow follows a structured CRM analytics approach:

- Customer behavior analysis (RFM metrics)
- Purchase frequency and monetary modeling
- Probabilistic CLTV estimation
- Customer segmentation based on predicted value

This work demonstrates an end-to-end application of **Buy-’Till-You-Die models** and **Gamma-Gamma** monetary estimation methods widely used in modern CRM systems.

---

## 🧠 Key Steps in the Analysis

### 1. Exploratory Data Analysis (EDA)
- Identified customer purchasing patterns  
- Analyzed recency, frequency, and monetary distributions  
- Checked data quality, missing values, and outliers  

### 2. RFM Feature Engineering
Created standard CRM metrics:
- **Recency:** Time since last purchase  
- **Frequency:** Number of repeat purchases  
- **Monetary:** Average revenue per transaction  

### 3. Probabilistic Modeling
Implemented two core models from the **lifetimes** library:

- **BG/NBD (Beta Geometric / Negative Binomial Distribution)**  
  Predicts expected number of future purchases  

- **Gamma-Gamma Model**  
  Estimates expected revenue per purchase  

Combined these models to generate an **expected CLTV** score per customer.

### 4. CLTV Segmentation
Customers were segmented into strategic groups:
- High-value  
- Medium-value  
- Low-value  
- At-risk or churn-prone  

### 5. Business Insights
- Identified customers worth prioritizing for retention  
- Estimated long-term revenue potential  
- Provided guidance for marketing ROI optimization  

---

## 📦 Technologies & Libraries

- Python  
- Pandas, NumPy  
- Lifetimes (BG/NBD & Gamma-Gamma)  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📊 Results

- Successfully estimated customer lifetime values using probabilistic modeling  
- Created interpretable customer segments  
- Delivered a complete CRM analytics workflow suitable for marketing, retention, and financial planning teams  

---

## 📁 Project Structure

