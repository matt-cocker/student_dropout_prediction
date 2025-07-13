# Predicting Student Dropout with Machine Learning Models

This project applies supervised machine learning techniques to predict student dropout risk based on demographic and behavioural features. The goal is to support early intervention strategies by identifying at-risk students and enabling better resource planning.

## Project Overview

Using a combination of cleaned enrolment data and feature engineering (e.g., age, attendance patterns), this analysis evaluates the predictive performance of several models including XGBoost and neural networks. Feature importance methods (SHAP) are used to assess model interpretability and support practical decision-making. In further iterations of this project, SHAP would be used to identify the most relevant input data for the models

## Business Context

Educational institutions face growing pressure to improve student outcomes while operating under resource constraints. A data-driven dropout prediction model offers a way to identify students most in need of support, potentially improving retention and academic performance.

## Objectives

- Preprocess and engineer features from student enrolment datasets
- Train and compare machine learning models for dropout prediction
- Interpret model outputs using explainability tools
- Recommend strategies for early intervention

## Tools and Libraries

- Python, pandas, NumPy, seaborn, matplotlib
- XGBoost, TensorFlow, Keras, scikit-learn
- SHAP

## Results Summary

- Trained multiple models, with XGBoost delivering the best accuracy and balance of interpretability
- SHAP analysis revealed key dropout predictors including engagement, course timing, and student profile features

## Limitations

- Model performance depends on data quality and availability across education stages
- Further validation required to generalise findings beyond the sample population

## Next Steps

- Identify most relevant predictors of dropout to improve input data
- Deploy predictive insights in student support workflows
- Conduct pilot testing with support staff and course coordinators

## Data Note

The dataset used in this notebook was provided in a controlled academic setting and is loaded directly from a hosted source. Sensitive fields were anonymised as part of preprocessing.
