# 🏦 Credit Risk Prediction Using Logistic Regression

This project aims to predict whether a loan applicant is likely to **default** on a loan using a **classification model** (Logistic Regression). The dataset was taken from Kaggle's **Loan Prediction** dataset and processed using Python and scikit-learn.

---

## 📌 Project Objective

> To build a predictive model that classifies whether a loan should be approved (`Loan_Status` = Y/N) based on features like applicant income, loan amount, education, employment, etc.

---

## 📁 Dataset

- File used: `train.csv`
- Size: ~600 records with multiple features

---

## 🧼 Data Preprocessing

- Handled missing values using **mode** (for categorical) and **median** (for numerical)
- Combined applicant and co-applicant incomes into `TotalIncome`
- Encoded categorical features using **LabelEncoder**

---

## 📊 Exploratory Data Analysis (EDA)

Visualized key features using Seaborn and Matplotlib:
- Distribution of loan amounts
- Relationship between education and loan status
- Boxplot of total income vs loan status

---

## 🤖 Model Training

- **Model Used**: Logistic Regression (scikit-learn)
- **Train-Test Split**: 80% training, 20% testing
- **Evaluation Metrics**:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)

---

## 📈 Results

| Metric     | Value     |
|------------|-----------|
| Accuracy   | ~82%      |
| Precision  | ~0.84     |
| Recall     | ~0.92     |
| F1-Score   | ~0.88     |

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---



