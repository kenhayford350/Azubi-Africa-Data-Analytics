# Azubi-Africa-Data-Analytics
A data analytics project using banking campaign data to predict term deposit subscriptions. Includes exploratory data analysis, feature engineering, ML model development, performance evaluation, and actionable business recommendations.

# 📊 Term Deposit Subscription Prediction

This repository contains a data analytics project aimed at predicting whether clients will subscribe to a term deposit based on marketing campaign data from a Portuguese bank. The project covers the full data science workflow—from data exploration to model deployment—and includes actionable business insights.

---

## 🎯 Project Objective

To build a machine learning model that predicts a client’s likelihood of subscribing to a term deposit using features like age, job, education, contact method, call duration, and past campaign outcomes. This helps optimize marketing efforts and improve customer targeting.

---

## 🧾 Dataset Description

The data comes from direct marketing campaigns conducted via phone calls. The dataset includes:

- `bank-additional-full.csv` – Main dataset used (41,188 records, 20 features).
- Target Variable: `y` (binary – "yes" or "no")

---

## 📌 Key Steps

### 1. Exploratory Data Analysis (EDA)
- Analyzed distribution of categorical and numerical variables.
- Identified class imbalance, feature importance, and patterns in subscription behavior.

### 2. Feature Engineering
- Encoded categorical features.
- Assessed importance of variables (e.g., duration, poutcome, month).
- Addressed class imbalance using oversampling (SMOTE) and class weights.

### 3. Model Building
- Trained multiple ML models including Logistic Regression and Random Forest.
- Selected the best-performing model based on metrics like accuracy, recall, and F1-score.

### 4. Model Evaluation
- Accuracy, Precision, Recall, and F1 Score evaluated.
- Special handling for imbalanced classes to avoid false positives.

---

## 📈 Key Insights

- **Call duration** has the strongest correlation with "yes" outcomes.
- **Cellular contact** outperforms telephone.
- Clients with **positive past responses** are more likely to subscribe.
- **March, September, and December** are peak subscription months.
- **Students, retirees, and highly educated clients** show higher interest.

---

## ✅ Recommendations

- Prioritize **mobile contact methods**.
- **Target campaigns** in peak months (March, Sept, Dec).
- Focus on clients with **prior positive interactions**.
- Avoid using `duration` for live predictions—only use for post-call evaluation.
- Tailor messaging for **educated and retired demographics**.

---

## 🧠 Technologies Used

- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook
- Google Colab (for demonstration/deployment)
- Git & GitHub

---

## 📂 Contents

- `new.ipynb` – Full notebook with EDA, modeling, and insights.
- `bank-additional-full.csv` – Dataset used for training and analysis.
- `README.md` – Project overview and documentation.

---

## 🚀 How to Run

1. Clone the repo:
  
2. Open the notebook (`new.ipynb`) in Jupyter or Google Colab.

3. Run cells in sequence to reproduce the analysis and results.

---

## 📬 Contact

For questions or collaboration opportunities:  
📧 Email: Hkenneth350@gmail.com

---

## 📌 License

This project is licensed for educational use only.


