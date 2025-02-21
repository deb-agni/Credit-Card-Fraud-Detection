# Credit-Card-Fraud-Detection
This is a Credit Card Fraud Detection ML model that uses credentials data to help predict whether a transaction is normal or fraudulent.
---

**Project Title:** Credit Card Fraud Detection

**Author:** Deb Agni Patra

## Description
This project focuses on detecting fraudulent credit card transactions using machine learning models. A DecisionTreeClassifier (DTC) model was chosen, achieving an accuracy of approximately 93%.

## Dataset
The dataset used is highly imbalanced:
- **0** → Normal transactions
- **1** → Fraudulent transactions

The project applies dataset balancing techniques to improve fraud detection.

## Installation & Requirements
Ensure you have the following dependencies installed before running the notebook:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
Alternatively, check the notebook for any additional required libraries.

## Usage
1. Load the dataset and preprocess it.
2. Perform Exploratory Data Analysis (EDA) and handle imbalanced data.
3. Split the dataset into training and testing sets.
4. Train multiple models:
   - Logistic Regression (LR)
   - Decision Tree Classifier (DTC)
   - Random Forest Classifier (RFC)
   - Support Vector Classifier (SVC)
   - K-Nearest Neighbors (KNN)
5. Evaluate model performance using accuracy and other metrics.

## Results
The DecisionTreeClassifier model achieved an accuracy of approximately 93%. Further tuning and alternative models may be explored for better fraud detection.

## Contributors
- **Deb Agni Patra**

## License
This project is for educational purposes. You may modify and use it as needed.

