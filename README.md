# loan_prediction
Classification problem about loan approval
# Behind the Rejection: Machine Learning on HMDA Mortgage Denial Data

## Project Overview

Why do mortgage applications get denied, and what factors are most important in predicting these outcomes?

This project applies machine learning techniques to **2024 Texas home-purchase mortgage application data** reported under the Home Mortgage Disclosure Act (HMDA). The study aims to predict mortgage denial outcomes, identify influential predictive factors, compare different machine learning algorithms, and evaluate fairness across demographic groups.

The project explores both traditional statistical learning methods and advanced tree-based ensemble models to understand their predictive performance and potential limitations.

### Key Objectives

- **Predict mortgage denial:** Develop machine learning models to classify mortgage applications as denied or not denied.
- **Identify influential factors:** Examine the applicant, loan, property, and application-process characteristics that contribute to model predictions.
- **Compare models:** Evaluate Logistic Regression, Ridge, Lasso, Elastic Net, Random Forest, XGBoost, CatBoost, and LightGBM.
- **Evaluate fairness:** Investigate differences in model outcomes across racial, ethnic, and sex groups using fairness metrics.
- **Promote responsible AI:** Discuss the limitations of predictive models and the importance of fairness, transparency, and responsible use in lending.

### Dataset

The analysis uses 2024 HMDA mortgage application data for Texas, with a focus on home-purchase loans. The dataset includes applicant demographics, financial characteristics, loan attributes, property information, geographic context, and application-process variables.

### Key Areas of Analysis

- Exploratory data analysis and data quality assessment
- Missing-value handling and feature preprocessing
- Class imbalance management
- Machine learning model development and hyperparameter tuning
- Predictive performance evaluation using ROC-AUC, PR-AUC, recall, and F1-score
- Feature importance and model interpretation
- Fairness assessment using disparate impact, true positive rate, and false positive rate

### Key Findings

Tree-based ensemble models achieved stronger predictive performance than the linear-model baselines in the reported evaluation. Debt-to-income ratio was among the most influential predictive features. The fairness analysis also identified potential disparities across racial groups, highlighting the importance of evaluating fairness alongside predictive accuracy.



### Technologies

Python · Pandas · NumPy · Scikit-learn · XGBoost · CatBoost · LightGBM · Matplotlib · Seaborn

### Project Scope
This project demonstrates how machine learning can be used to analyze mortgage denial outcomes while highlighting the challenges of model interpretability, class imbalance, and algorithmic fairness in a high-impact financial setting.

This project demonstrates how machine learning can be used to analyze mortgage denial outcomes while highlighting the challenges of model interpretability, class imbalance, and algorithmic fairness in a high-impact financial setting.
