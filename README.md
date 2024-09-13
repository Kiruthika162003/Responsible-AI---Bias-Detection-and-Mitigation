# Bias Detection and Mitigation in Machine Learning

This repository contains a Jupyter Notebook that demonstrates techniques to detect and mitigate bias in machine learning models. The case study focuses on automating the loan eligibility process using a binary classification model trained on historical data.

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- AIF360
- BlackBoxAuditing
- Fairlearn


## Dataset

The dataset used in this notebook comes from a public challenge organized by Analytics Vidhya. It contains details about customers such as Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others, along with the related loan status.

## Bias Detection and Mitigation Techniques

- **Disparate Impact (DI)**: Measures the ratio of favorable outcomes for unprivileged groups to that of privileged groups.
- **Statistical Parity Difference (SPD)**: Measures the difference in favorable outcomes between unprivileged and privileged groups.
- **Prevalence**: Assesses the proportion of positive cases in different groups.
- **Exploratory Data Analysis (EDA)**: Visualizes data to identify potential sources of bias.

## Model

The notebook uses a Logistic Regression model as a binary classifier to predict loan eligibility based on customer information.

## Results

The notebook provides visualizations and metrics to quantify bias and demonstrates techniques to mitigate bias in the model.

