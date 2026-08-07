# Predicting Adverse Birth Outcomes in Missouri Using County-Level Maternal Health Indicators, Social Determinants of Health, and Machine Learning

## Overview

Preterm birth is one of the leading causes of infant morbidity and mortality in the United States. This project investigates whether publicly available county-level maternal health indicators, social determinants of health, and community health measures can be used to predict preterm birth across Missouri. Statistical and machine learning models were developed to support county-level maternal health surveillance and public health planning.

## Objectives
- Predict county-level preterm birth rates.
- Identify counties at elevated risk for preterm birth.
- Compare statistical and machine learning models.
- Identify the most influential county-level predictors.
- Demonstrate the value of publicly available data for maternal health surveillance.


## Data Sources

- Missouri Birth MICA
- American Community Survey (ACS)
- County Health Rankings & Roadmaps (CHR&R)

## Outcomes

- Preterm birth
- High-risk Preterm birth

## Methods
The datasets were cleaned, integrated, and analyzed using Python. Recursive Feature Elimination (RFE) was used for feature selection. Multiple regression and classification models were evaluated using grouped five-fold cross-validation.

## Results
## Best Regression Model
Linear Regression
RMSE: 2.34
MAE: 1.78
R²: 0.085
## Best Classification Model
Logistic Regression
ROC-AUC: 0.673
Recall: 0.562
F1-score: 0.431
## Most Important Predictors
Medicaid-covered births
Low educational attainment
Maternal smoking
Early prenatal care
Adult obesity
Physical inactivity
Median household income

## Author

Lafouet Kevine Yemelong

Master of Science in Health Data Science

Saint Louis University

