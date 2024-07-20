# Machine Learning for "Sure Tomorrow" Insurance

## Introduction

Welcome to the "Sure Tomorrow" Insurance project repository! This project aims to harness machine learning techniques to address key business challenges for the fictional insurance company "Sure Tomorrow." The objectives include enhancing marketing efforts, predicting potential insurance claims, estimating claim amounts, and ensuring data privacy through effective anonymization.

## Goals

1. **Client Similarity Analysis**: Identify clients with characteristics similar to specific criteria to improve targeted marketing efforts.

2. **Claim Probability Prediction**: Predict the likelihood of new clients making insurance claims and compare the performance of the machine learning model against a dummy model.

3. **Claim Amount Estimation**: Use linear regression to estimate the potential claim amount for new clients to assess financial risk.

4. **Data Protection**: Implement anonymization techniques to protect client information while maintaining the effectiveness of predictive models.

## Instructions

### Data Loading and Preparation

- Load the dataset from `/datasets/insurance_us.csv`.
- Clean the data to address missing values, outliers, and other anomalies.

### Task Implementation

- Complete each of the four tasks using machine learning techniques as outlined in the project template.
- Answer the associated questions provided in the project template for each task.

### Conclusion

- Summarize your findings and experiences.
- Reflect on the effectiveness of your models and data protection measures.

### Code Utilization

- Use the initial code provided in the project template as a starting point.
- Complete and modify the code as needed to achieve project goals.

## Dataset Description

The dataset contains the following features:

- **Gender**: Gender of the insured individual.
- **Age**: Age of the insured individual.
- **Salary**: Salary of the insured individual.
- **Family Size**: Number of family members of the insured individual.
- **Claim Amount**: Target variable representing the total amount of claims received by the insured individual over the past five years.

## Findings and Results

- **Data Quality**: Identified and removed 153 duplicated rows to avoid redundant results.
- **Feature Impact**: Analysis showed that age positively affects receiving benefits.
- **Model Performance**:
  - The dummy model had low accuracy and F1 score compared to the kNN classification model.
  - kNN classification achieved a high accuracy and F1 score of over 98% on both train and test datasets.
  - RMSE score: 0.36
  - R² score: 0.66
- **Data Masking**: The masked data did not significantly alter the RMSE and R² scores, indicating effective anonymization without compromising model performance.
