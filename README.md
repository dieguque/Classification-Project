# Chicago Food Inspections

Diego Duque

## Abstract

According to the **City of Chicago** are over 15,000 food establishments across the City of Chicago that are subject to sanitation inspections by the Department of Public Health. Three dozen inspectors are responsible for checking these establishments, which means one inspector is responsible for nearly 470 food establishments. The Department of Public Health has systematically collected the results of nearly 100,000 sanitation inspections. That is enough data to make a classification project to interpret and even create some models to understand and predict these inspections.
This data is public and avilable at the [Chicago Department of Public Health’s Food Protection Program](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5).

## Design

This project originates from the idea to understand more about the huge restaurant industry in Chicago. As a Chicago resident, and as a user of some of this restaurants I got the idea to get more info for other residents. Especially for parents and families in general. Fortunately, the [City of Chicago](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5) has some related info to all food establishments in the city. This huge data set was used to create some classification and interpreation models.

## Data

The data is public. It is available on [Kaggle](https://www.kaggle.com/tjkyner/chicago-food-inspections) and the [City of Chicago](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5). This datadate has 17 features and 223K inspections. Most of its features are categorical features.

## Algorithms 

Data Collection and Manipulation

Gathered data from the [City of Chicago](https://data.cityofchicago.org/Health-Human-Services/Food-Inspections/4ijn-s7e5) and did feature engineering to cut down the features from 17 to 9.

Modeling


Random Forest
XGBoost

## Tools

1. Sklearn 
  - LogisticRegression
  - RandomForestClassifier
  - GridSearchCV
  - Fbeta_score
  - Confusion_matrix
  - Classification_report
2. Xgboost - XGBClassifier
3. Numpy
4. Pandas
