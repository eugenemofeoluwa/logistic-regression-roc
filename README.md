# Predicting Diabetes: Logistic Regression & ROC Analysis

A reproducible R Markdown workflow for binary outcome modelling in clinical data.

**📄 [View the rendered report](report.html)**

## Overview
This project demonstrates how to build, evaluate, and interpret a logistic regression model in R. Using the Pima Indians Diabetes dataset, we model the probability of diabetes based on clinical predictors, evaluate the model's discriminatory power using ROC curves, and produce publication-ready tables and figures.

## What this project demonstrates
- Data cleaning and complete-case handling
- Fitting a binary logistic regression model (`glm`)
- Calculating and interpreting Odds Ratios with 95% CIs
- Generating a publication-ready regression table (`gtsummary`)
- Evaluating model performance using ROC curves and AUC (`pROC`)
- Automated inline text reporting (no manual copy-pasting of statistics)

## Key Findings
- Plasma glucose is the strongest predictor of diabetes (OR ≈ 1.04 per mg/dL).
- The model achieves an AUC of **0.82**, indicating excellent discrimination.

## How to reproduce
1. Clone this repository.
2. Open `logistic-roc.Rproj` in RStudio.
3. Open `report.Rmd` and click **Knit**.

## Author
**Eugene Mofeoluwa**
*Available for freelance statistical analysis projects.*