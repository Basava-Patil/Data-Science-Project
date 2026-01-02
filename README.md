📊 Telecom Customer Churn Prediction
📌 Project Overview

Customer churn is a major challenge in the telecom industry, directly impacting revenue and customer lifetime value.
This project focuses on analyzing customer behavior, predicting churn using machine learning, and providing data-driven retention strategies to reduce customer attrition.

The goal is to identify at-risk customers early, understand key churn drivers, and support personalized retention decisions.

🎯 Objectives

Analyze customer churn patterns using Exploratory Data Analysis (EDA)

Segment customers based on tenure and spending behavior

Build and evaluate machine learning models to predict churn

Prioritize recall to minimize missed churn customers

Translate model insights into actionable business recommendations

🗂 Dataset Description

The project uses a telecom customer churn dataset containing the following key features:

Tenure

MonthlyCharges

TotalCharges

Contract Type

Payment Method

Internet & Service Usage

Churn (Target Variable)

⚙️ Project Workflow

Data Cleaning & Preparation

Handled missing values (especially TotalCharges)

Encoded categorical variables

Split data into training and testing sets

Exploratory Data Analysis (EDA)

Identified churn patterns across tenure, contract type, charges, and payment method

Discovered higher churn among new customers and month-to-month contracts

Customer Segmentation

Segmented customers using tenure (loyalty) and monthly charges (customer value)

Created segments such as new vs long-term customers and low vs high spenders

Churn Prediction Modeling

Trained and compared multiple models:

Logistic Regression

Decision Tree

Random Forest

XGBoost

Focused on recall to reduce missed churn customers

Model Evaluation & Interpretation

Evaluated models using Accuracy, Precision, Recall, F1-score, ROC-AUC

Identified key churn drivers using feature importance

Business Recommendations

Early engagement programs for new customers

Personalized offers for high-value customers

Incentives to move customers to long-term contracts

Improved payment experience for electronic check users

📈 Key Insights

New customers are more likely to churn

Month-to-month contracts show higher churn rates

High monthly charges increase churn risk

Payment method plays a significant role in churn behavior

🏆 Best Model

XGBoost performed best with higher recall and ROC-AUC

Effectively captured complex relationships between customer behavior and churn

🛠 Tools & Technologies

Programming: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost

Techniques: EDA, Customer Segmentation, Classification, Model Evaluation

✅ Final Outcome

Built a recall-focused churn prediction system

Identified high-risk customers proactively

Delivered actionable insights for churn reduction

Demonstrated end-to-end data science workflow
