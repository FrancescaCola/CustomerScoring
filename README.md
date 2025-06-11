# Loan Approval Classification Model

### Overview
This project is the result of a collaborative effort within our Data & AI course at Develhope. The objective was to build a **predictive machine learning model** capable of determining whether a loan should be approved or denied, based on user and financial data.

---

### Goal
Develop a classification model that predicts the loan approval outcome (`Approved` or `Denied`) given a set of features, such as:
- Income
- Credit history
- Home ownership
- Loan intent and amount
- Previous loan defaults

---

### Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Logistic Regression, Decision Tree, Random Forest, Neural Network)
- Statsmodels (inference)

---

### Models Tested
- **Logistic Regression**: Baseline model with good interpretability
- **Decision Tree**: Interpretable and flexible (used both pre-pruned and post-pruned)
- **Random Forest**: Ensemble method with high accuracy and generalization
- **Neural Network**: Included for experimentation; dataset complexity was too low to fully benefit from it

---

### Key Metrics
- Accuracy
- Precision (especially for class `Approved`)
- Recall & F1-score
- Confusion Matrix
- ROC Curve and AUC

---

### Insights
- `loan_int_rate`, `loan_amnt`, and `previous_loan_defaults` were among the most influential features.
- Decision Tree post-pruning helped avoid overfitting.
- Random Forest provided the most balanced and robust results.
- Neural Network performed decently but was not optimal due to dataset simplicity.

---

### Future Improvements
- Try SMOTE or other synthetic balancing techniques
- Deploy model via Flask or Streamlit
- Add explainability tools like SHAP

A detailed report of our work is available in the attached document: [**TEAM_PROJECT.pdf**](./TEAM_PROJECT.pdf).

