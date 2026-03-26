# Mortgage Risk Modeling

## Overview
This project develops predictive models for two important mortgage outcomes: **default** and **prepayment**. The goal is to evaluate whether borrower, loan, and property characteristics can help explain and predict these outcomes using historical mortgage performance data.

The project is structured as a dual-model classification study:
- a **default model** to identify loans at higher risk of serious delinquency
- a **prepayment model** to identify loans more likely to be voluntarily paid off early

## Business Problem
Mortgage lenders and investors need to understand how loans may perform over time. Two key risks are:

- **Default risk**, which may lead to financial loss and increased servicing costs
- **Prepayment risk**, which changes expected cash flows and reduces future interest income

This project applies data science methods to study both risks in a structured and interpretable way.

## Project Objectives
- Define mortgage default and prepayment targets from historical loan data
- Prepare a clean modeling dataset
- Explore relationships between loan characteristics and target outcomes
- Engineer useful predictive features
- Build separate models for default and prepayment
- Evaluate model behavior in a mortgage risk context

## Results
The project analyzed approximately **2.07 million monthly loan records** and **104,924 unique loans** across **five states**. The observed **default rate** was approximately **2.35%**, while the observed **prepayment rate** was approximately **50.9%**.

## Final Models

**Default model: Gradient Boosting**
- AUC-ROC: 0.759
- Recall: 0.702
- F1 score: 0.098

**Prepayment model: Gradient Boosting**
- AUC-ROC: 0.703
- Accuracy: 0.627
- F1 score: 0.696

## Project Structure
```text
Mortgage_Risk_Modeling/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── mrm_02_data_wrangling.ipynb
│   ├── mrm_03_exploratory_data_analysis.ipynb
│   ├── mrm_04_feature_engineering.ipynb
│   ├── mrm_05_default_risk_modeling.ipynb
│   └── mrm_06_prepayment_risk_modeling.ipynb
│
├── reports/
│   ├── mrm_01_problem_identification.md
│   └── mrm_07_project_report.md
│
├── requirements.txt
└── README.md