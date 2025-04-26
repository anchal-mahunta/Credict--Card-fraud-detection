# Credict--Card-fraud-detection# 💳 Credit Card Fraud Detection Using Logistic Regression

![Credit Card Fraud Detection](https://img.freepik.com/free-photo/top-view-handcuffs-credit-cards-laptop_23-2148564170.jpg)  
*Image Source: [Freepik](https://www.freepik.com/free-photo/top-view-handcuffs-credit-cards-laptop_1241393.htm)*

---

## 📌 Overview

This project demonstrates how **Logistic Regression** can be used to detect fraudulent credit card transactions using real-world data from [Kaggle's Fraud Detection dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection).

The model is trained to distinguish between legitimate and fraudulent transactions and achieves an **AUC-PR score of 89%**, making it a practical baseline for fraud detection.

---

## 📁 Dataset

- Source: [Kaggle - Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection)
- Contains anonymized transaction data with a `is_fraud` binary target label.

---

## ⚙️ Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Imbalanced-learn (for SMOTE)

---

## 🧪 Methodology

1. **Data Loading & Cleaning**
   - Merged training and test data
   - Removed null values (if any)
2. **Exploratory Data Analysis (EDA)**
   - Visualized class imbalance and feature distribution
3. **Preprocessing**
   - Standardized numeric features
   - Handled class imbalance using SMOTE
4. **Modeling**
   - Used Logistic Regression with default and tuned parameters
5. **Evaluation**
   - Evaluated using Precision-Recall curve
   - AUC-PR achieved: **89%**

---

## 📊 Results

| Metric             | Score    |
|--------------------|----------|
| Accuracy           | 96%      |
| Precision-Recall AUC | **0.89** |
| F1 Score           | 0.74     |

> The model effectively detects fraud despite class imbalance, with strong PR-AUC performance.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-logistic.git
   cd credit-card-fraud-logistic
