\# End-to-End ML Classification Pipeline for Telco Customer Churn



This project implements an end-to-end Machine Learning pipeline to predict customer churn in a telecommunications company.



\## 📌 Features

\- \*\*Exploratory Data Analysis (EDA)\*\* using Seaborn \& Matplotlib.

\- \*\*Data Preprocessing \& Cleaning\*\*: Handled missing values, standardized numerical features, encoded categorical values with `OneHotEncoder`.

\- \*\*Pipeline Architecture\*\*: Built modular workflows with `scikit-learn` Pipelines and `ColumnTransformer` to prevent data leakage.

\- \*\*Model Comparison\*\*: Trained Logistic Regression, Decision Tree, and Random Forest models.

\- \*\*Hyperparameter Tuning\*\*: Fine-tuned Random Forest via `GridSearchCV` (5-fold Cross-Validation).



\## 🚀 Results

\- \*\*Baseline Logistic Regression ROC-AUC\*\*: \~0.84

\- \*\*Tuned Random Forest ROC-AUC\*\*: \~0.85

\- Key metrics evaluated: Precision, Recall, F1-Score, and ROC-AUC.



\## 🛠️ How to Run

1\. Clone the repository:

&#x20;  ```bash

&#x20;  git clone \[https://github.com/askhanlqve/ml-classification-pipeline.git](https://github.com/askhanlqve/ml-classification-pipeline.git)

&#x20;  cd ml-classification-pipeline

