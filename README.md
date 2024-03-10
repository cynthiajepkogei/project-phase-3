# project-phase-3

# Customer Churn Prediction using Machine Learning
 | Author Cynthia Jepkogei |

## Business Understanding

Customer churn, the loss of customers or subscribers, can significantly impact a business's profitability. This project focuses on predicting customer churn for SyriaTel, a telecommunications company facing high churn rates. The objective is to build a machine learning model that identifies customers likely to churn, allowing proactive measures for retention.

## Problem Statement

SyriaTel experiences a notable customer churn problem, necessitating the identification of potential churners and implementing strategies for retention. Machine learning models leveraging customer usage patterns, payment history, and demographics can aid in predicting churn. The goal is to develop a classifier to foresee customer churn, enabling timely intervention.

## Objectives

1. Build a high-recall model for predicting customer churn.
2. Identify features influencing customer churn.
3. Provide recommendations to reduce customer churn.

## Dataset Details

The dataset, sourced from Kaggle, encompasses 21 columns with 3333 entries, containing customer demographics, usage patterns, payment history, and subscriptions.

## Data Understanding

### Data Cleaning

Addressing errors, inaccuracies, and inconsistencies, including handling missing values and duplicates.

### Statistical Analysis

#### Univariate Analysis

Examining the target variable "churn" distribution, a categorical variable indicating customer likelihood to churn (True/False).

## Modeling

1. **Logistic Regression**: Predicts churn probability using customer data.
2. **Random Forest Classifier**
3. **Decision Tree Classifier**
4. **Gradient Boosting Classifier**
5. **XGBoost**

## Model Tuning

- Tuning parameters for Decision Tree and XGBoost classifiers.

## Conclusion

The XGBoost model achieved a recall of 0.79 for churned customers, indicating its potential for identifying actual churn cases. Further validation on diverse datasets or through cross-validation is recommended to ensure robust performance.

## Recommendations

1. **XGBoost Model**: Recommended for predicting customer churn due to its high recall and decent ROC AUC.
2. **Pricing Strategies**: Review day charges to ensure competitiveness and value for money.
3. **International Service**: Enhance offerings for customers with international plans to address high costs or service issues.
4. **Voice Mail Services**: Improve and promote voice mail services, offering tutorials or assistance.
5. **Customer Support**: Strengthen customer support to address dissatisfaction and unresolved issues effectively.

These recommendations aim to enhance customer satisfaction and reduce churn, emphasizing the importance of understanding specific customer needs and preferences.

