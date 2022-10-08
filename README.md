### Medium
https://lukaskris12.medium.com/analysis-and-predict-heart-disease-2449a519a994

# Introduction
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

##### Source

This dataset was created by combining different datasets already available independently but not combined before. In this dataset, 5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes. The five datasets used for its curation are:

Cleveland: 303 observations
Hungarian: 294 observations
Switzerland: 123 observations
Long Beach VA: 200 observations
Stalog (Heart) Data Set: 270 observations
Total: 1190 observations Duplicated: 272 observations

Every dataset used can be found under the Index of heart disease datasets from UCI Machine Learning Repository on the following link: https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/

# Problem/Overview
Using this (https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/download?datasetVersionNumber=1) dataset, we are to design a Machine Learning model that will correctly if given the inputs, predict whether a person has heart disease or not.

This is a type of Logistic problem, and we are going to use a classification model to derive our solution, that is we are going to design a model that will correctly predict whether a person is having heart disease or not. The dataset consist of twelve columns, in which the first eleven columns are the independent features, while the last column is the dependent feature.

##### Attribute Information
Age: The age of the patient, in years.

Sex: The patient's gender, M or F.

ChestPainType: The type of chest pain experienced by the patient.

- TA: Typical Angina
- ATA: Atypical Angina
- NAP: Non-Anginal Pain
- ASY: Asymptomatic

RestingBP: The patient's resting blood pressure in mmHg.

Cholesterol: The patient's serum cholesterol in mg/dl.

FastingBS: The patient's fasting blood sugar.

- 1 if glucose is greater than 120 mg/dl
- 0 if not

RestingECG: The patient's resting ECG.

- Normal
- ST : having ST-T wave abnormality
- LVH : showing probable or definite left ventricular hypertrophy

MaxHR: The patient's maximum heart rate achieved in beats per min.

ExerciseAngina: Exercise induced angina, yes or no.

Oldpeak: The patient's numeric measure of ST depression induced by exercise relative to rest.

ST_Slope: The slope of the peak exercise ST segment.

- Up : upsloping
- Flat 
- Down : downsloping

HeartDisease: Output class

- 1 : heart disease
- 0 : normal