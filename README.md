# Heart-Disease-Prediction--Data-Analysis-and-Preliminary-Modeling
This project analyzes cardiovascular disease (CVD) data to identify heart attack risk factors like age, cholesterol, and blood pressure. After cleaning the data and exploring key relationships, a logistic regression model is built to predict CVD risk, serving as a baseline for further improvements.
Project Overview
This project aims to analyze cardiovascular disease (CVD) data and build a predictive model to detect heart attack risk. Cardiovascular diseases are the leading cause of death globally, and identifying key risk factors is essential for early detection and prevention. The dataset provided contains various patient attributes related to heart health, and the objective is to conduct a comprehensive analysis and create a baseline model for heart attack prediction.
________________________________________
Table of Contents
1.	Dataset Overview
2.	Objectives
3.	Project Workflow
4.	Preliminary Data Analysis
o	Data Inspection
o	Data Cleaning
5.	Exploratory Data Analysis (EDA)
o	Statistical Summary
o	Categorical Variables
o	CVD and Age Distribution
o	CVD and Gender Distribution
o	Resting Blood Pressure
o	Cholesterol Levels
o	Exercise and Heart Attack
o	Thalassemia and CVD
6.	Factor Analysis
7.	Pair Plot Visualization
8.	Baseline Model: Logistic Regression
9.	Conclusion
10.	How to Use This Repository
11.	Future Work
________________________________________
Dataset Overview
The dataset consists of medical records for patients, including attributes such as age, gender, Resting Blood Pressure, sereum cholesterol, fasting blood sugar, resting electrocardiographic result (>120 mg then 1 orelse 0) , thalach (Maximum heart rate achived), exang (exercise induced angina , yes =1 no=0), oldpeak (ST depresion induced by exercise related rate), ca (Nymber of major vessels 0-3), thal (3-normal, 6-fixed dffect,7- recversible defect,  and whether the patient has had a heart attack (CVD). This data will help us understand the factors that are strongly associated with heart diseases.
•	Target Variable: Presence of CVD (binary: 1 = Yes, 0 = No)
•	Key Features: Age, Gender, Cholesterol, Resting Blood Pressure, Max Heart Rate, Exercise, Thalassemia, etc.
________________________________________
Objectives
•	Perform preliminary data analysis: handle missing values, duplicates, and basic inspection.
•	Conduct an exploratory data analysis (EDA) to understand the relationships between features and the target variable.
•	Build and evaluate a baseline logistic regression model to predict the likelihood of a heart attack.
________________________________________
Project Workflow
1.	Preliminary Data Analysis
o	Inspect the dataset for structure, missing values, and duplicates.
o	Clean the data by removing duplicates and treating missing values using appropriate strategies (e.g., mean/median imputation, mode, etc.).
2.	Exploratory Data Analysis (EDA)
o	Generate a statistical summary to understand central tendencies and distribution (mean, median, range, variance).
o	Analyze categorical variables using count plots.
o	Examine the distribution of CVD across age groups and gender.
o	Explore key health factors like resting blood pressure, cholesterol, and exercise-induced anomalies.
o	Create pair plots for feature interaction analysis.
3.	Baseline Model
o	Develop a logistic regression model to predict heart attack risk based on the features.
o	Evaluate the model performance using metrics like accuracy, precision, recall, and F1-score.
________________________________________
Preliminary Data Analysis
Data Inspection
•	Structure of the Data: Includes attributes like age, gender, cholesterol, blood pressure, max heart rate, thalassemia, and CVD status.
•	Missing Values: Identified missing values in the dataset and treated them using mean/median for numerical data and mode for categorical data.
•	Duplicates: Duplicate entries in the dataset were identified and removed to ensure data integrity.
Data Cleaning
•	Strategy for Missing Values: Missing values were treated based on the data type:
o	For numerical variables: Mean or median imputation.
o	For categorical variables: Mode imputation.
•	Outliers: Checked for extreme values that could skew the analysis and adjusted appropriately.
________________________________________
Exploratory Data Analysis (EDA)
Statistical Summary
•	Calculated measures of central tendencies (mean, median, mode) and spread (variance, standard deviation) to provide insights into the distribution of the data.
Categorical Variables
•	Gender, Chest Pain Type, Thalassemia: Count plots were used to analyze the frequency and distribution of categorical features.
CVD and Age Distribution
•	The incidence of CVD was analyzed across different age groups to identify age-related risks.
CVD and Gender Distribution
•	Examined the composition of patients with respect to gender to understand the gender-specific risk of CVD.
Resting Blood Pressure
•	Analyzed how anomalies in resting blood pressure are associated with heart attack risk.
Cholesterol Levels
•	Examined the relationship between cholesterol levels and the occurrence of heart attacks.
Exercise and Heart Attack
•	Investigated how peak heart rate during exercise correlates with the occurrence of heart attacks.
Thalassemia and CVD
•	Studied whether thalassemia plays a significant role in the development of heart disease.
________________________________________
Factor Analysis
The relationship between all factors was explored to identify any strong correlations or patterns that might predict CVD more effectively.
________________________________________
Pair Plot Visualization
A pair plot was generated to visualize the interactions and relationships between all numerical variables, aiding in pattern detection and insight discovery.
________________________________________
Baseline Model: Logistic Regression
A logistic regression model was implemented to predict heart attack risk. The model was trained and evaluated using standard metrics:
•	Accuracy
•	Precision
•	Recall
•	F1-Score
This model serves as a baseline, and future models may improve upon its performance using more advanced techniques.
________________________________________
Conclusion
•	The exploratory analysis highlighted several factors (age, gender, cholesterol levels, resting blood pressure, exercise) that have a significant relationship with heart disease.
•	The logistic regression model provides a basic framework for predicting heart attack risk, and further improvements can be made by refining the feature set and experimenting with other machine learning algorithms.
