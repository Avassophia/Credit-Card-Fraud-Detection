# Credit-Card-Fraud-Detection
## Overview
This project focuses on **detecting fraudulent credit card transactions** using machine learning. We implemented a **custom logistic regression model** with a carefully selected subset of features and compared its performance to Scikit-learn’s logistic regression using all features.

The goal is to demonstrate that even a **simple, interpretable model with fewer features** can effectively identify fraudulent activity, which is crucial for minimizing financial losses and protecting customers.

---

## Dataset
- The dataset used is the **Credit Card Fraud Detection dataset** from Kaggle ([link here](https://www.kaggle.com/mlg-ulb/creditcardfraud)).  
- It contains **284,807 transactions**, of which only **492 are fraudulent**, making it a highly imbalanced dataset.  

---

## Project Highlights
- **Custom Logistic Regression:** Implemented from scratch to better understand the mechanics and impact of threshold tuning.  
- **Feature Selection:** Used a subset of features to improve interpretability and maintain strong performance.  
- **Model Comparison:** Evaluated against Scikit-learn’s logistic regression using metrics such as accuracy, precision, recall, and confusion matrices.  
- **Threshold Tuning:** Adjusted classification thresholds to optimize detection of fraudulent transactions while minimizing false positives.  

---

## Business Significance
Fraud detection is a critical business application where **false negatives (missed frauds) and false positives (blocked legitimate transactions)** have significant costs.  
- **Reducing losses:** Accurately identifying fraudulent transactions can save businesses millions annually.  
- **Improving customer experience:** Minimizing false positives ensures legitimate customers are not inconvenienced.  
- **Resource efficiency:** Using fewer, well-selected features allows faster processing and more interpretable models for risk analysts.

This project shows that even **lightweight models can provide actionable insights**, supporting decision-making in real-world financial systems.

---
