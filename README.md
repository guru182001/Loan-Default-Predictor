# 💰 Loan Default Predictor

## 🔍 Overview
A classification project to predict whether a borrower will default on a loan based on features like income, experience, credit card usage, and more.

Achieved **98.7% accuracy** using **Random Forest**, even with imbalanced data!

---

## 📊 Tools & Techniques
- Python, pandas, scikit-learn
- Models: Logistic Regression, SVC, Random Forest
- StratifiedKFold Cross-Validation
- GridSearchCV for hyperparameter tuning
- SMOTE & Feature Scaling
- Evaluation: Confusion Matrix, Classification Report, ROC AUC

---

## ✅ Results

| Model                 | Accuracy | Best Params                      |
|----------------------|----------|----------------------------------|
| Logistic Regression  | 95.06%   | -                                |
| Support Vector Classifier | 98.04%   | C=10, kernel='rbf'               |
| Random Forest         | 98.78%   | n_estimators=100, max_depth=None |

**Final Model: Random Forest Classifier**

---

## 📈 Classification Report
          precision    recall  f1-score   support

       0       0.99      1.00      0.99       895
       1       0.99      0.91      0.95       105

accuracy                           0.99      1000

