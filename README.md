# Diabetes Prediction

## Project Overview
In this project, my team and I attempt to predict the onset of diabetes based on a set of medical characteristics provided by the diabetes dataset included in this repository. This project was completed as a group project as part of our Masters in Data Science program at Bellevue University.

## Data
The Diabetes prediction dataset encompasses a diverse set of features, including age, gender, BMI, hypertension, heart disease, smoking history, HbA1c level, and blood glucose level of 100,000 patients.
These features offer a comprehensive view of patients' health profiles, making it an ideal dataset for developing predictive models. 
The ultimate goal is to assist healthcare professionals in identifying individuals at risk of diabetes and to contribute to the development of personalized treatment plans.


## Exploratory Data Analysis (EDA)
The EDA with this data uncovered there is a 2:3 ratio for diabetes in men to females. Also, the higher the BMI, the more likely a patient is at risk for diabetes. Lastly, the average age of a patient with diabetes peaks at 41.89 years of age.

## Data preprocessing
There were no missing values to deal with. We gained an understanding of the datatypes, shape, and columns in the dataset. We removed the 'other' under gender to allow it to be a binary variable. We also transformed the smoking history column, which 
represents a categorical variable encompassing six distinct features, each reflecting various aspects of individuals' smoking habits. 
To effectively utilize this information in our predictive models, it necessitates transformation into indicator variables.

## Modeling & Results
We utilize the K-nearest neighbors modeling algorithm. We obtain an accuracy of 96.03%, and after conducting Grid Search analysis to find the best k value, we obtain a 96.11% accuracy.
