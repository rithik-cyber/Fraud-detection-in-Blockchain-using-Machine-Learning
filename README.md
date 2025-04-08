# Fraud-detection-in-Blockchain-using-Machine-Learning
Project Overview

This project focuses on detecting fraudulent transactions in the Ethereum blockchain using machine learning techniques. By leveraging a labeled Ethereum transaction dataset, the system identifies patterns and characteristics associated with fraudulent activity, helping to improve trust and transparency in blockchain-based platforms such as e-commerce.

Dataset

Name: Ethereum Transaction Dataset

Format: .csv

Source: Includes both normal and fraudulent transactions

Features Include:

Average time between sent/received transactions

Total Ether sent/received

Number of created contracts

Unique received/sent addresses

ERC20 token features

Label: FLAG (0 = Normal, 1 = Fraudulent)

Project Files:

1.ipynb: Data preprocessing, feature selection, visualization

2.ipynb: Model training and evaluation (including tuning and ROC analysis)

transaction_dataset.xls: Original Ethereum transaction dataset

boxplots.png: Visual comparison of features (e.g., Created Contracts vs Fraud Flag)

correlation_matrix.png: Heatmap of feature correlation

roc_curve_xgb_tuned.png: ROC curve for tuned XGBoost classifier

Exploratory Data Analysis

Boxplots: Compared how features vary between fraudulent and non-fraudulent transactions

Correlation Matrix: Visualized inter-feature correlation and relation to FLAG

Model:

Algorithm Used: XGBoost Classifier

Tuning: Hyperparameter tuning performed for better accuracy

Evaluation Metric: ROC AUC Score

Result: AUC = 1.00 (indicating a perfect classifier on this dataset)

Key Insights:

Fraudulent accounts generally have very low interaction metrics.

Most fraudulent transactions do not involve creating contracts or receiving from many unique addresses.

Feature correlation with fraud flag is low, indicating non-linear patterns best captured by tree-based models like XGBoost.

Usage:

Clone the repository

Install required libraries:

pip install pandas numpy matplotlib seaborn xgboost scikit-learn

Run 1.ipynb for data analysis and visualization

Run 2.ipynb for model training and evaluation

Applications:

E-commerce fraud detection

Smart contract anomaly monitoring

Blockchain forensic analysis

Conclusion: Machine learning can effectively detect fraudulent behavior in blockchain by learning from historical transaction patterns. XGBoost, in particular, provided excellent results with high AUC, demonstrating its suitability for fraud classification tasks in Ethereum-based systems.

Author: Rithik 
Date: December 2024


