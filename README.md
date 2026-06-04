# DevelopersHub-Data-Science-Tasks
Data science tasks for the Developers Hub Corp internship.
Name: Tayyiba Shamraiz

Date: June 5, 2026

This repository contains all my code files and datasets for the final internship submission. I completed all 5 main tasks from the assignment document, plus an extra spam filter project for extra practice.

What is in this repository:

Task 1: Iris Data Exploration I loaded the Iris dataset using pandas and generated scatter plots, histograms, and box plots using seaborn. This was to inspect data distributions and look for outliers before doing any modeling.

Task 2: Credit Risk Prediction I handled the missing values in the dataset and isolated features like income and loan amounts. Then I trained a Logistic Regression classification model to predict if a client is likely to default on a loan, and checked the performance using a confusion matrix.

Task 3: Bank Customer Churn Prediction I prepared the customer data and encoded text columns like gender and geography into numbers. Because the dataset had way fewer churned examples than active ones, the model had a strong bias. I fixed this by adding class weighting to balance the data, which cleared the evaluation errors.

Task 4: Predicting Insurance Claim Amounts I built a Linear Regression model to estimate medical costs based on age, BMI, and smoking status. I plotted the data to show how smoking status dramatically increases claims, and evaluated the model error using MAE and RMSE.

Task 5: Personal Loan Acceptance I explored bank marketing data to see which demographic groups accept loan offers. I trained a Decision Tree classifier with a set depth to avoid overfitting, and generated a standard classification report to show the precision.

Bonus Task: Spam Email Detection I also built a text classifier that filters emails. I used CountVectorizer to turn the raw email strings into word-count numbers, then trained a Naive Bayes model to instantly catch spam phrases.

Note: All tasks were built and tested locally using a dedicated virtual environment (.venv) to keep the dependencies separate and avoid library version conflicts.
