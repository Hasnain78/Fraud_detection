# 💳 Credit Card Fraud Detection using Isolation Forest

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using **Machine Learning** techniques.  
It uses the **Isolation Forest algorithm**, which is highly effective for anomaly detection in imbalanced datasets.

---

## 🚀 Objectives
- Detect fraudulent transactions from a highly imbalanced dataset
- Apply preprocessing and feature scaling
- Build an anomaly detection model using Isolation Forest
- Evaluate model performance

---

## 🛠️ Tech Stack
- Python 🐍
- Pandas
- NumPy
- Scikit-learn

---

## 📂 Dataset
The dataset used is the **Credit Card Fraud Detection dataset**, which contains:
- Transactions made by credit cards
- Highly imbalanced data (fraud cases are very rare)

> ⚠️ Note: Dataset path in the notebook is local. Update it before running.

---

## 🔍 Workflow

### 1. Data Loading
```python
df = pd.read_csv('creditcard.csv')
