# Predicting Diabetes Readmission
This project applies supervised machine learning to predict early hospital readmissions (within 30 days) among diabetic patients using a large real-world dataset from the UCI Machine Learning Repository. The dataset used for this project is the "Diabetes 130-US hospitals for years 1999-2008".

Available here: https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

This dataset represents 10 years (1999-2008) of clinical care data from 130 US hospitals and integrated delivery networks. 
Each record corresponds to a hospital admission of a patient diagnosed with diabetes, including information about laboratory tests, medications, patient demographics, diagnostic codes, and discharge outcomes. The dataset contains over 100,000 records, making it one of the most comprehensive open-source clinical datasets for diabetes research.

Early readmission is a critical issue in healthcare, often signaling gaps in post-discharge care and contributing to higher medical costs. 
By accurately identifying patients at risk for early return, hospitals can implement proactive interventions that improve patient outcomes and optimize resource allocation. This project models this risk using supervised machine learning techniques.

### Project Goal
To develop a machine learning model that can accurately predict whether a patient diagnosed with diabetes will be readmitted to the hospital within 30 days of discharge. This can help health systems identify high-risk individuals and allocate resources accordingly.

----

The target variable was engineered to identify early readmissions, and the dataset was cleaned and transformed using a combination of missing data handling, encoding strategies, and scaling techniques. Correlation analysis was performed to support feature selection, and the most informative features were retained for model development. Several classification models were explored, with Random Forest ultimately selected for its balance of performance and interpretability.

The analysis was conducted in Python using pandas and numpy for data wrangling, scikit-learn and xgboost for model development, and matplotlib and seaborn for visualization. Cross-validation was used to ensure model generalizability, and hyperparameters were optimized through grid search. The final model was evaluated using ROC curves and standard classification metrics, achieving moderate performance in identifying early readmission risk.

This work was completed as the final project for the Machine Learning for Public Health course at the University of Chicago. It reflects my interest in applying machine learning to real-world healthcare data to improve patient outcomes and support data-informed decision-making within clinical systems.

