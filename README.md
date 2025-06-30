# Smart-Loan-Classifier

# 🧠 Smart Loan Classifier

**Course**: IE 7275 – Data Mining in Engineering  
**Team**: Samruddhi Bansod, Rutuja Jadhav  
**Date**: April 8, 2025

---

## 🚀 Project Overview

This project builds a machine learning pipeline to predict whether a loan application will be approved or denied. Using demographic, financial, and credit data, we trained multiple classification models to aid financial institutions in automating risk-aware and data-driven decisions.

---

## 📊 Dataset Information

- **Source**: [Kaggle Loan Approval Dataset](https://www.kaggle.com/datasets/taweilo/loan-approval-classification-data)
- **Records**: ~45,000 entries
- **Features**: 14 columns including age, gender, income, credit history, loan purpose, etc.
- **No missing or duplicate values**

---

## 📈 Visual Exploratory Data Analysis

### 1. Distribution of Credit Scores  
Most applicants had scores around 650, forming a near-normal bell curve.

![Credit Score Distribution](Credit%20score%20distribution.png)

---

### 2. Loan Amount vs. Income (Color-Coded by Loan Status)  
Higher income generally led to more approvals (orange dots).

![Income vs Loan Amount](Income%20vs%20loan%20scatter.png)

---

### 3. Distribution of Loan Interest Rate  
Most interest rates were between 6% and 14%, skewed right.

![Loan Interest Rate Distribution](istribution%20of%20loan%20interest%20page.png)

---

### 4. Loan Status by Education Level  
Bachelor’s and High School applicants dominated, with Masters having a better approval ratio.

![Loan Status by Education](loan%20status%20by%20education.png)

---

### 5. PCA Explained Variance  
First 10 components explained over 95% of the variance.

![PCA Variance Explained](PCA%20Variance.png)

---

## 🔧 Preprocessing & Feature Engineering

- One-hot encoding for categorical variables
- Scaling using `StandardScaler`
- Dimensionality reduction using **PCA (10 components)**

---

## 🧠 Models Implemented

| Model                  | Accuracy | AUC Score |
|------------------------|----------|-----------|
| Logistic Regression    | 88.56%   | 0.95      |
| Random Forest          | **91.20%** | **0.97** |
| Support Vector Machine | 89.98%   | 0.96      |
| XGBoost Classifier     | 91.00%   | 0.97      |
| LightGBM Classifier    | 90.16%   | **0.97**  |

---

## 🏁 Conclusion & Recommendation

- **Best Model**: Random Forest
  - Highest accuracy
  - Balanced precision/recall
  - Robust against overfitting
- **Alternative Models**: XGBoost & LightGBM for better performance with ranking tasks

---

## 📂 Files in This Repo

- `Final_Loan_Classifer.ipynb` – All code and visualizations
- `Final Draft Project Report.pdf` – Detailed write-up of problem, models, and analysis

---
