![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)

# 👥 HR Employee Attrition Prediction (Machine Learning Project)

## 📌 Business Problem

Employee attrition is a major challenge for organizations because replacing experienced employees requires significant time and financial resources. High employee turnover can reduce productivity, disrupt team performance, and increase recruitment costs.

This project uses machine learning and HR analytics to identify factors associated with employee attrition and predict whether an employee is likely to leave the organization.

The goal is to demonstrate how predictive analytics can support workforce planning and employee retention strategies.

---

## 🎯 Project Objectives

The objectives of this project were to:

- Explore employee attrition patterns
- Identify factors associated with employee turnover
- Build a machine learning classification model
- Evaluate model performance using appropriate metrics
- Generate actionable business insights and recommendations

---

## 📊 Dataset Overview

The dataset contains employee information including:

- Age
- Gender
- Department
- Salary
- Training Hours
- Performance Rating
- Employee Tenure
- Overtime Ratio
- Attrition Status

**Target Variable:** Employee Attrition (Stayed vs Left)

---

## 🛠️ Tools & Technologies

### Programming & Analytics

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

### Data Science Skills

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Classification
- Logistic Regression
- Model Evaluation
- Business Insight Generation

---

## 🔄 Machine Learning Workflow

The project followed a complete machine learning pipeline:

Raw Data  
↓  
Data Cleaning  
↓  
Exploratory Data Analysis  
↓  
Feature Engineering  
↓  
Encoding Categorical Variables  
↓  
Train-Test Split  
↓  
Feature Scaling  
↓  
Logistic Regression Model  
↓  
Model Evaluation  
↓  
Business Insights

---

# 📈 Exploratory Data Analysis

### Attrition Distribution

Understanding the distribution of employees who stayed versus those who left the organization.

<img width="245" height="61" alt="image" src="https://github.com/user-attachments/assets/8306562a-74fb-4ca8-a7d2-26b31067c9ef" />

---

### Attrition by Department

Analysis of attrition patterns across different departments.

<img width="250" height="206" alt="image" src="https://github.com/user-attachments/assets/f4cb8f57-2a6b-457a-b1f7-b8764ccf86b2" />

---

# 🤖 Machine Learning Model

A Logistic Regression classification model was developed to predict employee attrition.

The model was trained using employee demographic, departmental, salary, and performance-related features.

Special attention was given to class imbalance because attrition cases represented a smaller portion of the dataset.

---

# 📊 Model Performance

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Classification Metrics

<img width="434" height="173" alt="image" src="https://github.com/user-attachments/assets/4c229ed7-5676-47f6-bae5-eeec46135cb0" />


**Overall Accuracy:** 47%

The results demonstrate the challenges associated with predicting employee attrition and highlight why recall and F1-score are important metrics for imbalanced classification problems.

---

### Confusion Matrix

<img width="131" height="58" alt="image" src="https://github.com/user-attachments/assets/3575e976-f64a-400a-9c90-30a52a21910d" />

---

## 📌 Feature Importance

The Logistic Regression coefficients indicate which variables were most strongly associated with employee attrition risk.

<img width="289" height="364" alt="image" src="https://github.com/user-attachments/assets/c7d41c5c-e6b9-424c-8142-b8d5d2e3ea57" />

### Key Influential Features

- Salary
- Training Hours
- Department
- Employee Tenure
- Gender
- Performance Rating

---

# 💡 Key Insights

### 💰 Salary Matters

Salary appears to influence employee attrition risk and may play a role in employee retention.

### 🏢 Departmental Differences

Attrition patterns varied across departments, suggesting that organizational factors may affect employee retention.

### ⏳ Employee Tenure is Important

Length of service showed a relationship with employee attrition patterns.

### ⚖️ Class Imbalance Affects Prediction

The dataset contained fewer attrition cases, making prediction more challenging and highlighting the importance of appropriate evaluation metrics.

### 🎯 Accuracy Alone Is Not Enough

Recall and F1-score provided more meaningful insights than accuracy alone when evaluating attrition predictions.

---

# 📋 Recommendations

Based on the analysis, organizations could:

- Monitor employees in higher-risk departments more closely
- Review compensation structures and salary progression
- Improve employee engagement and retention initiatives
- Identify at-risk employees earlier using predictive analytics
- Continuously monitor workforce trends through HR dashboards

---

# 🚀 Future Improvements

Future enhancements to this project may include:

- Random Forest models
- Gradient Boosting models
- Hyperparameter optimization
- Cross-validation
- SMOTE-based class balancing
- Interactive HR analytics dashboards using Power BI
- Model deployment as a web application

---

