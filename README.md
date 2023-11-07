**Readme File**

**Project Title: Credit Card Fraud Detection**

**Introduction:**

Credit card fraud is a critical concern for financial institutions and cardholders. Detecting fraudulent transactions is essential to prevent unauthorized charges and ensure customer security. This project focuses on building a model for detecting fraudulent credit card transactions.

**Dataset Information:**

- The dataset contains credit card transactions made by European cardholders in September 2013.
- It encompasses transactions over a two-day period, consisting of 492 frauds out of a total of 284,807 transactions. The class distribution is highly imbalanced, with frauds accounting for just 0.172% of all transactions.
- The dataset comprises only numerical input variables derived from Principal Component Analysis (PCA). Features V1 to V28 are the principal components, while 'Time' and 'Amount' are the only non-transformed features.
- 'Time' represents the time elapsed in seconds since the first transaction, and 'Amount' represents the transaction amount.
- The 'Class' feature serves as the response variable, taking a value of 1 for fraud and 0 for non-fraudulent transactions.

**Methods Used:**

- **SMOTE (Synthetic Minority Over-sampling Technique):** Addressed the class imbalance issue by oversampling the minority class, ensuring a balanced dataset for model training.

- **Logistic Regression:** Developed a logistic regression model to predict the likelihood of fraudulent transactions, leveraging interpretable results for fraud detection.

- **Decision Trees:** Utilized decision trees to capture non-linear relationships and decision boundaries in the data, providing an alternative approach for fraud detection.

- **XGBoost (Extreme Gradient Boosting):** Employed XGBoost, a powerful ensemble learning algorithm, to enhance model performance and predictive accuracy.

**Evaluation Metric:**

Given the class imbalance ratio, the primary evaluation metric used is the **Area Under the Precision-Recall Curve (AUPRC)**. This metric is more informative for unbalanced classification tasks compared to confusion matrix accuracy.

**Conclusion:**

This project aims to develop a robust credit card fraud detection system using SMOTE for balancing data and a variety of machine learning techniques. The models can effectively identify fraudulent transactions, thereby enhancing financial security for both customers and credit card companies.

**Dependencies:**

- Python 3.x
- Libraries: Scikit-learn, XGBoost, Pandas, NumPy, SMOTE
- Jupyter Notebook for running code

**Usage:**

1. Ensure you have the required dependencies installed.
2. Open the Jupyter Notebook and run the code cells to build and evaluate the models.

**Author:**

Akshat Agrawal
**Contact Information:**

aa5252@columbia.edu
