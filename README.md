# 📊 Employee Attrition Prediction

This project explores machine learning techniques to predict employee attrition using structured HR data. It focuses on building interpretable models that balance performance with practical business insight.

---

## 🛠️ Tools Used
- Python, Jupyter, scikit-learn, XGBoost, SHAP
- R (for exploratory data analysis)

---

## 🔍 Project Steps
1. **EDA (in R):** Visualized key relationships (e.g., job satisfaction, overtime)
2. **Baseline Modeling:** Trained logistic regression, decision tree, random forest, and XGBoost
3. **Hyperparameter Tuning:** Improved random forest and XGBoost using GridSearchCV
4. **Model Evaluation:** Focused on recall, precision, F1-score, and ROC-AUC for attrition class
5. **Model Interpretation:** Used SHAP to explain predictions globally and at the individual level

---

## ✅ Best Model Performance
- **Model:** Random Forest (tuned)
- **Recall (leavers):** 0.49
- **Precision (leavers):** 0.43
- **F1-score (leavers):** 0.46
- **ROC-AUC:** 0.77

These results indicate a good balance between identifying employees likely to leave and minimizing false positives, particularly given the class imbalance (~16% attrition rate).

---

## 💡 SHAP Insights
- **Overtime** is the strongest predictor of attrition.
- **Low stock option level, income, and satisfaction** increase risk.
- SHAP provided **transparent, feature-level explanations** for both overall trends and individual cases.

---

## ⚠️ Why Stacking Was Not Used
Stacking models were explored but ultimately excluded due to convergence and stability issues during training, with minimal expected performance gain.
