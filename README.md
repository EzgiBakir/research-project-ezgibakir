# Fire Incident Analysis - İzmir 2023

This project explores fire response times and fire outcome prediction using real fire incident data from İzmir Büyükşehir Belediyesi (2023).

# Research Questions

1. Is there a significant difference in firefighter arrival times between urban and rural areas?
2. Can fire outcomes be predicted using early incident data such as fire type, cause, arrival time, and materials used?

# Dataset
12 986 fire records from İzmir (year 2023)
Each record includes: fire type, cause, response time, materials used, outcome, and location

# Methods
Preprocessing: missing value handling, encoding, feature engineering
Statistical testing: Shapiro-Wilk, Levene’s test, Mann-Whitney U
Machine Learning model: Random Forest Classifier
Hyperparameter tuning with RandomizedSearchCV
Feature importance visualization and outcome distribution analysis

# Key Findings
Rural fire response times are significantly longer than urban areas
Fire type is the most important predictor of fire outcome
Random Forest outperforms a naive baseline model
Visualization supports statistical results

# Deliverables
Final paper in IEEE format: see reports/Ezgi_Bakir_Project_Report.pdf
Full analysis code: see notebooks/fire_analysis_notebook.ipynb
All generated figures: in reports/figures/

# Author
Ezgi Bakır
Graduate School of Informatics 
Middle East Technical University
ezgi.bakir@metu.edu.tr


