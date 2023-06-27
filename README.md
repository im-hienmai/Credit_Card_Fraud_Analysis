# Credit Card Fraud Analysis

This project aims to develop a predictive model for detecting credit card fraud. It utilizes a dataset containing credit card transactions made by European cardholders in September 2013. By analyzing the transaction features and applying machine learning techniques, the project aims to accurately identify fraudulent transactions and help credit card companies mitigate financial losses.

## Project Overview

The project follows a step-by-step process, including data exploration, preprocessing, data analysis, model building, and evaluation. Here's a brief overview of each step:

1. Data Exploration:
   - The dataset consists of 31 columns, including transaction features obtained through PCA transformation, 'Time' (elapsed time since the first transaction), 'Amount' (transaction amount), and 'Class' (fraudulent or not).
   - The dataset is highly unbalanced, with only a small percentage of transactions labeled as fraud.

2. Data Preprocessing:
   - The dataset is split into feature variables (X) and the target variable (y).
   - The 'Amount' feature is scaled using standardization, while the other features are already scaled through PCA transformation.

3. Data Analysis:
   - Visualizations are created to analyze the distribution of fraudulent transactions compared to normal transactions based on transaction amount and time.
   - Histograms and density plots are used to compare the distributions of the principal components (V1-V28) for fraudulent and normal transactions.

4. Model Building and Evaluation:
   - Logistic Regression, Decision Tree, and Random Forest models are trained and evaluated using the train-test split approach.
   - Model performance metrics such as accuracy, F1-score, and ROC curve are calculated and displayed for each model.
   - Confusion matrices are used to analyze the model's ability to correctly classify fraudulent and normal transactions.

## Results

The project yields the following results:

<img width="267" alt="fraud" src="https://github.com/im-hienmai/Credit_Card_Fraud_Analysis/assets/131462914/4f72de5d-603c-4cc7-9308-10575a851fcb">


Based on the evaluation metrics, the Random Forest model performs the best among the three models, achieving the highest accuracy, F1-score, and ROC AUC. However, it's important to note that these results may vary depending on the specific dataset and modeling choices.
