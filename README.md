# Project: Diabetes Prediction using Machine Learning

## Description
This project focuses on developing a machine learning model to predict the likelihood of diabetes based on patient health data. The objective is to support early detection by analyzing key risk factors such as age, BMI, blood glucose levels, and lifestyle behaviors.

## Dataset

### Source
- Kaggle – Diabetes Prediction Dataset

### Features
- Age
- Gender
- Body Mass Index (BMI)
- HbA1c level
- Blood glucose level
- Hypertension
- Heart disease
- Smoking history

## Data Preprocessing
- Removed duplicate records using `drop_duplicates()`
- Handled missing values
- Filtered invalid categorical data (e.g., gender, smoking history)
- Transformed categorical variables into readable formats
- Split dataset into training and testing sets (80:20)

## Tools and Technologies
- Python (Pandas, NumPy)
- RapidMiner
- Machine Learning: Decision Tree

## Model and Methodology
- Built a Decision Tree model for classification
- Used Correlation Matrix to analyze relationships between variables

### Key Features
- HbA1c level
- Blood glucose level
- BMI
- Age

## Key Results
- HbA1c level and blood glucose level were the most significant predictors
- The model effectively classified patients using threshold-based rules
  - Example: HbA1c > 6.7 indicates a high likelihood of diabetes
- Demonstrated clear patterns for early-stage risk identification

## Outcome
- Provides a data-driven approach for identifying individuals at risk of diabetes
- Can be extended into a clinical decision support system for early diagnosis
