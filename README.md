Loan Approval Prediction using Python
Overview

This project demonstrates how to predict loan approvals using Machine Learning in Python. By analyzing applicant details such as income, employment, education, credit history, and loan amount, we train a classification model to determine whether a loan should be approved.

The project walks through:

Data cleaning & preprocessing

Exploratory Data Analysis (EDA)

Handling missing values & outliers

Feature engineering (one-hot encoding, scaling)

Model training using Support Vector Classifier (SVC)

Predictions on test data

Dataset

The dataset contains details of applicants with attributes like gender, marital status, education, self-employment, income, loan amount, loan term, credit history, and property area.
Target variable: Loan_Status (Y = Approved, N = Not Approved).

Steps

Data Preprocessing

Handle missing values (mode for categorical, median/mode for numeric).

Remove outliers using IQR.

Encode categorical features with one-hot encoding.

Scale numeric features with StandardScaler.

EDA (Exploratory Data Analysis)

Visualized loan approval status, gender, marital status, education, self-employment, applicant/co-applicant income, loan amount, credit history, and property area distributions.

Checked relationships between loan status and key financial features.

Model Training

Algorithm: Support Vector Classifier (sklearn.svm.SVC)

Data split: 80% training, 20% testing.

Prediction

Trained model used to predict loan approval (Loan_Status_Predicted) for test applicants.

Technologies Used

Python

Pandas, NumPy

Plotly (visualizations)

Scikit-learn (ML preprocessing + model)

Results

The model successfully predicts loan approvals, helping financial institutions streamline the decision-making process.

Future Improvements

Test with ensemble models like Random Forests or XGBoost.

Hyperparameter tuning for improved accuracy.

Deploy the model with a web app (Flask/Streamlit).
