
# Credit Card Fraud Detection

## 📌 Project Overview
This project implements a machine learning-based system to detect fraudulent credit card transactions. The dataset is highly imbalanced, making fraud detection a challenging task. Various models such as Logistic Regression, Random Forest, Decision Trees, and XGBoost were applied and evaluated on metrics like Precision, Recall, F1-score, and AUC-ROC.

## 📂 Dataset
- Dataset: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Transactions: 284,807
- Fraud cases: 492 (~0.17% of total)
- Features are anonymized (V1–V28) plus `Time`, `Amount`, and `Class` (target variable).

## ⚙️ Installation
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt

🔍 Methodology

Data Preprocessing & Scaling

Handling Imbalanced Data (SMOTE / Undersampling)

Exploratory Data Analysis (EDA)

Model Training:

Logistic Regression

Decision Tree

Random Forest

XGBoost

Model Evaluation:

Confusion Matrix

Precision, Recall, F1-Score

ROC-AUC

---->> Results

Random Forest & XGBoost achieved the best detection performance.

Logistic Regression provided interpretable insights.

Precision-Recall tradeoff is highlighted due to high imbalance.
