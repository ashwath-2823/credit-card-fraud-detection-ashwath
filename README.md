# Credit Card Fraud Detection - Ashwath Narayana Reddy K

## Problem Statement

The problem statement for this project is to predict fraudulent credit card transactions using machine learning.

In this project, we analyze customer-level credit card transaction data collected during a research collaboration. The goal is to build predictive models that can accurately detect fraudulent transactions, which are rare and difficult to identify in real-time.

The dataset is taken from the [Kaggle Website](https://www.kaggle.com/mlg-ulb/creditcardfraud).

---

## Business Problem Overview

For many banks and financial institutions, retaining high-value customers and ensuring transaction security is a top priority. Fraudulent transactions not only lead to financial losses but also damage customer trust and reputation.

According to a [Nilson Report](https://nilsonreport.com/upload/content_promo/The_Nilson_Report_10-2022.pdf), credit card fraud is expected to cost the global economy over $30 billion in losses annually.

Hence, detecting fraud using machine learning is not just a trend, but a necessity in the banking and fintech industries.

---

## Understanding and Defining Fraud

Credit card fraud includes any unauthorized or illegal use of a credit card for financial gain. Some common types of fraud include:

- Stolen or lost credit cards
- Counterfeit card creation
- Telemarketing fraud
- Card data manipulation or skimming

---

## Data Dictionary

The dataset includes transactions made by European cardholders over two days in September 2013. It contains 284,807 transactions with 492 labeled as fraud.

- **Time**: Seconds elapsed between transactions
- **V1 - V28**: PCA-transformed features
- **Amount**: Transaction amount
- **Class**: Target variable (0 = non-fraud, 1 = fraud)

---

## 📌 Project Pipeline

The project pipeline is summarized in the following steps:

- **📥 Data Understanding**: Load and explore dataset, understand class imbalance and transaction patterns.
- **📊 Exploratory Data Analysis (EDA)**: Perform univariate and bivariate analysis to visualize distributions and outliers.
- **🔀 Train/Test Split**: Split data into training and test sets to evaluate generalization.
- **🧪 Model Building**: Use Logistic Regression and Random Forest classifiers to train predictive models.
- **📈 Model Evaluation**: Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC curve.

---

## Results

- **Best Model**: Random Forest Classifier
- **Accuracy**: ~95%
- **Evaluation Metrics**: High recall and precision with strong AUC-ROC

---

## Author -

**Ashwath Narayana Reddy K**  
- GitHub: [@ashwath-2823](https://github.com/ashwath-2823)  
- Portfolio: [ashwathnreddyk.in](https://ashwathnreddyk.in)  
- Email: [ashwathnreddyk@gmail.com](mailto:ashwathnreddyk@gmail.com)


