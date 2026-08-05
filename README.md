# 💳 Credit Card Fraud Detection

A machine learning project that detects fraudulent credit card transactions using **Logistic Regression**. The project addresses the challenge of **highly imbalanced data** through undersampling and evaluates model performance using multiple classification metrics.

---

## 📌 Project Overview

Credit card fraud detection is a critical application of machine learning in the financial industry. This project analyzes **284,807 real-world credit card transactions** to classify transactions as **legitimate** or **fraudulent**.

The workflow covers the complete machine learning pipeline, including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Handling class imbalance using undersampling
- Feature scaling
- Model training
- Model evaluation

---

## 🚀 Key Features

- 📊 Performed Exploratory Data Analysis (EDA)
- 🧹 Preprocessed and cleaned transaction data
- ⚖️ Addressed class imbalance using Random Undersampling
- 📈 Applied feature scaling with StandardScaler
- 🤖 Built a Logistic Regression classification model
- 📉 Evaluated model performance using multiple classification metrics

---

## 📂 Dataset

**Dataset:** Credit Card Fraud Detection Dataset

🔗 https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Dataset Summary

| Feature | Description |
|----------|-------------|
| Transactions | **284,807** |
| Fraud Cases | **492** |
| Features | Time, Amount, V1–V28 |
| Target | Class (0 = Legitimate, 1 = Fraud) |

The dataset is highly imbalanced, making fraud detection a challenging binary classification problem.

---

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Machine Learning Workflow

1. Load and explore the dataset
2. Perform Exploratory Data Analysis (EDA)
3. Handle missing values and inspect data distribution
4. Balance the dataset using Random Undersampling
5. Split data into training and testing sets
6. Scale numerical features
7. Train a Logistic Regression model
8. Evaluate model performance

---

## 📊 Model Performance

| Metric | Score |
|---------|-------|
| Test Accuracy | **94.4%** |
| Precision | **98.9%** |
| Recall | **89.8%** |
| F1-Score | **94.1%** |

These metrics demonstrate reliable fraud detection while maintaining high precision on an imbalanced dataset.

---

## 📁 Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── fraud-detection.ipynb
├── README.md
└── requirements.txt
```

---

## 🎯 Future Improvements

- Implement SMOTE for advanced class balancing
- Compare multiple classification algorithms (Random Forest, XGBoost, LightGBM)
- Perform hyperparameter tuning
- Deploy the model using Streamlit
- Build an interactive dashboard for fraud analysis

---

## ⭐ Key Skills Demonstrated

- Machine Learning
- Fraud Detection
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Handling Imbalanced Data
- Feature Scaling
- Classification
- Model Evaluation
- Python
- NumPy
- Pandas
- Scikit-learn
