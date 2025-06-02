# Credit Card Fraud Detection 🕵️‍♂️💳

This project uses machine learning techniques to detect fraudulent credit card transactions. The goal is to build a classification model that accurately predicts whether a transaction is fraudulent based on a set of features.

---

## 📊 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Description**: The dataset contains transactions made by European cardholders in September 2013. It includes 284,807 transactions, of which 492 are fraudulent.
- **Features**: 30 numerical input features (V1 to V28, Time, Amount), and a binary target variable (`Class`: 1 for fraud, 0 for normal).

---

## 📌 Project Highlights

- Data preprocessing and exploration
- Handling class imbalance using **SMOTE**
- Training models:
  - Logistic Regression
  - Random Forest
  - XGBoost (optional)
- Evaluation using:
  - Confusion Matrix
  - Precision, Recall, F1-score
  - ROC-AUC curve
- Model comparison and selection

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/UserYuv19/creditcard-fraud-detection.git
   cd creditcard-fraud-detection
   ```

2. Run the Jupyter notebook:
   ```bash
   jupyter notebook Final_creditcard_fraud_detection.ipynb
   ```

---

## ✅ Requirements

- Python 3.7+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn

---

## 📈 Sample Output

*Model accuracy: ~99.8% (after balancing classes)*  
*High recall on fraudulent transactions.*

---

## 📚 References

- [Kaggle: Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Scikit-learn Documentation
- imbalanced-learn for SMOTE

---

## 🧑‍💻 Author

- Yuvaraj K (https://github.com/UserYuv19)

---

## ⚠️ Disclaimer

This project is for educational purposes only and should not be used in real financial systems without extensive testing.
