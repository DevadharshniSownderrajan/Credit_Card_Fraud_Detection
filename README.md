# 💳 Fraud Detection using Machine Learning

## 📌 Overview

This project focuses on detecting fraudulent transactions using machine learning classification algorithms. The dataset contains transaction-related features, and the models classify each transaction as **Fraud** or **Non-Fraud**.

The project also demonstrates the complete machine learning workflow, including data cleaning, exploratory data analysis, preprocessing, model training, and evaluation.

## 🎯 Objective

To build and compare different machine learning classification models for identifying fraudulent transactions and evaluate their performance using appropriate classification metrics.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

## 🔄 Workflow

1. Data Loading
2. Data Cleaning
3. Missing Value Handling
4. Duplicate Check
5. Outlier Analysis
6. Exploratory Data Analysis
7. Encoding Categorical Features
8. Train-Test Split
9. Feature Scaling
10. Model Training
11. Model Evaluation
12. Confusion Matrix Analysis

## 🤖 Machine Learning Models

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* XGBoost

## 📊 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## 📈 Results

| Model               | Accuracy | Precision | Recall | F1-Score |
| ------------------- | -------: | --------: | -----: | -------: |
| Logistic Regression |    95.2% |        0% |     0% |       0% |
| Decision Tree       |    91.2% |     4.55% |  4.17% |    4.35% |
| Random Forest       |    95.2% |        0% |     0% |       0% |
| KNN                 |    95.1% |        0% |     0% |       0% |
| SVM                 |    95.2% |        0% |     0% |       0% |
| XGBoost             |    94.8% |        0% |     0% |       0% |

## 🔎 Key Finding

The dataset was imbalanced, with significantly more non-fraud transactions than fraud transactions. Although the models achieved high accuracy, their ability to detect fraudulent transactions was limited.

This demonstrates why **accuracy alone is not sufficient for evaluating fraud detection models**. Precision, recall, F1-score, and the confusion matrix provide more useful information for this type of classification problem.




## 📌 Note

This project uses a **synthetic dataset created for machine learning practice and educational purposes**. It does not represent real banking or financial transaction data.
