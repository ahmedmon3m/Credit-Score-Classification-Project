# 🏦 Credit Score Classification Project

This project uses machine learning to classify individuals' credit scores as **Good**, **Standard**, or **Poor** based on various financial indicators. The goal is to predict risk categories to aid in credit risk assessment.

---

## 📊 Dataset

- **Source**: [Kaggle - Credit Score Classification](https://www.kaggle.com/datasets/parisrohan/credit-score-classification)
- **Rows**: ~1250+
- **Columns**: 18 (e.g., Annual Income, Num Bank Accounts, Credit History Age)

---

## 🚀 Project Workflow

### 🔹 1. Data Understanding
- Loaded dataset and explored structure
- Handled nulls, outliers, and data types

### 🔹 2. Data Preprocessing
- Filled missing values
- Encoded categorical features
- Scaled numeric columns using `StandardScaler`
- Converted target to multi-class format

### 🔹 3. Model Building
- Trained multiple classifiers:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Chose best model based on accuracy

### 🔹 4. Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📈 Results

| Model               | Accuracy |
|---------------------|----------|
| XGBoost             | 97%      |

✅ **Best Model**: XGBoost

---

## 🖥️ Streamlit App

We built an interactive web interface using Streamlit to predict credit score classes based on user input.

### ▶️ Run Locally

```bash
streamlit run app.py
