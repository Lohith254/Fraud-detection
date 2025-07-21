
# 📊 Fraud Detection using Machine Learning

This project focuses on detecting fraudulent transactions in financial systems using a supervised machine learning approach. The dataset contains over 6 million transaction records, including features such as transaction type, amount, account balances, and fraud labels.

---

## 📁 Project Structure

```
├── fraud_detection.ipynb       # Jupyter notebook with full analysis
├── README.md                   # Project overview and setup
├── data/                       # (Optional) Folder for local CSV if not using URL
```

---

## 🚀 Problem Statement

The objective is to develop a predictive model to detect fraudulent transactions and extract actionable insights for improving fraud prevention in real-time systems.

---

## 🧰 Tools & Technologies

- Python 🐍
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (Random Forest, Evaluation)
- Google Colab / Jupyter Notebook

---

## 📌 Key Steps

1. **Data Loading and Exploration**
2. **Data Cleaning & Feature Engineering**
3. **Handling Class Imbalance**
4. **Model Building using Random Forest**
5. **Model Evaluation (Precision, Recall, F1, AUC)**
6. **Feature Importance Analysis**
7. **Business Recommendations**

---

## 📈 Results

- **ROC AUC Score:** 0.996
- **Precision (Fraud):** 0.98
- **Recall (Fraud):** 0.79
- Model correctly identifies the majority of fraudulent cases with very low false positives.

---

## 📌 Insights

- Features like `diffOrig`, `oldbalanceOrg`, and `amount` are key indicators of fraud.
- Transfer and cash-out transactions with zero balance behaviors are common fraud patterns.

---

## 🛡️ Business Recommendations

- Implement real-time risk scoring for high-value transfers.
- Flag accounts with zero-to-zero transfers or large `diffOrig`.
- Add OTP/review checks for high-risk transaction types.

---

## 📎 Dataset

📥 [Download from Google Drive](https://drive.google.com/uc?id=1VQ-HAm0oHbv0GmDKP2iqqFNc5aI91OLn&export=download)

---

## 👤 Author

**Lohith R**  
_Internship Assignment | INSAID_
