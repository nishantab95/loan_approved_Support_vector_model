Loan Approval Prediction – Support Vector Classifier (SVC)
This repository contains a machine learning project that builds and evaluates a Support Vector Classifier (SVC) model to predict loan approvals using a structured loan dataset.

📌 Overview
This project demonstrates an end-to-end workflow for binary classification using SVC, including:
Data preprocessing and feature handling
Train-test split
SVC model training
Hyperparameter tuning
Performance evaluation (accuracy, precision, recall, F1-score)
Comparison before and after tuning
The goal is to accurately predict whether a loan will be approved based on applicant features.

🚀 Features
✔ Clean handling of missing values
✔ Scikit-learn SVC implementation
✔ Hyperparameter tuning for performance improvement
✔ Detailed classification metrics
✔ Easy-to-interpret results and plots

📊 Results Summary
The tuned SVC model significantly improved performance:
Higher accuracy compared to baseline
Better F1-score, balancing precision and recall
Improved recall for approved loans, which is valuable for business decisions

📂 File Description
loan_approved_Support_vector_model.ipynb – Main notebook containing full model build, tuning, and evaluation

🔗 Kaggle Notebook
You can view and run this project on Kaggle here:
👉 Kaggle Link:"/kaggle/input/loan-approved-dataset/loan_approved.csv"

🧠 How It Works
Load the loan dataset
Preprocess and encode categorical features
Train an initial SVC model
Use GridSearchCV (or similar) for hyperparameter optimization
Evaluate and compare model performance before and after tuning

📌 How to Run
Clone this repository
git clone https://github.com/nishantab95/loan_approved_Support_vector_model.git
Install dependencies
pip install -r requirements.txt
Launch the notebook
jupyter notebook loan_approved_Support_vector_model.ipynb

📈 Metrics Explained
Metric	Description
Accuracy	% of correct predictions overall
Precision	Proportion of positive predictions that were correct
Recall	Proportion of actual positives correctly identified
F1-Score	Harmonic mean of precision and recall
📝 Notes

This model is a strong baseline and can be improved further with:
Feature engineering
Class balancing techniques (SMOTE, class weights)
Alternative classifiers (Random Forest, XGBoost, LightGBM)
