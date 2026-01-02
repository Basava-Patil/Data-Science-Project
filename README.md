📊 Telecom Customer Churn Prediction
📌 Project Overview
        Customer churn is a major challenge in the telecom industry, directly impacting revenue and customer lifetime value.
        This project focuses on analyzing customer behavior, predicting churn using machine learning, and providing data-driven retention strategies to reduce customer attrition.
        
        The goal is to identify at-risk customers early, understand key churn drivers, and support personalized retention decisions.

🎯 Objectives
      Analyze customer churn patterns using Exploratory Data Analysis (EDA)
      Segment customers based on tenure and spending behavior
      Build and evaluate machine learning models to predict churn
      recall to minimize missed churn customers
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
   1) Data Cleaning & Preparation
        Handled missing values (especially TotalCharges)        
        Encoded categorical variables
        Split data into training and testing sets

   2) Exploratory Data Analysis (EDA)
        Identified churn patterns across tenure, contract type, charges, and payment method
        Discovered higher churn among new customers and month-to-month contracts

   3) Customer Segmentation
        Segmented customers using tenure (loyalty) and monthly charges (customer value)
        Created segments such as new vs long-term customers and low vs high spenders

   4) Churn Prediction Modeling
        Trained and compared multiple models:
            Logistic Regression
            Decision Tree
            Random Forest
            XGBoost
        Focused on recall to reduce missed churn customers

   5) Model Evaluation & Interpretation
        Evaluated models using Accuracy, Precision, Recall, F1-score, ROC-AUC
        Identified key churn drivers using feature importance

   6) Business Recommendations
        Early engagement programs for new customers
        Personalized offers for high-value customers
        Incentives to move customers to long-term contracts
        Improved payment experience for electronic check users
