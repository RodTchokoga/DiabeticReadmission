# Predicting Hospital Readmission for Diabetic Patients
## Overview  
This projects aims to predict hospital readmission for diabetic patients using ML techniques.
The objective is to classify patients into three categories:  
- NO readmission.
- Readmision within 30 days.
- Readmission after 30 days.
Hospital readmissions are a key indicator of healthcare quality and contribute significantly
to healthcare cost. Accurate prediction can support early intervention and improve patients outcomes.

## Dataset
The dataset used is the **Diabetes 130-US hospital dataset (1999-2008)** from the UCI repersitory.
It contains 101,766 records and 50 features.

## Methodology  
The project follows a structured ML pipeline: data cleaning and preproceessing (including EDA),
feature engineering and selection using **Low-variance filtering** and **Mutual Information**, undersampling for class imbalance.  
The models used are: KNN, SVM, Naive Bayes and Random Forest.

## Results
- Naive Bayes achieved the highest overall accuracy,
- Random Forest showed balanced performance across classes
- All models showed bias toward the majority class (No readmission)
- Prediction *readmission within 30 days* remained challenging.

## Key Insight
Mutual Information analysis showed relatively low feature importance scores, suggesting that hospital readmission is influence
by complex interactions betwween variables rather than single strong predictors.

## COnclusion
ML models can effectively support the prediction of hospital readmissions. however, performance is 
limited by class imbalance and weak individual feature relationships. Future imporovement
should focus on better data balancing techniques, enhancing feature engineering, and more advanced modelling approaches.

## Author
Rodrigue Tchokoga
