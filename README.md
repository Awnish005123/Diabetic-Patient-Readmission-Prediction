# Diabetic Patient Readmission Prediction

 
![R](https://img.shields.io/badge/R-4.0%2B-276DC3?style=flat&logo=r&logoColor=white)  

## Project Overview

This GitHub project predicts 30-day hospital readmissions for diabetic patients using a modified version of the Kaggle notebook "Predicting Hospital Readmission of Diabetics" (originally by chongchong33, based on UCI Diabetes 130-US Hospitals dataset from 1999–2008). The notebook has been downloaded, customized, and fully implemented in R for data exploration, preprocessing, modeling, and evaluation.

Key objectives:
- Build predictive models to identify high-risk diabetic patients for readmission.
- Analyze factors like hospital stays, diagnoses, lab procedures, and medications.
- Recommend improved post-discharge care to reduce readmissions.

*Dataset*: ~100,000 patient encounters with features including demographics, clinical data, and medications. Models evaluated: Logistic Regression, Decision Tree, Random Forest, Naïve Bayes (Random Forest as top performer with 73.22% accuracy).

## Interactive Demo

Explore the R notebook interactively!  
[View R Notebook on nbviewer](https://nbviewer.org/github/Awnish005123/Diabetic-Patient-Readmission-Prediction/blob/main/notebook.Rmd) (Click to render the full R Markdown with code, visuals, and outputs).

## Key Findings

- **Best Model**: Random Forest with strong performance on accuracy, Kappa, ROC curve, and confusion matrix.
- **Top Predictors**:
  - Number of inpatient visits
  - Total diagnoses
  - Lab procedures count
  - Medication numbers
- **Insights**: Emphasizes the need for continued care after discharge to lower readmission rates.

