# Credit-Card-Fraud-Detection

## Overview
This project focuses on building a machine learning model to predict credit card fraud. Various models including logistic regression, random forests, and support vector machines (SVM) were employed to achieve this objective. The aim is to develop an accurate and reliable predictive model that can assist in identifying fraudulent transactions and preventing financial losses.

## Objective
The primary objective of this project is to develop a predictive model that accurately identifies instances of credit card fraud. By leveraging machine learning algorithms, we aim to classify transactions as legit transactions and fraudulent transactions in order to enhance fraud detection capabilities and thereby minimising the impact of fraudulent activities on financial transactions.

## Dataset
The dataset used for this project contains transactions made by credit cards in September 2013 by European cardholders. It consists of features such as transaction amount, time, and various anonymized numerical features obtained through PCA transformation due to privacy concerns. The target variable is a binary indicator representing whether a transaction is fraudulent or not.

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Methodology
* Data Preprocessing: Cleaning the dataset, handling missing values, scaling features, and splitting into training and testing sets.
* Model Selection: Training logistic regression, random forests (using gridsearch), and SVM models on the training data.
* Model Evaluation: Assessing model performance using evaluation metrics such as accuracy, precision, recall, and F1-score.
  
## Tools and Libraries
* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn
  
## Results
Random Forest Model outperformed others with higher accuracy and F1-score.

## Conclusion
This project demonstrates the application of machine learning techniques to address the challenge of credit card fraud detection. By leveraging models like logistic regression, random forests, and SVM, a predictive model capable of identifying fraudulent transactions with high accuracy has been developed. Further improvements and optimizations can be explored to enhance the model's performance and reliability in real-world scenarios.



