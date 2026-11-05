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

## 🎯 Why Recall Matters

Fraud detection is a highly imbalanced classification problem, making **accuracy** less reliable as the primary metric.

A **False Negative** means:

> Actual fraud → Predicted as legitimate

Since missing fraudulent transactions can lead to financial loss, **Recall is prioritized**, while Precision and F1-Score are also considered to control false positives.

Key metrics:

- **Recall** – Detect as many fraud cases as possible
- **Precision** – Reduce false fraud alerts
- **F1-Score** – Balance Precision and Recall
- **PR-AUC** – Evaluate performance under class imbalance
- **ROC-AUC** – Measure overall class discrimination

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

| Feature | Value |
|---|---:|
| Total Transactions | 284,807 |
| Legitimate | 284,315 |
| Fraudulent | 492 |
| Fraud Rate | ~0.17% |
| Features | Time, Amount, V1–V28 |
| Target | Class |

`Class = 0` → Legitimate  
`Class = 1` → Fraudulent

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

The initial Logistic Regression model using Random Undersampling achieved:

| Metric | Score |
|---------|-------|
| Test Accuracy | **94.4%** |
| Precision | **98.9%** |
| Recall | **89.8%** |
| F1-Score | **94.1%** |

> **Note:** These baseline results were obtained after undersampling and should not be considered representative of the original 0.17% fraud distribution. The improved version will use a more realistic evaluation strategy.

---

## 📁 Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── fraud-detection-using-regression-model.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

- [ ] Compare Logistic Regression, Random Forest, XGBoost 
- [ ] Apply SMOTE and class-weighted approaches
- [ ] Use stratified train/test evaluation with training-only resampling
- [ ] Add Stratified K-Fold Cross-Validation
- [ ] Perform hyperparameter tuning
- [ ] Optimize classification threshold for higher fraud recall

---

## ⭐ Skills Demonstrated

**Machine Learning • Fraud Detection • EDA • Imbalanced Classification • Data Preprocessing • Logistic Regression • Model Evaluation • Precision • Recall • F1-Score • Python • Pandas • NumPy • Scikit-learn** 
