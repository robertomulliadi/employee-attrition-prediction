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

## 💡 SHAP Insights
- **Overtime** is the strongest predictor of attrition.
- **Low stock option level, income, and satisfaction** increase risk.
- SHAP provided **transparent, feature-level explanations** for both overall trends and individual cases.
