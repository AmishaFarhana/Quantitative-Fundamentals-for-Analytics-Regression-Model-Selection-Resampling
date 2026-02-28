# Quantitative Fundamentals for Analytics: Regression, Model Selection & Resampling

> Implemented statistical learning foundations including linear regression, logistic regression, model selection, cross-validation, and resampling to build and evaluate predictive models.

**Author:** Amisha Farhana Shaik  
**Project Type:** Statistical Modeling | Regression | Model Selection | Quantitative Foundations  

---

## Project Overview

This repository consolidates quantitative coursework building the statistical foundation required for modern analytics and machine learning.

The work covers:

- Linear regression (simple & multiple)
- Hypothesis testing (t-tests, F-tests)
- Model fit metrics (R², Adjusted R²)
- Residual analysis
- Multicollinearity diagnostics
- Interaction & polynomial effects
- Train/test validation
- Cross-validation
- Model selection (Forward selection, BIC, AIC)
- Logistic regression
- Classification metrics
- ROC curves & AUC
- Bootstrapping & resampling

These assignments move from statistical theory to applied modeling in Python using `statsmodels`, `sklearn`, and `ISLP`.

---

# 1️⃣ Linear Regression Foundations

Using the Advertising dataset :contentReference[oaicite:7]{index=7} :contentReference[oaicite:8]{index=8}:

- Estimated simple regression (Sales ~ TV)
- Computed RSS and RSE
- Derived t-statistics and p-values
- Built confidence intervals
- Interpreted R² (≈ 0.61 for simple model)
- Extended to multiple regression (TV + Radio + Newspaper)
- Observed R² ≈ 0.897 for additive model

### Concepts Demonstrated

- Least Squares estimation
- Interpretation of coefficients
- ANOVA and F-statistic
- Variance decomposition (TSS, RSS)
- Statistical significance testing

---

# 2️⃣ Collinearity & Model Diagnostics

In extended models :contentReference[oaicite:9]{index=9}:

- Generated correlation matrix heatmaps
- Computed Variance Inflation Factor (VIF)
- Identified multicollinearity issues
- Evaluated condition number
- Performed residual vs fitted diagnostics
- Assessed non-linearity and heteroskedasticity
- Investigated leverage points & outliers

### Insights

- Newspaper showed weak predictive power
- Interaction terms improved fit
- Polynomial terms increased R² but introduced numerical instability

---

# 3️⃣ Train-Test Evaluation & MSE

Implemented hold-out validation :contentReference[oaicite:10]{index=10}:

- Split dataset into training & test sets
- Compared models with and without interaction terms
- Computed Train MSE & Test MSE
- Identified overfitting patterns

Result:
Model including interaction term (TV*Radio) achieved lower Test MSE.

---

# 4️⃣ Classification & Logistic Regression

Using Default dataset :contentReference[oaicite:11]{index=11}:

- Compared linear probability model vs logistic regression
- Interpreted log-odds transformation
- Estimated logistic coefficients
- Constructed confusion matrices
- Evaluated True Positive / False Positive rates
- Adjusted classification thresholds
- Generated ROC curves
- Compared AUC values

Key Insight:
Logistic regression provides probability-constrained predictions and better classification behavior.

---

# 5️⃣ Cross-Validation & Resampling

Using Smarket dataset :contentReference[oaicite:12]{index=12}:

- Implemented k-fold cross-validation
- Calculated validation AUC
- Compared forward selection models
- Evaluated deviance in logistic models
- Performed bootstrapping for return estimation
- Measured variance of bootstrap samples

### Demonstrated

- Bias-variance tradeoff
- Model stability assessment
- Estimation variability through resampling
- Selection of predictors based on validation metrics

---

# 6️⃣ Model Selection & Forward Selection

Explored subset selection :contentReference[oaicite:13]{index=13}:

- Evaluated combinatorial growth of predictors (2^p)
- Implemented forward selection
- Compared models via BIC & validation AUC
- Identified multicollinearity in full OLS model
- Reduced model complexity to improve interpretability

### Tradeoff Observed

- Higher R² does not guarantee better generalization
- Penalized metrics (BIC) prefer smaller models
- Validation AUC better reflects test performance

---

# End-to-End Quantitative Workflow

Exploratory Data Analysis  
        ↓  
Fit Baseline Linear Model  
        ↓  
Hypothesis Testing & Diagnostics  
        ↓  
Add Interactions & Non-linear Terms  
        ↓  
Train-Test Validation  
        ↓  
Cross-Validation  
        ↓  
Model Selection (AIC/BIC)  
        ↓  
Classification & Threshold Optimization  
        ↓  
Bootstrapping for Stability  

---

## Technical Skills Demonstrated

- OLS Regression
- Logistic Regression
- Hypothesis Testing
- Confidence Intervals
- F-tests & ANOVA
- R² & Adjusted R²
- Multicollinearity (VIF)
- Residual Diagnostics
- Interaction Modeling
- Polynomial Regression
- Train-Test Splitting
- k-Fold Cross Validation
- Forward Selection
- AIC / BIC
- ROC & AUC
- Confusion Matrices
- Threshold Optimization
- Bootstrapping

---

## Why This Project Is Important

This portfolio demonstrates:

- Strong statistical foundations
- Ability to interpret model diagnostics
- Understanding of overfitting & bias-variance tradeoff
- Experience comparing predictive vs explanatory modeling
- Competence in selecting models systematically
- Knowledge of classification evaluation metrics
- Application of resampling methods for robustness

These quantitative foundations underpin advanced machine learning, forecasting, risk modeling, and optimization projects.

---

## Applications

Statistical Modeling | Predictive Analytics | Model Validation | Machine Learning Foundations | Quantitative Research | Data Science
