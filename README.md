# Employee Attrition Prediction

A machine learning project to predict employee turnover.

## Project Overview
- Dataset: HR Employee Attrition Data  
- Features: Age, Job Role, Monthly Income, Work-Life Balance, Performance Rating, Years at Company, and more  
- Target: Attrition (Yes/No)  

## Features
  Some of the features
- Demographic: Age, Years at Company, Years Since Last Promotion  
- Job: Job Role, Job Level, Job Satisfaction  
- Compensation: Monthly Income, Performance Rating  
- Work-Life: Work-Life Balance  

## Machine Learning Models
- Logistic Regression  
- SVC  
- XGBoost  

## Preprocessing Steps
- Handling missing values  
- Removing outliers using IQR capping  
- Encoding categorical features  
- Scaling numeric features  

## Evaluation Metrics
  Accuracy Results
- Logistic Regression: 86%  
- SVC: 86%  
- XGBoost: 86%  

The models predict the majority class “No Attrition” very well. Predicting “Yes” is more challenging due to natural imbalance in HR datasets.

## Conclusion
This project demonstrates that machine learning can effectively support HR teams in identifying employees at risk of leaving. The models performed consistently well, achieving 86% accuracy.
