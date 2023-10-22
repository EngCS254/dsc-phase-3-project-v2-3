
# SYRIATEL CUSTOMER CHURN

Author: Caleb Ochieng

![awesome](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*47xx1oXuebvYwZeB0OutuA.png)

Welcome to the "SYRIATEL CUSTOMER CHURN" project! This repository hosts a comprehensive analysis of customer churn for Syriatel, a fictitious telecommunications company. Customer churn, the phenomenon where subscribers switch from one service provider to another, is a critical challenge for telecom businesses worldwide. This project delves into understanding the factors contributing to customer churn and aims to provide insights and strategies for retaining valuable customers.

# Project Overview
In this repository, we explore various aspects related to customer churn prediction and management. We've carried out data preparation, feature engineering, and extensive analysis to understand the dynamics of churn within the Syriatel customer base. We've also leveraged machine learning models, including Logistic Regression, Random Forest, XGBoost, Support Vector Machine, and K-Nearest Neighbors, to predict customer churn with the goal of enhancing retention strategies.

# Key Highlights
**Data Preparation**: We've meticulously prepared the data, including handling missing values and encoding categorical variables, to ensure the quality and integrity of the dataset.

**Model Exploration**: We've evaluated multiple machine learning models to identify the most effective approach in predicting customer churn. Our findings shed light on the strengths and weaknesses of each model.

**Feature Importance**: We've identified the top five features that play a pivotal role in predicting customer churn. This insight is invaluable for tailoring retention strategies.

**Recommendations**: Based on the analysis, we've made actionable recommendations for addressing churn, emphasizing the significance of factors like international plans and customer service calls.

Certainly, here's a more concise version:

---

## Project Background

This analysis focuses on the challenge of customer churn within the telecommunications industry. For telecom companies like SyriaTel, retaining customers is essential for revenue and growth. This project addresses critical issues:

**1. Churn Prediction:** Anticipate which customers are likely to churn, enabling proactive retention strategies.

**2. Customer Segmentation:** Group customers based on behavior and preferences for tailored strategies.

**3. Service Quality:** Identify and enhance areas affecting customer satisfaction and churn.

**4. Pricing Strategy:** Optimize pricing to balance retention and revenue.

**5. Marketing Effectiveness:** Assess and improve marketing campaigns.

## Project Objectives

This analysis aims to:

**1. Predict Churn:** Develop precise models to forecast potential churn, allowing SyriaTel to implement retention strategies.

**2. Evaluate Models:** Compare model performance to choose the most effective one.

**3. Feature Insights:** Identify key factors contributing to churn for data-informed decision-making.

---

### 2. Business Understanding 
**Objective:** Predict customer churn and develop strategies for customer retention.

**Key Business Problems:**
- Customer Churn Prediction: Identify customers at risk of leaving SyriaTel's services.
- Customer Segmentation: Group customers based on behavior, preferences, and likelihood of churn.
- Service Quality Improvement: Address factors contributing to customer dissatisfaction and churn.
- Pricing Strategy Optimization: Balance pricing to minimize churn while maximizing revenue.
- Marketing Effectiveness: Assess marketing campaigns for improved customer retention and acquisition.

### 3. Data Understanding 
**Data Source:** The dataset contains customer-related information, including usage, subscriptions, and churn status.

**Data Exploration:** We explored the dataset to understand its features and distribution.

### 4. Data Preparation 
**Data Cleaning:** We handled missing values and ensured data consistency.

**Feature Engineering:** We created new features and encoded categorical variables.

**Balancing Class Imbalance:** To address class imbalance, we applied the SMOTE technique.

### 5. Modeling 
**Model Selection:** We explored various models, including Logistic Regression, Random Forest, XGBoost, SVM, and KNN.

**Model Training:** Models were trained using resampled data.

### 6. Evaluation 
**Performance Metrics:** We evaluated models based on accuracy, precision, recall, F1-score, and AUC-ROC.

**XGBoost:** The top-performing model with an accuracy of 95%.

### 7. Deployment 
The XGBoost model can be deployed in a real-time or batch prediction system to proactively identify and retain at-risk customers.

### 8. Conclusion 
The project identified the significance of features like "international_plan_yes" and "customer_service_calls" in predicting churn. The XGBoost model outperformed others, offering valuable insights for informed decision-making.

---
