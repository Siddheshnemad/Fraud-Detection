# 💳 Credit Card Fraud Detection using Machine Learning

## 🚀 Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques on a highly imbalanced dataset. The goal is to build a system that can effectively identify fraud while minimizing false positives.

---

## 🎯 Problem Statement

Fraudulent transactions are rare but highly impactful.
The objective is to detect fraud cases accurately while balancing the trade-off between catching fraud and avoiding unnecessary alerts.

---

## ⚙️ Approach
- Data cleaning & EDA
- Feature scaling
- SMOTE for imbalance handling
- Models: Logistic Regression, Random Forest
---

## 📈 Results
- Accuracy: 95%
- Recall: 82%
- ROC-AUC: 0.86

---

## 📊 Dataset

* 284,000+ transactions
* Highly imbalanced dataset (<1% fraud cases)
* Features transformed using PCA (V1–V28)
* Additional features: Time, Amount

---

## 🔍 Exploratory Data Analysis (EDA)

* Severe class imbalance observed
* Fraud transactions are significantly fewer than normal ones
* Transaction amount and timing show subtle differences

---

## ⚙️ Approach

### 🔹 Handling Imbalance

* Undersampling (baseline approach)
* Class weighting (real-world approach)

---

### 🔹 Models Used

* Logistic Regression (with class balancing)
* Random Forest Classifier

---

## 📈 Model Evaluation

Due to class imbalance, evaluation focused on:

* Precision
* Recall (Fraud Detection)
* ROC-AUC
* Precision-Recall Curve

---

## 🔥 Advanced Techniques

### ✅ Threshold Tuning

Optimized decision threshold using F1-score instead of default 0.5.

### ✅ Precision-Recall Analysis

Used PR curve to better evaluate performance on imbalanced data.

### ✅ Confusion Matrix Comparison

Analyzed model performance before and after threshold optimization.

### ✅ Feature Importance

Identified key features contributing to fraud detection using Random Forest.

---

## 📊 Key Insights

* Fraud detection requires prioritizing **recall** to minimize financial loss
* Lowering threshold improves fraud detection but increases false positives
* Precision-recall trade-off is critical in real-world deployment

---

## 💼 Business Impact

* Helps financial institutions detect fraudulent transactions early
* Reduces financial losses due to undetected fraud
* Highlights trade-off between fraud detection and customer experience

---

## 🧠 Learnings

* Handling highly imbalanced datasets
* Importance of evaluation metrics beyond accuracy
* Threshold optimization for real-world ML systems
* Translating model performance into business decisions

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 🔮 Future Improvements

* Hyperparameter tuning (GridSearchCV)
* Use of advanced models (XGBoost, LightGBM)
* Real-time fraud detection system
* Model deployment using APIs

---

## 📌 Conclusion

This project demonstrates how machine learning can be applied to detect fraud in highly imbalanced scenarios while balancing detection performance and user experience.

---

## 👨‍💻 Author

Siddhesh Nemad
