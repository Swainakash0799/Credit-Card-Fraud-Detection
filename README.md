# 💳 Credit Card Fraud Detection using Machine Learning

A machine learning project that detects fraudulent credit card transactions using **Logistic Regression**. The project handles the highly imbalanced nature of fraud detection by applying **undersampling** and evaluates the model using multiple classification metrics.

---

## 📌 Project Overview

Credit card fraud has become a significant challenge in the financial industry. This project builds a binary classification model capable of distinguishing between legitimate and fraudulent transactions using historical transaction data.

The workflow includes data preprocessing, exploratory analysis, class balancing through undersampling, feature scaling, model training, and performance evaluation.

---

## 🚀 Features

* 📊 Performs exploratory data analysis (EDA)
* 🔍 Detects missing values and analyzes dataset structure
* ⚖️ Handles class imbalance using **Random Undersampling**
* 📈 Standardizes numerical features using `StandardScaler`
* 🤖 Trains a **Logistic Regression** classification model
* 📉 Evaluates performance using:

  * Accuracy
  * Precision
  * Recall
  * F1-Score
  * Confusion Matrix
  * Classification Report

---

## 📂 Dataset
Link:https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
The project uses the **Credit Card Fraud Detection Dataset**, which contains anonymized credit card transactions.

**Dataset Features**

* Time
* Amount
* V1 – V28 (PCA-transformed features)
* Class

  * `0` → Legitimate Transaction
  * `1` → Fraudulent Transaction

> Due to the highly imbalanced dataset, random undersampling is performed before training the model.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
---

## 📁 Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── fraud-detection.ipynb      # Complete ML workflow            
├── README.md
└── requirements.txt
```

---

## 🔬 Machine Learning Pipeline

1. Load the dataset
2. Explore the dataset
3. Check missing values
4. Analyze fraud vs legitimate transactions
5. Balance the dataset using undersampling
6. Split data into training and testing sets
7. Standardize features
8. Train a Logistic Regression model
9. Evaluate the model using multiple metrics

---

## 📊 Evaluation Metrics

The model is evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

These metrics provide a better understanding of model performance, especially for imbalanced datasets.

---

## 📚 Libraries Used

```python
numpy
pandas
scikit-learn
```

---

## 🎯 Future Improvements

* Train advanced models such as:
  * Random Forest
  * XGBoost
  * LightGBM
* Apply SMOTE instead of random undersampling
* Perform hyperparameter tuning
* Deploy the model using Streamlit or Flask
* Compare multiple machine learning algorithms

---
