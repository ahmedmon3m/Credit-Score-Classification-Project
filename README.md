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
- Data loaded and cleaned from CSV
- Columns reviewed for nulls, types, and outliers

### 🔹 2. Data Preprocessing
- Handled missing values
- Label Encoding for categorical features
- Feature scaling using `StandardScaler`
- Converted target variable into multi-class format

### 🔹 3. Model Building
- Used classification models:
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost
- Performed train/test split and evaluated accuracy

### 🔹 4. Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1)

---

## 📈 Results

| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | 88%      |
| Random Forest       | 91%      |
| XGBoost             | 92%      |

**Best Model**: ✅ XGBoost with 92% accuracy

---

## 🛠️ Requirements

Install dependencies via:

```bash
pip install -r requirements.txt
