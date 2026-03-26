# Mortgage Risk Modeling
# 01 — Problem Identification

## Overview
Mortgage lending involves multiple forms of risk, including the possibility that a borrower may default or choose to pay off a loan early. Both outcomes are important because they affect portfolio performance, servicing strategy, and financial planning. This project focuses on building a structured analytical workflow to study two key mortgage outcomes: default risk and prepayment risk.

The project is designed as a dual-model classification problem. One model will estimate the likelihood of mortgage default, while the other will estimate the likelihood of voluntary prepayment. Together, these models aim to provide a more complete view of borrower behavior and mortgage portfolio risk.

---

## Business Problem
Mortgage lenders and investors need to understand how loans may perform over time. Two of the most important outcomes are default and prepayment.

Default risk is important because serious delinquency can lead to financial losses, increased servicing costs, and reduced portfolio quality. Prepayment risk is also important because early payoff changes expected cash flows, affects interest income, and can reduce the value of mortgage-related assets.

The core business problem in this project is to identify whether loan-level and borrower-level characteristics can be used to predict these two outcomes. A reliable modeling framework may help support risk monitoring, servicing decisions, and portfolio analysis.

## Objectives
The main objectives of this project are:

1. To define mortgage default and prepayment targets using available loan performance data.
2. To prepare a clean analytical dataset suitable for predictive modeling.
3. To explore relationships between borrower, loan, and property characteristics and the two target outcomes.
4. To engineer useful features that may improve model performance.
5. To build separate predictive models for default and prepayment.
6. To evaluate the effectiveness of each modeling approach using appropriate classification metrics.
7. To interpret the practical meaning of the modeling outputs in a mortgage risk context.