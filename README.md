# Customer Churn Prediction Using Logistic Regression

## Project Overview

Customer retention is one of the most important challenges faced by subscription-based businesses. Acquiring new customers is often more expensive than retaining existing ones, making customer churn analysis a valuable business activity.

This project develops a Logistic Regression machine learning model to predict whether a customer is likely to leave a telecommunications company. Using the Telco Customer Churn dataset, the project follows a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

The project demonstrates how machine learning can support proactive customer retention strategies by identifying customers who are at a high risk of churning.

## Business Problem

Customer churn directly impacts revenue, profitability, and long-term business growth. Without understanding why customers leave, companies struggle to design effective retention strategies.

The objective of this project is to analyse customer characteristics and service usage patterns to identify factors associated with churn and build a predictive model that can estimate the likelihood of a customer leaving the company.

## Objectives

The objectives of this project are to:

* Explore customer demographic and service-related data.
* Perform data cleaning and preprocessing.
* Conduct exploratory data analysis to discover trends and relationships.
* Prepare data for machine learning through feature engineering and encoding.
* Train a Logistic Regression classification model.
* Evaluate model performance using appropriate classification metrics.
* Identify the most influential factors contributing to customer churn.
* Provide business recommendations that support customer retention.

## Dataset Overview

Dataset: Telco Customer Churn Dataset

Source: Kaggle

The dataset contains information about telecommunications customers, including demographic information, subscribed services, billing information, contract details, and customer churn status.

### Dataset Summary

| **Attribute**          | **Description**       |
| ---------------------- | --------------------- |
| Number of observations | 7,043                 |
| Number of features     | 21                    |
| Prediction target      | Churn                 |
| Problem type           | Binary Classification |

Example variables include:

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Internet Service
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Churn

## Project Workflow

The project follows a complete end-to-end machine learning pipeline:

1. Data Loading
2. Data Exploration
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Data Preprocessing
6. Feature Engineering
7. Train-Test Split
8. Logistic Regression Model Development
9. Model Training
10. Model Evaluation
11. Model Interpretation
12. Business Insights and Recommendations

## Tools & Technologies

| **Category**            | **Tools**           |
| ----------------------- | ------------------- |
| Programming Language    | Python              |
| Data Manipulation       | Pandas, NumPy       |
| Data Visualization      | Matplotlib, Seaborn |
| Machine Learning        | Scikit-learn        |
| Development Environment | Google Colab        |
| Version Control         | Git & GitHub        |

## Images Preview

The project includes several visualisations created during exploratory data analysis, including:

* Customer Churn Distribution
* Churn by Contract Type
* Churn by Internet Service
* Monthly Charges Distribution
* Tenure Distribution
* Correlation Heatmap
* Feature Relationships
* Model Evaluation Visualisations (Confusion Matrix and ROC Curve)

Screenshots of these visualisations will be added once the project analysis is completed.

## Quick Results / Highlights

The project aims to uncover key patterns associated with customer churn and evaluate the effectiveness of Logistic Regression as a predictive model.

Some of the expected outcomes include:

* Identification of customer groups with the highest churn rates.
* Understanding the impact of contract type, tenure, and monthly charges on customer retention.
* Evaluation of Logistic Regression using Accuracy, Precision, Recall, F1-Score, ROC-AUC, and the Confusion Matrix.
* Actionable business recommendations based on the model's findings.

## Future Improvements

Potential enhancements to this project include:

* Compare Logistic Regression with other classification algorithms such as Decision Trees, Random Forest, Support Vector Machines, and Gradient Boosting.
* Perform hyperparameter tuning to optimise model performance.
* Apply feature selection techniques to improve model interpretability.
* Address potential class imbalance using resampling techniques such as SMOTE.
* Deploy the trained model as an interactive web application.
* Build a customer churn prediction dashboard integrating machine learning outputs with business intelligence visualisations.
