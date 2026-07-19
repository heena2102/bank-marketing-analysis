# Bank Marketing - Term Deposit Subscription Prediction

**Marketing Analytics Machine Learning Project**

## Overview
This repository contains an end-to-end data science and machine learning project focused on marketing analytics. 

**Goal:** Predict whether a bank client will subscribe to a term deposit (`y` = yes/no) based on client, campaign, and macroeconomic data.

**Dataset:** UCI Bank Marketing (`bank-additional-full`) - 41,188 rows, 21 columns, Portuguese bank direct-marketing campaigns (2008–2010).

## Project Flow
The analysis is structured into the following distinct stages:
1. **Setup & imports**
2. **Understand the data** (shape, types, target, the `unknown` audit)
3. **Handle `unknown` values**
4. **Encoding** (label / ordinal / one-hot)
5. **Feature engineering & imputation**
6. **Scaling / standardization**
7. **Exploratory Data Analysis (EDA)**
8. **Multicollinearity (VIF)**
9. **Train/test split + class imbalance**
10. **Modeling** (Logistic Regression → Decision Tree → Random Forest → Gradient Boosting)
11. **Evaluation**
12. **Model leaderboard**

## Files
- `bank_marketing_project_python_final.ipynb`: The main Jupyter Notebook containing the full analysis, modeling pipeline, and evaluation results.
