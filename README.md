# Credit Card Fraud Detection

## 📌 Project Overview
This project applies machine learning techniques to detect fraudulent credit card transactions. Since fraud cases represent less than 0.2% of all transactions, the dataset is highly imbalanced, making the problem challenging. The models are evaluated on **Precision, Recall, F1-score, and AUC-ROC**, as accuracy alone is not meaningful in such cases.

## 📂 Dataset
- Source: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Transactions: 284,807
- Fraud cases: 492 (~0.17%)
- Features are anonymized (V1–V28) + `Time`, `Amount`, and `Class` (target variable).

## ⚙️ Installation
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt


Methodology

Data Preprocessing (scaling, cleaning)

Handling Class Imbalance

Exploratory Data Analysis (EDA)

Model Training:

Logistic Regression (LogisticRegression)

Random Forest (RandomForestClassifier)

Gradient Boosting (GradientBoostingClassifier)

Model Evaluation:

Confusion Matrix

Precision, Recall, F1-Score

ROC-AUC Curve

📊 Results

Gradient Boosting and Random Forest achieved the best detection performance.

Logistic Regression provided interpretable insights but lower recall.

Highlighted the precision-recall tradeoff due to high imbalance.
