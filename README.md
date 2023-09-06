**About Dataset**

**Context**

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

**Content**

The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

**Objective:**

Utilize machine learning and data analysis skills to develop a highly accurate credit card fraud detection system, contributing to the security and stability of the financial industry.

**Summary:**
1. **Data Preprocessing and Exploration:** Employed exploratory data analysis techniques to understand the project's dataset, and implemented data preprocessing methods including scaling to ensure accurate model training.

2. **Machine Learning Model Development:** Developed a machine learning pipeline for feature selection and engineering, and selected appropriate classification algorithms. Trained a model using cutting-edge techniques such as Logistic Regression, Descision Tree, Random Forest, achieving a high level of accuracy in identifying fraudulent transactions.
