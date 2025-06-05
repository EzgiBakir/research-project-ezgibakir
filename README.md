# Fire Incident Analysis - İzmir 2023

This project explores fire response times and fire outcome prediction using real fire incident data from İzmir Büyükşehir Belediyesi (2023).

# Research Questions

1. Is there a significant difference in firefighter arrival times between urban and rural areas? <br>
2. Can fire outcomes be predicted using early incident data such as fire type, cause, arrival time, and materials used? <br>

# Dataset
12 986 fire records from İzmir (year 2023) <br>
Each record includes: fire type, cause, response time, materials used, outcome, and location <br>

# Methods
Preprocessing: missing value handling, encoding, feature engineering <br>
Statistical testing: Shapiro-Wilk, Levene’s test, Mann-Whitney U <br>
Machine Learning model: Random Forest Classifier <br>
Hyperparameter tuning with RandomizedSearchCV <br>
Feature importance visualization and outcome distribution analysis <br>

# Key Findings
Rural fire response times are significantly longer than urban areas <br>
Fire type is the most important predictor of fire outcome <br>
Random Forest outperforms a naive baseline model <br>
Visualization supports statistical results <br>

# Deliverables
Final paper in IEEE format: see reports/Ezgi_Bakir_Project_Report.pdf <br>
Full analysis code: see notebooks/fire_analysis_notebook.ipynb <br>
All generated figures: in reports/figures/ <br>

# Author
Ezgi Bakır <br>
Graduate School of Informatics <br>
Middle East Technical University <br>
ezgi.bakir@metu.edu.tr <br>


