# Diabetes Feature Engineering

This project aims to develop a **machine learning model** that can predict whether a person has diabetes based on various health features, using the **Diabetes dataset**. The focus is on **feature engineering** to improve model performance.

The dataset comes from a study on **Pima Indian women aged 21 and above** living in Phoenix, Arizona. It contains **768 observations** and **8 numerical independent variables**. The target variable, **Outcome**, indicates diabetes status: 1 = positive, 0 = negative.


# Problem Statement
Build a model that can predict diabetes given patient features. The process includes **Exploratory Data Analysis (EDA)** and **Feature Engineering** before model training.


# Dataset Features

| Feature | Description |
|---------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Glucose level |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Skin thickness |
| Insulin | Insulin level |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes probability based on family history |
| Age | Age (years) |
| Outcome | Diabetes status (1 = positive, 0 = negative) |


#Project Steps

## Exploratory Data Analysis (EDA)
- General overview of the dataset
- Analysis of numerical and categorical variables
- Target variable analysis
- Outlier detection
- Missing value analysis
- Correlation analysis

## Feature Engineering
- Handling missing and outlier values
- Creating new features (Age, BMI, Glucose, Insulin, etc.)
- Label Encoding and One-Hot Encoding
- Standardizing numerical variables

## Modeling
- Random Forest Classifier

## Feature Importance
- Visualizing which features contribute most to the model
- Evaluating the impact of newly created features


