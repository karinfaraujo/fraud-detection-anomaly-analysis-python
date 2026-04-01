# 💳 Fraud Detection and Anomaly Analysis in Financial Transactions

## 🔍 Model Explainability

The SHAP summary plot below highlights the variables that contributed the most to fraud prediction.
![SHAP Explainability](https://github.com/karinfaraujo/fraud-detection-anomaly-analysis-python/blob/main/images/shap_summary.png?raw=true)


## 📌 Project Overview

This project focuses on detecting fraudulent financial transactions using machine learning techniques.

Fraud detection is a **highly imbalanced classification problem**, where fraudulent transactions represent only a very small portion of the dataset. The main objective is to build robust predictive models capable of identifying fraud cases while minimizing false negatives.

---

## 🎯 Business Problem

Financial fraud causes significant losses for institutions and customers. Detecting suspicious transactions quickly is essential for reducing risks and improving operational security.

This project aims to develop machine learning models to classify transactions as:

* **Class 0 → Legitimate transaction**
* **Class 1 → Fraudulent transaction**

---

## 📂 Dataset

The dataset used in this project contains anonymized financial transaction records, including transformed features and transaction amount information.

It is a classic fraud detection dataset widely used for machine learning classification problems.

---

## ⚙️ Project Workflow

The project was developed following these steps:

1. 📌 Business Problem
2. 📚 Import Libraries
3. 📥 Load Data
4. ⚖️ Check Class Imbalance
5. 🛠️ Feature Engineering
6. 🤖 Baseline Modeling (Logistic Regression)
7. ⚖️ Data Balancing
8. 🚀 Advanced Model (XGBoost)
9. 📊 Feature Importance
10. 🎯 Hyperparameter Tuning
11. 🔍 Model Explainability (SHAP)

---

## 🧰 Technologies Used

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 📈 Matplotlib
* 📊 Seaborn
* 🤖 Scikit-learn
* 🚀 XGBoost
* 🔍 SHAP
* ☁️ Google Colab

---

## 📈 Key Results

* ✅ Strong improvement in fraud detection after balancing the data
* ✅ XGBoost outperformed Logistic Regression
* ✅ Improved recall for fraudulent transactions
* ✅ Better detection of minority class patterns
* ✅ Identification of the most relevant variables
* ✅ Explainability analysis using SHAP

---

## 💡 Business Insights

This project demonstrates how class imbalance can strongly affect model performance.

After applying balancing techniques and advanced machine learning models, the predictive performance improved significantly, especially for fraud detection.

Feature importance and SHAP analysis provided valuable insights into the variables that most influenced fraud predictions.

---

## 🎯 Conclusion

This project demonstrates the application of machine learning techniques for fraud detection in highly imbalanced datasets, combining:

* 📊 predictive performance
* 🔍 explainability
* 💼 business insights

It highlights the importance of handling class imbalance and using advanced models to improve fraud detection systems.

---

## 🚀 Author

Developed by **Karin Araujo** as part of a Data Analytics / Machine Learning portfolio project.
