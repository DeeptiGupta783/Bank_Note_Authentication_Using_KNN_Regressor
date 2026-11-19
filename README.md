# Bank_Note_Authentication_Using_KNN_Regressor
Banknote Authentication using K-Nearest Neighbors (KNN) classification with different distance metrics.

Project Overview
This project implements the K-Nearest Neighbors (KNN) algorithm to classify banknotes into two categories: Genuine and Forged.

Dataset
Dataset: Banknote Authentication
Source: UCI Machine Learning Repository
Total records after removing duplicates: 1,348
Features: Variance, Skewness, Curtosis, Entropy
Target: Class (Genuine / Forged)

Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook
Project Workflow
Data Loading
Data Exploration
Data Cleaning
Feature and Target Separation
Train-Test Split
Feature Scaling using StandardScaler
KNN Model Training
Distance Metrics Comparison
Actual vs Predicted Results
Unseen Data Prediction

Distance Metrics and Accuracy
Minkowski: 100%
Manhattan: 99.63%
Hamming: 46.67%
Chebyshev: 100%

Minkowski and Chebyshev achieved the highest accuracy on the selected test split.

Conclusion
The KNN algorithm was successfully implemented for binary classification. Four distance metrics were compared, and Minkowski and Chebyshev achieved 100% accuracy on the test dataset.
