# 🧠 Breast Cancer Classification with Logistic Regression

This project applies **Logistic Regression** to the **Breast Cancer Wisconsin dataset** (from Kaggle) to classify tumors as **Malignant (1)** or **Benign (0)**.

---

## 📌 Objective

To build a binary classifier using Logistic Regression, evaluate it with common classification metrics, and visualize its performance using confusion matrix and ROC-AUC curve.

---

## 📁 Dataset

- Source: [Kaggle - Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Features: 30 real-valued numeric features (e.g., radius_mean, area_mean, etc.)
- Target:
  - `M` = Malignant (1)
  - `B` = Benign (0)

---

## ✅ What’s Included

- Data cleaning & preprocessing (drop ID columns, map labels)
- Train-test split (80-20)
- Feature standardization using `StandardScaler`
- Logistic Regression model training
- Model evaluation:
  - Confusion matrix
  - Accuracy, Precision, Recall, F1-score
  - ROC curve & AUC score
- Threshold tuning
- Sigmoid function explanation and plot

---

## 🛠 Tools & Libraries
- Pandas
- NumPy
- Scikit-learn
- Seaborn & Matplotlib

---

## 📊 Results

| Metric         | Value (approx.) |
|----------------|-----------------|
| Accuracy       | 97%–99%         |
| ROC AUC Score  | ~0.99           |
| Precision/Recall | Excellent balance |

---

## 📈 Visualizations

- 🔷 Confusion Matrix  
- 🧮 ROC Curve  
- 🔁 Sigmoid Function  
- ⚙️ Custom Threshold Impact

---


## 🧠 Key Concepts

- Logistic Regression
- Sigmoid Function
- ROC-AUC, Precision, Recall, F1
- Classification Thresholding
- Feature Scaling
