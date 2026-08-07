# Predicting Adverse Birth Outcomes in Missouri Using County-Level Maternal Health Indicators, Social Determinants of Health, and Machine Learning

## Overview

This capstone project investigates whether publicly available county-level maternal health indicators, social determinants of health, and community health measures can predict adverse birth outcomes in Missouri, with a primary focus on **preterm birth**.

By integrating multiple statewide datasets and applying statistical and machine learning techniques, this project demonstrates how data science can support maternal health surveillance and inform evidence-based public health decision-making.

---

## Project Objectives

- Predict county-level preterm birth rates across Missouri.
- Identify counties at elevated risk for preterm birth.
- Compare traditional statistical models with machine learning approaches.
- Identify the most important county-level predictors of preterm birth.
- Demonstrate the use of publicly available data for population health surveillance.

---

## Data Sources

The analysis integrates three publicly available datasets:

- **Missouri Birth MICA** – County-level maternal and birth outcome data
- **American Community Survey (ACS)** – Socioeconomic and demographic indicators
- **County Health Rankings & Roadmaps (CHR&R)** – Community health and healthcare access measures

---

## Methods

The project workflow included:

- Data cleaning and integration
- Exploratory data analysis (EDA)
- Feature selection using Recursive Feature Elimination (RFE)
- Regression modeling
- Classification modeling
- Model comparison using grouped 5-fold cross-validation
- Geographic visualization
- Feature importance analysis

---

## Key Results

### Best Regression Model
**Linear Regression**

- RMSE: **2.34**
- MAE: **1.78**
- R²: **0.085**

### Best Classification Model
**Logistic Regression**

- ROC-AUC: **0.673**
- Recall: **0.562**
- F1-score: **0.431**

### Most Important Predictors

- Medicaid-covered births
- Low educational attainment
- Maternal smoking
- Early prenatal care
- Adult obesity
- Physical inactivity
- Median household income
- Poverty
- Uninsured population

---

## Repository Structure

```text
.
├── Missouri Birth MICA Raw/
├── Missouri County Boundaries/
├── Processed Data/
├── Notebook/
├── Poster/
├── Report/
├── README.md
└── requirements.txt
```

---

## Technologies

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- XGBoost
- GeoPandas
- Matplotlib

---

## Public Health Impact

This project demonstrates how publicly available maternal health and community-level data can be integrated to support county-level surveillance of preterm birth. While the models are intended for population-level planning rather than individual clinical decision-making, they provide a practical framework for identifying communities that may benefit from targeted maternal health interventions and more informed resource allocation.

---

## Author

**Lafouet Kevine Yemelong**

Master of Science in Health Data Science  
Saint Louis University

Saint Louis University

