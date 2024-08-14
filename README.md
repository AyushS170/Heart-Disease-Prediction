#Predicting heart disease using Machine Learning 

This notebook looks into usingvarious Python-based ML adn DS libraries in an atempt to build a ML Model capable of predicting whether or not someone has heart disease based on their medical attributes.

We're going to take he following approach:
1. Problem defination
2. Data
3. Evaluation
4. Featuring
5. Modelling
6. Experimentation

## 1. Problem Defination

In a statement ,
> Givem clinical parameters about a patient, can we predict whether or not they have a heart Disease

## 2. Data
The data we are using in current project is uploaded in repository

for extra data we can refer this website:
https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

## 3. Evaluation

> If we can gain accuracy of model than its previous accuracy at predicting whether or not a patient has heart disease the proof of concept we'll pursue the project.

## 4. Features
1. age: age in years
2. sex: sex (1 = male; 0 = female)
3. cp: chest pain type
        -- Value 1: typical angina
        -- Value 2: atypical angina
        -- Value 3: non-anginal pain
        -- Value 4: asymptomatic
4. trestbps: resting blood pressure (in mm Hg on admission to the hospital)
5. chol: serum cholestoral in mg/dl
6. fbs: (fasting blood sugar > 120 mg/dl)  (1 = true; 0 = false)
7. restecg: resting electrocardiographic results
        -- Value 0: normal
        -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
        -- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
        
8. thalach: maximum heart rate achieved
9. exang: exercise induced angina (1 = yes; 0 = no)
10. oldpeak = ST depression induced by exercise relative to rest
11. slope: the slope of the peak exercise ST segment
        -- Value 1: upsloping
        -- Value 2: flat
        -- Value 3: downsloping
12. ca: number of major vessels (0-3) colored by flourosopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
14. num: diagnosis of heart disease (angiographic disease status)
        -- Value 0: < 50% diameter narrowing
        -- Value 1: > 50% diameter narrowing
        (in any major vessel: attributes 59 through 68 are vessels)
