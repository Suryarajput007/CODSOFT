# 💳 Credit Card Fraud Detection System

## 🚀 Project Overview

This repository contains the implementation of **Task 2 – Credit Card Fraud Detection** completed as part of the **CodSoft Machine Learning Internship**.

The objective of this project is to develop a machine learning model capable of identifying fraudulent credit card transactions by analyzing transaction patterns and detecting unusual behavior. The system is designed to distinguish between legitimate and potentially fraudulent transactions, helping improve financial security and fraud prevention.

---

## 🎯 Problem Statement

Credit card fraud is one of the most significant challenges in modern digital banking systems. Fraudulent transactions typically represent only a small fraction of all transactions, creating a highly imbalanced classification problem.

Traditional accuracy metrics can be misleading in such cases. Therefore, this project focuses on building a model that can effectively identify fraudulent activities while minimizing false negatives and false positives.

---

## ✨ Key Features

* Fraud Detection using Machine Learning
* Handling Imbalanced Data
* Transaction Risk Analysis
* Automated Fraud Prediction
* Real-Time Transaction Validation
* Model Performance Evaluation

---

## ⚙️ Machine Learning Pipeline

```text
Raw Transaction Data
        │
        ▼
Data Preprocessing
        │
        ▼
Feature Scaling (StandardScaler)
        │
        ▼
Train-Test Split (80:20)
        │
        ▼
Random Forest Classifier
        │
        ▼
Fraud Prediction Engine
        │
        ▼
Risk Assessment Output
```

---

## 📊 Dataset Generation

To simulate real-world transaction behavior:

* Generated 2,000 synthetic transaction records
* Included transaction amount and distance-based features
* Introduced fraudulent transaction patterns
* Created realistic anomaly distributions for model training

---

## 🔍 Data Preprocessing

The following preprocessing techniques were applied:

* Missing value handling
* Feature scaling using StandardScaler
* Dataset balancing considerations
* Feature normalization for improved model performance

---

## 🤖 Model Selection

### Random Forest Classifier

A Random Forest Classifier was selected because it:

* Handles non-linear relationships effectively
* Performs well on classification tasks
* Reduces overfitting through ensemble learning
* Provides robust performance on tabular datasets

Model Configuration:

* Algorithm: Random Forest Classifier
* Estimators: 100 Trees
* Train-Test Split: 80:20
* Evaluation Metrics: Accuracy, Precision, Recall, F1-Score

---

## 📈 Sample Predictions

### Scenario A: Normal Transaction

Transaction Amount: $32.40

Distance from Home: 4.2 KM

Prediction:

🟢 Legitimate Transaction

Low Risk Score

---

### Scenario B: Suspicious Transaction

Transaction Amount: $2,450.00

Distance from Home: 680.5 KM

Prediction:

🚨 Fraudulent Transaction Detected

High Risk Score

---

### Scenario C: Online Subscription

Transaction Amount: $14.99

Distance from Home: 0 KM

Prediction:

🟢 Legitimate Transaction

Low Risk Score

---

## 📊 Performance Evaluation

The model performance was evaluated using:

* Confusion Matrix
* Classification Report
* Accuracy Score
* Precision Score
* Recall Score
* F1 Score

These metrics help measure the effectiveness of the model in detecting fraudulent transactions while minimizing classification errors.

---

## 📁 Project Structure

```text
Credit_Card_Fraud_Detection/
│
├── dataset/
│   └── credit_card_transactions.csv
│
├── screenshots/
│   ├── advanced_data_analysis.png
│   └── advanced_confusion_matrix.png
│
├── fraud_detection.ipynb
├── fraud_detection.py
├── requirements.txt
└── README.md
```

---

## 🛠️ Technologies Used

### Programming Language

* Python 3

### Libraries

* Pandas
* NumPy
* Scikit-Learn

### Visualization

* Matplotlib
* Seaborn

### Development Environment

* Jupyter Notebook
* GitHub
* VS Code

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Machine Learning Classification
* Data Preprocessing
* Fraud Detection Techniques
* Feature Engineering
* Model Evaluation
* Real-World Data Analysis

---

## 🔮 Future Enhancements

* Real-Time Fraud Monitoring Dashboard
* Deep Learning-Based Detection Models
* API Integration for Live Predictions
* Advanced Feature Engineering
* Deployment using Flask or Streamlit

---

## 👨‍💻 Author

**Surya Rajput**

BCA Student | CORE University

CodSoft Machine Learning Intern

---

## ⭐ Acknowledgement

This project was developed as part of the **CodSoft Machine Learning Internship Program**, providing hands-on experience in applying machine learning techniques to real-world financial fraud detection challenges.
