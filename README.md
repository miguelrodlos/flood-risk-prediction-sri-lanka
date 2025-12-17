# Flood Risk Prediction in Sri Lanka
**Statistical Modeling with Linear Regression and Generalized Linear Models**

## Overview
This repository contains a complete statistical analysis aimed at **predicting flood risk in Sri Lanka** using regression-based methods. The project applies **Linear Regression** to model a continuous flood risk score and **Generalized Linear Models (logistic regression)** to analyze flood occurrence as a binary outcome.

The analysis follows a rigorous, reproducible workflow implemented in **R Markdown (.Rmd)**, combining data exploration, modeling, diagnostics, benchmarking, and uncertainty quantification.

---

## Objectives
- Model flood risk using environmental, geographical, and socio-demographic predictors
- Compare simple, multivariate, and benchmark regression models
- Interpret model coefficients and effects in a meaningful way
- Evaluate model assumptions and predictive performance
- Extend the analysis to binary flood occurrence using logistic regression

---

## Dataset
- **Source:** Kaggle – *Sri Lanka Flood Risk and Inundation Dataset*
- **Observations:** ~25,000 geo-referenced locations
- **Predictors include:**
  - Environmental: rainfall (7-day and monthly), vegetation indices (NDVI, NDWI)
  - Geographical: elevation, distance to rivers, drainage index
  - Socio-demographic and infrastructure indicators
- **Response variables:**
  - `flood_risk_score` (continuous, 0–100)
  - `flood_occurrence_current_event` (binary)

The dataset is synthetic but designed to reflect realistic flood risk patterns.

---

## Methodology
### 1. Exploratory Data Analysis
- Variable inspection and summary statistics
- Distributional analysis and correlation structure
- Identification of relevant predictors

### 2. Linear Regression
- Simple and multiple linear regression models
- Model comparison using RMSE, MAE, and R²
- Benchmark model based on the training-set mean

### 3. Model Diagnostics
- Residual analysis and influence diagnostics
- Assessment of normality and homoscedasticity
- Detection of high-leverage observations

### 4. Uncertainty Quantification
- 95% prediction intervals
- Empirical coverage evaluation

### 5. Generalized Linear Models
- Logistic regression for flood occurrence
- Interpretation via odds ratios and marginal effects
- Model comparison using deviance and AIC

---

## Reproducible Workflow
The entire analysis is implemented in an **R Markdown (`.Rmd`) file**, which:
- Combines code, output, and interpretation
- Produces the final report directly in PDF/HTML format
- Ensures full reproducibility of results

## Repository Structure
├── README.md                 
├── HW1_s100568756.rmd                             
├── HW1_s100568756.html                           
└── sri_lanka_flood_risk_dataset_25000.csv    
