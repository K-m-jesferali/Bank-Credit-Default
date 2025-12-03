# 💳 Bank Credit Default Prediction
**Binary classification model to predict customer creditworthiness using financial & behavioral features**

---

## 📘 Overview
This project builds a **machine learning–based risk assessment system** to classify credit card customers into:
- **Good credit history (0)**
- **Bad credit history (1)**

Accurate prediction of customer creditworthiness helps Bank GoodCredit reduce risk, prevent loan defaults, and improve credit policy decisions.

---

## 🎯 Project Goals

### **Task 1 — Exploratory Data Analysis (EDA)**
- Explore customer spending, payments, and behavioral patterns
- Identify major factors influencing credit risk
- Detect correlations and anomalies in customer profiles

### **Task 2 — Credit Default Prediction Model**
- Build and compare multiple ML algorithms
- Models include Random Forest, XGBoost, Neural Networks
- Evaluate using accuracy, precision, recall, F1-score, ROC-AUC

### **Task 3 — Business Recommendations**
- Highlight high-impact features leading to default
- Provide actionable risk mitigation insights for the bank

---

## 🧬 Dataset Summary


The dataset contains customer-level attributes such as:
- Demographics
- Payment history
- Credit utilization
- Behavioral risk indicators

### **Target Variable**
- `Bad_label`
  - `0` — Good credit history
  - `1` — Bad credit history

---

## 🛠️ Tech Stack

| Category | Tools |
|---------|-------|
| **Language** | Python |
| **EDA** | Pandas, NumPy, Matplotlib, Seaborn |
| **Models** | Scikit-Learn, XGBoost, keras |
| **Tuning** | Optuna  |
| **Balancing** | SMOTE (imbalanced-learn) |
| **Evaluation** | ROC-AUC, F1-score, Confusion Matrix |

---

## 📊 Workflow / Pipeline

1. **Data Loading & Cleaning**
2. **EDA — Understanding Customer Financial Behaviour**
3. **Class Balancing (if required)**
4. **Feature Engineering & Scaling**
5. **Model Training**
6. **Hyperparameter Tuning**
7. **Evaluation & Comparison**
8. **Business Insights & Recommendations**

---

## 🚀 How to Run This Project

### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 2️⃣ Open the notebook
```bash
jupyter notebook Bank_Goodcredit.ipynb
```

### 3️⃣ Run the cells sequentially to reproduce the results.

---

## 📁 Project Structure
```
Bank_GoodCredit/
│
├── Bank_Goodcredit.ipynb
├── README.md
├── requirements.txt
│
├── data/
├── models/
├── reports/
```

---

## 💡 Key Insights (Example — Update Based on Results)
- Higher credit utilization correlates strongly with higher default probability.
- Customers with inconsistent payment behavior are more likely to have bad credit history.
- Ensemble models (Random Forest, XGBoost) typically yield the best performance.

---

