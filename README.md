# Employee Attrition Prediction using Machine Learning

## Project Overview

This project was completed as part of the XYlofy AI Internship Program (Week 2).

The objective of this project is to predict employee attrition using machine learning techniques and identify the factors that contribute most to employee turnover. The analysis helps HR teams understand employee retention patterns and make data-driven decisions to reduce attrition.

---

## Problem Statement

Employee attrition is a major challenge for organizations as it leads to increased recruitment costs, training expenses, and productivity loss.

The goal of this project is to:

- Predict whether an employee is likely to leave the company.
- Analyze factors influencing employee attrition.
- Provide actionable HR recommendations based on data insights.

---

## Dataset

Dataset Used:
IBM HR Analytics Employee Attrition Dataset

Source:
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

Dataset Size:
- 1,470 employee records
- 35 original features

Target Variable:
- Attrition (Yes / No)

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Project Workflow

### 1. Data Loading and Exploration

- Loaded dataset using Pandas
- Examined dataset structure
- Identified target variable
- Calculated attrition rate
- Analyzed numerical and categorical features

### 2. Data Preprocessing

- Checked missing values
- Removed irrelevant columns
- Converted Attrition column into binary format
- Applied One-Hot Encoding to categorical features
- Scaled numerical features using StandardScaler

### 3. Exploratory Data Analysis (EDA)

Performed analysis on:

- Attrition by Department
- Attrition by Job Role
- Attrition vs Monthly Income
- Attrition vs Work-Life Balance
- Attrition vs Years at Company

### 4. Model Building

Implemented and compared:

1. Logistic Regression
2. Random Forest Classifier
3. Gradient Boosting Classifier

### 5. Model Evaluation

Models were evaluated using:

- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

### 6. Feature Importance Analysis

Identified the most influential factors contributing to employee attrition.

---

## Key Findings

- Employees in the Sales department showed higher attrition rates.
- Sales Representatives and Laboratory Technicians were among the highest-risk job roles.
- Employees working overtime were more likely to leave.
- Frequent business travel was associated with higher attrition.
- Career growth factors such as promotions and experience significantly impacted employee retention.

---

## Business Recommendations

1. Focus retention efforts on high-risk departments and job roles.
2. Monitor employee overtime and improve work-life balance initiatives.
3. Provide clear career development and promotion opportunities.
4. Conduct regular employee engagement and satisfaction surveys.

---

## Repository Structure

```
EmployeeAttritionPrediction/
│
├── analysis.ipynb
├── HR Attrition.csv
├── summary.docx
├── README.md
│
└── charts/
     ├── attrition_by_department.png
     ├── attrition_by_jobrole.png
     ├── confusion_matrix.png
     ├── feature_importance.png
     ├── income_vs_attrition.png
     ├── roc_curve.png
     ├── worklife_attrition.png
     └── years_company_attrition.png
```

---

## Author

**Manasa Bandari**

XYlofy AI Internship Program – Week 2

Employee Attrition Prediction using Machine Learning
