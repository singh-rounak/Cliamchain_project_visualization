# Insurance Fraud Detection using Explainable AI (SHAP)

Machine learning project that detects fraudulent insurance claims using predictive models and interprets model decisions using SHAP (SHapley Additive Explanations) to improve transparency in fraud investigations.

This project demonstrates how explainable AI can support insurance companies and fraud analysts in identifying suspicious claims while understanding the factors influencing model predictions.

## Project Overview

Insurance fraud causes billions of dollars in losses every year. Traditional rule-based systems struggle to detect complex fraud patterns hidden in large datasets.

This project builds a machine learning pipeline for fraud detection on insurance claims data and uses SHAP values to interpret the model predictions.

The goal is not only to detect fraudulent claims but also to explain why a claim was classified as fraudulent, enabling trust and transparency for fraud investigators.

The dataset contains 15,530 insurance claims with 31 features including:

* Customer Information

* Age

* Gender

* Marital status

* Policy Details

* Policy type

* Vehicle category

* Number of supplements

* Agent type

* Claim Information

* Incident report timing

* Witness presence

* Police report status

* Days between incident and claim

Out of all claims:

924 claims are labeled as fraudulent

## Explainable AI with SHAP

To improve transparency in model predictions, this project uses SHAP values.

SHAP helps answer critical questions:

* Why was a claim predicted as fraud?

* Which features influence the prediction most?

* How does each feature impact the model output?

This is important in industries like insurance where model explainability is required for compliance and investigation processes.

## Machine Learning Workflow

The project follows a standard machine learning pipeline:

1. Data preprocessing

2. Exploratory data analysis (EDA)

3. Feature engineering

4. Model training

5. Model evaluation

6. Explainability analysis using SHAP

7. Visualization of fraud risk patterns


# Key Insights from Data Analysis

Exploratory analysis of fraudulent claims revealed several patterns:

* 88.6% of fraud cases involved male claimants
* 67.2% of fraud cases involved married individuals
* Average fraudster age ≈ 38 years
* 98% of fraudulent claims had no police report
* 99% of fraudulent claims had no witness

These insights help insurers identify high-risk claim patterns.

# Visualizations
1. Data Exploration
   ![image alt]()

2. Model Performance Comparison
  ![image alt]()

3. SHAP Feature Importance
  ![image alt]()

   
4. SHAP Individual Prediction Explanation
   ![image alt]()
