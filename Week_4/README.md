# Week 4 Internship Task
## Machine Learning Model Development and Evaluation

### Dataset
IBM HR Analytics Employee Attrition & Performance

### Domain
Human Resources / Employee Attrition

### Objective
The objective of Week 4 was to develop and evaluate a machine learning classification model for predicting employee attrition using Python. The complete workflow included data preprocessing, categorical encoding, train-test splitting, feature scaling, model training, and evaluation.

### Model Used
Logistic Regression

Logistic Regression was selected because employee attrition is a binary classification problem with two possible outcomes: Yes or No.

### Data Preprocessing
- Converted Attrition into a binary target variable.
- Encoded categorical features using one-hot encoding.
- Split the dataset into training and testing sets using an 80:20 ratio.
- Applied standardization using StandardScaler.

### Model Evaluation Results
- Accuracy: 86.05%
- Precision: 61.54%
- Recall: 34.04%
- F1-Score: 43.84%
- AUC: 0.8079

### Key Finding
The model achieved good overall accuracy and an AUC of 0.8079. However, recall for the Attrition class was only 34.04%, showing that the model missed a considerable number of employees who actually left the organization.

### Visualizations
The folder contains:
- Confusion Matrix
- ROC Curve
- Model Performance Metrics

### Improvements
Future improvements can include handling class imbalance, tuning the classification threshold, using cross-validation, selecting important features, and comparing Logistic Regression with other machine learning algorithms.

### Author
**Kora Ahalya**
