Breast Cancer Classification using Machine Learning
Project Overview:-

This project uses the Breast Cancer Wisconsin Dataset from sklearn to build and compare multiple supervised machine learning classification models.

The main goal is to predict whether a tumor is:

Malignant (Cancerous)
Benign (Non-Cancerous)

Five classification algorithms were implemented and evaluated to identify the best-performing model.

Dataset:-

The dataset is available directly from the sklearn.datasets library.

It contains:

569 samples
30 numerical features
2 target classes
Target Labels
0 → Malignant
1 → Benign
🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

Project Workflow:-

1️:-Data Loading

Loaded the breast cancer dataset using load_breast_cancer().

2️:-Data Preprocessing
Checked for missing values
Applied feature scaling using StandardScaler
3️:-Train-Test Split

Split dataset into:

80% Training Data
20% Testing Data
4️:-Models Implemented
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)
k-Nearest Neighbors (KNN)
5️:-Model Evaluation

Used:

Accuracy Score
Confusion Matrix
Classification Report

Algorithms Used:-
Logistic Regression

Used for binary classification problems by predicting probabilities.

Decision Tree

Builds tree-like decision rules for classification.

Random Forest

Uses multiple decision trees and combines predictions.

Support Vector Machine (SVM)

Finds the best boundary line to separate classes.

K-Nearest Neighbors (KNN)

Classifies based on nearest data points.

Model Performance:-
Model	Accuracy
Random Forest	97%
SVM	97%
Logistic Regression	96%
KNN	95%
Decision Tree	93%

Accuracy may vary slightly depending on random state.

Best Model:-

Random Forest / SVM

Lowest Performance:-

Decision Tree

Key Learnings:-
Importance of feature scaling
Model comparison techniques
Binary classification concepts
Evaluation metrics in machine learning
Real-world healthcare dataset analysis

How to Run the Project:-
pip install pandas numpy scikit-learn matplotlib seaborn

Run the Python file:

python breast_cancer_classification.py
Project Structure
Breast-Cancer-Classification/
│── breast_cancer_classification.py
│── README.md

Author:-
Mohamed Shihad
