# Improving Employee Retention by Predicting Employee Attrition Using Machine Learning
*Author Fasya Melia Indahsari*

## Objective
The primary objective of this project is to analyze employee data to predict attrition and develop strategies to improve employee retention. The goal is to identify employees likely to resign and implement targeted retention strategies to reduce turnover rates.

## Tools & Techniques
- Programming Language: Python
- Libraries: Pandas, Matplotlib, Seaborn, Scikit-learn
- Machine Learning Models: Random Forest, AdaBoost, K-Nearest Neighbors, Logistic Regression, XGBoost, Decision Tree, Extra Trees

## Content Overview
### Introduction
The importance of predicting employee attrition to prevent resignations.

## Key tools and techniques used for analysis.
### EDA and Data Preprocessing
- Missing Values: Identification and handling of missing data using median and mode replacements.
- Data Cleaning: Conversion and replacement of values, and dropping of irrelevant columns.
- Data Insights: Analysis of employee retention rates and key historical trends.

### Employee Distribution and Resignations
- Distribution by Role: Analysis of top roles within the company, with a focus on engineering and product design roles.
- Resignations by Career Level: Insights into resignation trends among Fresh Graduates, Mid-Level, and Senior-Level employees.
- Resignation Count by Role: Breakdown of resignation numbers by specific roles within the company.

## Modeling
### Building an Automated Resignation Prediction Model
- Data Splitting: Separation of data into training and testing sets.
- Normalization: Feature scaling using StandardScaler.
- Handling Imbalance: Application of SMOTE to address class imbalance.
- Model Performance: Evaluation of various models with metrics such as accuracy, precision, recall, and time elapsed.

### Best Performing Model
- Random Forest: Selected as the best model due to its high accuracy, speed, and reliability.

### Performance Metrics
- ROC Curve and AUC: Demonstrates the model's effectiveness in distinguishing between classes with a strong AUC of 0.93.
- Specificity and Recall: Detailed analysis of the model's reliability in predicting resignations and non-resignations.

## Business Recommendations
- Targeted Employee Engagement: Strategies for high-risk roles.
- Career Development Opportunities: Suggestions for growth-oriented roles.
- Work-Life Balance: Recommendations for improving job satisfaction.
- Continuous Monitoring and Feedback: Importance of using predictive models and employee feedback for ongoing improvement.
