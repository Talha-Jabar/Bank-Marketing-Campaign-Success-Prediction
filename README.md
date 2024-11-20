# Bank-Marketing-Campaign-Success-Prediction
Machine Learning || Prediction Model || Python

# Overview
This project aims to predict whether a customer will subscribe to a term deposit based on 
the Bank Marketing Dataset. The solution employs data preprocessing, feature selection, and 
machine learning models to classify outcomes.
# Objective
- Predict customer subscription (yes or no) to a term deposit using historical campaign 
data.
- Perform feature selection to identify key features influencing success.
- Evaluate multiple machine learning models for accuracy and reliability.
# Dataset
- Source: Bank Marketing Dataset
- Target Variable: y (1 = Subscribed, 0 = Not Subscribed)
# Workflow
1. Data Preprocessing
- Handled missing values.
- Encoded categorical variables using LabelEncoder.
- Standardized numerical features using StandardScaler.
  
2. Feature Selection
- Selected top 10 features based on mutual information using SelectKBest.
  
3. Model Training
Trained the following models:
- Logistic Regression
- Decision Tree
- Random Forest (Ensemble Method)
Used 5-fold cross-validation to prevent overfitting.

4. Evaluation
Evaluated models using:
o Accuracy
o Precision
o Recall
o F1-Score
- Extracted feature importance from Random Forest for interpretability.
  
5. Results
- Compared model performance.
- Analyzed the top features influencing subscription success.
# Key Features Identified
- duration: Call duration of the last campaign.
- campaign: Number of contacts during the current campaign.
- pdays: Number of days since the client was last contacted.
