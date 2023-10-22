
# SYRIATEL CUSTOMER CHURN

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

### 1. Business Understanding 
**Objective:** Predict customer churn and develop strategies for customer retention.

**Key Business Problems:**
- Customer Churn Prediction: Identify customers at risk of leaving SyriaTel's services.
- Customer Segmentation: Group customers based on behavior, preferences, and likelihood of churn.
- Service Quality Improvement: Address factors contributing to customer dissatisfaction and churn.
- Pricing Strategy Optimization: Balance pricing to minimize churn while maximizing revenue.
- Marketing Effectiveness: Assess marketing campaigns for improved customer retention and acquisition.

### 2. Data Understanding 
**Data Source:** The dataset contains customer-related information, including usage, subscriptions, and churn status.

**Data Exploration:** We explored the dataset to understand its features and distribution.

### 3. Data Preparation 
**Data Cleaning:** We handled missing values and ensured data consistency.

**Feature Engineering:** We created new features and encoded categorical variables.

**Balancing Class Imbalance:** To address class imbalance, we applied the SMOTE technique.

### 4. Modeling 
**Model Selection:** We explored various models, including Logistic Regression, Random Forest, XGBoost, SVM, and KNN.

**- Logistic Regression Model**

![image](https://github.com/EngCS254/dsc-phase-3-project-v2-3/assets/139503182/0364b203-8f0f-4dd2-9a0d-4b55dd8ae97f)


Accuracy: 0.74
-----------------------------------

Classification Report:
               precision    recall  f1-score   support

           0       0.96      0.72      0.83       566
           1       0.35      0.83      0.49       101

    accuracy                           0.74       667
   macro avg       0.66      0.78      0.66       667
weighted avg       0.87      0.74      0.78       667

**- Random Forest classifier**

![image](https://github.com/EngCS254/dsc-phase-3-project-v2-3/assets/139503182/0a039c71-ecae-4785-9887-2a391857a8e9)


Random Forest Accuracy: 0.94
-----------------------------------

Random Forest Classification Report:
               precision    recall  f1-score   support

           0       0.97      0.97      0.97       566
           1       0.82      0.81      0.82       101

    accuracy                           0.94       667
   macro avg       0.89      0.89      0.89       667
weighted avg       0.94      0.94      0.94       667

**- XGBoost**

![image](https://github.com/EngCS254/dsc-phase-3-project-v2-3/assets/139503182/84f52158-8b9b-4715-baa5-11a8f03824bf)


XGBoost Accuracy: 0.95
-----------------------------------

XGBoost Classification Report:
               precision    recall  f1-score   support

           0       0.96      0.97      0.97       566
           1       0.84      0.80      0.82       101

    accuracy                           0.95       667
   macro avg       0.90      0.89      0.90       667
weighted avg       0.95      0.95      0.95       667

**- Support Vector Machine (SVM)**

![image](https://github.com/EngCS254/dsc-phase-3-project-v2-3/assets/139503182/39616752-9662-46a0-8e46-6ea13221de8a)


SVM Accuracy: 0.73
-----------------------------------

SVM Classification Report:
               precision    recall  f1-score   support

           0       0.96      0.72      0.82       566
           1       0.35      0.84      0.49       101

    accuracy                           0.73       667
   macro avg       0.65      0.78      0.66       667
weighted avg       0.87      0.73      0.77       667


**- K-Nearest Neighbors (KNN)**

![image](https://github.com/EngCS254/dsc-phase-3-project-v2-3/assets/139503182/ccd60083-5d5f-4731-8592-96ea5c425972)


KNN Accuracy: 0.80
-----------------------------------

KNN Classification Report:
               precision    recall  f1-score   support

           0       0.94      0.82      0.88       566
           1       0.41      0.70      0.52       101

    accuracy                           0.80       667
   macro avg       0.68      0.76      0.70       667
weighted avg       0.86      0.80      0.82       667







**Model Training:** Models were trained using resampled data.

### 5. Evaluation 
**Performance Metrics:** We evaluated models based on accuracy, precision, recall, F1-score, and AUC-ROC.

XGBoost emerged to be the top-performing model with an accuracy of 95%.

**ROC Curve Analysis**

![image](https://github.com/EngCS254/dsc-phase-3-project-v2-3/assets/139503182/9d82f50b-f5e8-4d3c-8c56-6d6b9977b4f1)

The AUC values provide a quantitative measure of the models' discriminative power. A higher AUC indicates a better model for this classification task. Based on the AUC values, the XGBoost model stands out as the best performer, followed closely by the Random Forest model, demonstrating their strong classification capabilities.

## **Feature Importance**

![image](https://github.com/EngCS254/dsc-phase-3-project-v2-3/assets/139503182/4ba64735-5526-4bd4-a195-23a2b38f859b)


### 6. Conclusion 

Following our thorough analysis, the key takeaways are:

**Data Prep & Class Balance**: Effective data preprocessing, one-hot encoding, and SMOTE class balancing are essential for accurate churn predictions.

**Model Top Performer**: XGBoost, with 95% accuracy, excelled in predicting churn effectively.

**Crucial Features**: Five key features include "international_plan_yes," "customer_service_calls," "number_vmail_messages," "total_intl_calls," and "total_day_minutes."

In summary, we recommend using XGBoost to predict customer churn, focusing on these key features for improved customer retention.

---

### 8. Recommendations

Based on the XGBoost model analysis and the top features, we suggest:

1. **Prioritize International Plans**: Focus on retaining customers with international plans.

2. **Enhance Customer Service**: Improve service quality to reduce calls and increase satisfaction.

3. **Optimize Voicemail Usage**: Analyze voicemail impact and adapt offerings.

4. **Address International Calls**: Develop strategies for customers with many international calls.

5. **Improve Service Quality**: Investigate and enhance service quality.

6. **Proactive XGBoost**: Implement XGBoost for real-time churn prediction.

7. **Customer Segmentation**: Segment customers for tailored strategies.

8. **Continuous Monitoring**: Regularly update the XGBoost model with new data.

9. **Feedback Loop**: Establish a feedback loop for service enhancement.

10. **Targeted Campaigns**: Create personalized retention campaigns.

Continual assessment is vital for reducing churn and driving growth.
