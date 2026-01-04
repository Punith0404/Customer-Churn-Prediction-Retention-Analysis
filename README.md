# Customer Churn Prediction & Retention Analysis

An end-to-end machine learning project focused on identifying customers at risk of churn and deriving actionable retention insights using historical customer and service usage data.

---

## Technical Overview
- Data preprocessing and feature engineering performed using **Pandas** and **NumPy**
- Categorical encoding and numerical standardization applied where appropriate
- Models built and evaluated using **Scikit-learn**
- Model performance evaluated using **Recall, Precision, and ROC-AUC**

---

## Key Churn Insights
- **Tenure is the strongest churn indicator**. Customers in the early months of their lifecycle are significantly more likely to churn, highlighting the importance of early engagement and onboarding.

- **Higher monthly charges are associated with increased churn**, suggesting price sensitivity and the need for better value communication.

- **Service adoption strongly impacts retention**. Customers without services such as Online Security, Tech Support, Online Backup, and Device Protection show substantially higher churn rates.

- **Fiber optic internet users exhibit higher churn** compared to DSL users, indicating possible service expectation gaps or competitive pressure.

- **Senior citizens represent a higher churn-risk segment**, emphasizing the need for tailored support and simplified plans.

- **Customers without partners or dependents churn more frequently**, likely due to lower switching costs and weaker customer lock-in.

---

## Modeling Summary
- A **Logistic Regression model** was trained as the baseline due to its interpretability and effectiveness for binary classification.
- A **Random Forest model** was trained as a comparison to capture non-linear relationships.
- Both models achieved strong discriminatory performance:
  - **ROC-AUC ≈ 0.85**
- Logistic Regression showed slightly higher churn recall, while Random Forest improved precision.

---

## Business Impact
The model enables identification of customers at higher risk of churn, allowing businesses to design proactive retention strategies focused on high-risk segments such as new customers, high-paying users, and customers without value-added services.
