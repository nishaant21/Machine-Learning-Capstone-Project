# ML Project: Bank Customer Churn Prediction
Project on Bank Customer Churn prediction: Aims to analyze customer churn and derive insights to help the bank improve customer retention strategies. Understanding the factors that contribute to churn is crucial for businesses to retain customers and maintain long-term profitability.

# Goal: The goal of this analysis is to understand the factors influencing customer churn in the bank. By exploring various features such as customer demographics, financial attributes, and behavioral patterns, the aim is to build a predictive model to identify key drivers of customer churn. The analysis seeks to uncover insights that can help in retaining customers and improving overall customer satisfaction.

## Introduction
Customer churn is a significant issue in the banking sector. This project aims to predict which customers are likely to leave the bank using machine learning techniques. Accurate predictions allow banks to take proactive measures to retain customers.

## Dataset
The dataset used in this project contains customer information and their churn status. It includes features such as age, balance, tenure, and more. The dataset is pre-processed to handle missing values and encode categorical variables.

## Exploratory Data Analysis (EDA)
EDA is performed to understand the dataset better and to uncover patterns, anomalies, and relationships between variables. Various visualizations are used to summarize the main characteristics of the data.

## Feature Selection
### Chi-Squared Test
The Chi-Squared test is used to determine the relationship between categorical features and the target variable (churn).

### ANOVA
ANOVA (Analysis of Variance) is used to identify whether there are any statistically significant differences between the means of numerical features for different churn statuses.

## Machine Learning Models
Several machine learning algorithms are employed to build the prediction models. The performance of each model is evaluated using appropriate metrics.

### Logistic Regression
A linear model used for binary classification tasks.

### Decision Tree
A non-linear model that splits the data into subsets based on feature values to make predictions.

### Random Forest
An ensemble method that uses multiple decision trees to improve the predictive performance and control overfitting.

### Support Vector Machine (SVM)
A model that finds the hyperplane which best separates the classes in the feature space.

### Naive Bayes
A probabilistic classifier based on Bayes' theorem with the assumption of independence between predictors.

## Results and Evaluation
The models are evaluated using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC. The results are compared to determine the best performing model for this task.

## Conclusion
The project demonstrates the application of various machine learning techniques to predict customer churn in the banking sector. Insights from feature importance help in understanding the key drivers of churn.
