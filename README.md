# Diabetic Patient Readmission Prediction
![R](https://img.shields.io/badge/R-4.0%2B-276DC3?style=flat&logo=r&logoColor) 

# Overview

This GitHub project predicts 30-day hospital readmissions for diabetic patients using machine learning models. It leverages UCI Diabetes 130-US Hospitals dataset (1999–2008), fully implemented in R for data exploration, preprocessing, modeling, and evaluation.

# Key Objectives:

- Build predictive models to identify high-risk diabetic patients for readmission.

- Analyze factors like hospital stays, diagnoses, lab procedures, and medications.

- Recommend improved post-discharge care to reduce readmissions.

*Dataset*: ~100,000 patient encounters from 130 US hospitals, with 50+ features including demographics, clinical data, medications, and lab results. 

# Methods

- Data preprocessing (imputation, encoding, balancing with ROSE), exploratory analysis (using dplyr, skimr, psych, ggplot2), model training (caret), and cross-validation for robust evaluation.
  
- Evaluated four machine learning algorithms (Logistic Regression, Decision Tree, Random Forest, and Naïve Bayes) using multiple performance metrics (accuracy, Kappa, ROC curve, confusion matrix).
   
Key Findings
*Best Model*: Random Forest emerged as the optimal model with 73.22% accuracy, demonstrating superior performance on accuracy, Kappa, ROC curve, and confusion matrix.

Most Significant Predictive Factors:

- Number of previous hospital stays

- Total number of diagnoses

- Number of laboratory procedures performed

- Total number of medications prescribed

Additional Contributing Factors:

- Admission type and source

- Primary diagnosis classification

- Insulin dosage levels

- HbA1c test values

*Insights*: Emphasizes the need for continued care after discharge to lower readmission rates, with complex patient profiles (multiple stays, diagnoses, and meds) strongly linked to higher risks.

## packages
install.packages(c("dplyr", "skimr", "stringr", "psych", "ROSE", "ggplot2", "caret"))

## Clone and run
git clone https://github.com/Awnish005123/Diabetic-Patient-Readmission-Prediction.git

MIT License | ⭐ Star if helpful! 🏥✨
