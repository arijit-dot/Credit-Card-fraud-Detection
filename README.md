# Credit Card Fraud Detection

## 📌 Overview
Machine learning pipeline to detect fraudulent credit card transactions in a highly imbalanced dataset. Focus is on handling class imbalance and evaluating with metrics that matter for fraud detection.

## 📂 Dataset
- Source: Kaggle Credit Card Fraud Detection (anonymized features V1–V28 + `Time`, `Amount`, target `Class`)
- Fraud prevalence ≈ 0.17% (extreme imbalance)

## ⚙️ Installation
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt

▶️ Usage
jupyter notebook credit_card_Fraud_detection.ipynb

🔍 Methodology

Data preprocessing (scaling/prep)

Class-imbalance handling (resampling/balanced splits)

Exploratory data analysis

Model training and comparison

Evaluation with classification report

🤖 Models Implemented

Logistic Regression (LogisticRegression)

Random Forest (RandomForestClassifier)

Gradient Boosting (GradientBoostingClassifier)

Notebook also includes balanced variants (e.g., logistic_model_b, rf_b, gbc_b).

🧪 Evaluation Metrics

Precision, Recall, F1-score, Support (from classification_report)

Emphasis on Recall (catching fraud) with acceptable Precision (reducing false alarms)

📊 Results (example summary)

Ensemble methods (Random Forest, Gradient Boosting) outperform Logistic Regression on recall/F1.

Logistic Regression remains useful for interpretability and as a baseline.
