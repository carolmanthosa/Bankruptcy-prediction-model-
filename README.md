

📌 Project Summary

This project investigates the use of machine learning algorithms for predicting the likelihood of company bankruptcy. Business failure has significant implications for creditors, investors, and employees, which makes the development of reliable prediction models vital for financial risk management.

The study applied several classification models to financial datasets, focusing on data preprocessing, class imbalance handling, feature reduction, and performance evaluation.

🔑 Key Features

Dataset: Financial indicators of companies (Polish/Taiwan bankruptcy dataset).

Preprocessing: Missing value imputation, normalization, and categorical encoding.

Class Imbalance Handling: Applied SMOTE to balance bankruptcy and non-bankruptcy cases.

Feature Reduction: Used PCA for dimensionality reduction and interpretability.

Models Tested: Logistic Regression, Random Forest, XGBoost, AdaBoost, and Support Vector Machines.

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, ROC Curve, and AUC.

🎯 Objective

Improve predictive performance by addressing imbalanced data and high dimensionality.

Identify the best-performing algorithm for bankruptcy prediction.

Provide insights into the financial indicators most associated with bankruptcy risk.

🛠️ Tools & Technologies

Programming Language: Python

Libraries: pandas, NumPy, scikit-learn, imbalanced-learn, XGBoost, matplotlib

Environment: Jupyter Notebook

📊 Results

Random Forest and XGBoost consistently achieved the highest predictive performance, with strong AUC scores indicating reliable bankruptcy classification.

Logistic Regression performed well in terms of interpretability but was outperformed by ensemble methods in predictive power.

AdaBoost showed competitive results but was slightly less stable across multiple test runs.

Support Vector Machines (SVM) demonstrated solid performance but required significant tuning and computational resources.

Overall, XGBoost was identified as the best-performing model, balancing accuracy, recall (bankruptcy detection), and AUC.

📈 Expected Impact

Provides an early-warning system for financial distress.

Helps investors, creditors, and policymakers in making informed decisions.

Contributes to improving predictive modeling approaches in financial risk research.
