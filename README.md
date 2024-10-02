# Diabetic Patient Readmission Prediction
![R](https://img.shields.io/badge/R-4.0%2B-276DC3?style=flat&logo=r&logoColor Overview

This GitHub project predicts 30-day hospital readmissions for diabetic patients using machine learning models. It leverages a modified Kaggle notebook (originally by chongchong33) based on the UCI Diabetes 130-US Hospitals dataset (1999–2008), fully implemented in R for data exploration, preprocessing, modeling, and evaluation.

# Key Objectives:

Build predictive models to identify high-risk diabetic patients for readmission.

Analyze factors like hospital stays, diagnoses, lab procedures, and medications.

Recommend improved post-discharge care to reduce readmissions.

*Dataset*: ~100,000 patient encounters from 130 US hospitals, with 50+ features including demographics, clinical data, medications, and lab results. Models evaluated: Logistic Regression, Decision Tree, Random Forest, Naïve Bayes (Random Forest as top performer with 73.22% accuracy).

# Methods Used

Developed a predictive model using comprehensive healthcare data (demographic, clinical, diagnostic, and medication features) to identify diabetic patients at high risk for 30-day readmission. Evaluated four machine learning algorithms (Logistic Regression, Decision Tree, Random Forest, and Naïve Bayes) using multiple performance metrics (accuracy, Kappa, ROC curve, confusion matrix). The R-based pipeline included data preprocessing (imputation, encoding, balancing with ROSE), exploratory analysis (using dplyr, skimr, psych, ggplot2), model training (caret), and cross-validation for robust evaluation.

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

# Implications & Recommendations
Clinical Impact: Actionable insights for hospitals to focus resources on inpatient treatment quality and robust post-discharge care programs, enabling early identification of high-risk patients for proactive interventions.

Improved Patient Outcomes: Predictive modeling supports evidence-based strategies to prevent readmissions, enhancing quality of life for diabetic patients.

Healthcare Resource Optimization: Helps allocate resources effectively to reduce costly readmissions, with potential for significant economic savings (addressing $41B+ annual US costs).

Technical Achievement: Successfully implemented and compared multiple machine learning approaches, demonstrating practical application of data science in clinical decision-making and providing evidence-based recommendations for healthcare practice improvement.

# Quick Start

## Install packages
install.packages(c("dplyr", "skimr", "stringr", "psych", "ROSE", "ggplot2", "caret"))

## Clone and run
git clone https://github.com/Awnish005123/Diabetic-Patient-Readmission-Prediction.git

MIT License | ⭐ Star if helpful! 🏥✨