# Alzheimer’s Prediction Dataset Analysis

## Overview
The Dataset csv file was downloaded from Kaggle Website:
https://www.kaggle.com/datasets/ankushpanday1/alzheimers-prediction-dataset-global
The csv file is inside the Data Folder.

This repository contains an analysis of a dataset focused on predicting the presence of Alzheimer’s disease based on various features, including demographic information, cognitive test scores, and other clinical measurements. Alzheimer's disease is a progressive neurological condition that affects memory, thinking, and behavior. Early diagnosis is crucial for providing patients with the best quality of care and intervention strategies.

The dataset contains several attributes, such as age, gender, cognitive scores, and education level, that are used to determine whether a person has Alzheimer's disease or not. This project aims to perform exploratory data analysis (EDA), create visualizations of the data.

## Dataset Description

The dataset includes the following key columns:

- **Age**: Age of the individual (numeric).
- **Gender**: Gender of the individual (binary: 0 = Male, 1 = Female).
- **Education Level**: Years of education.
- **Cognitive Test Score**: A score representing the individual’s cognitive performance.
- **Alzheimer’s Diagnosis**: Target variable indicating whether the individual has Alzheimer’s disease (1 = Alzheimer’s, 0 = No Alzheimer’s).

### Target Variable

The **target variable** in this analysis is `Alzheimers Diagnosis`, which is a binary classification of whether or not a person has Alzheimer’s disease.

## Analysis and Visualizations

### 1. **Exploratory Data Analysis (EDA)**

To better understand the dataset we needed to do:
- Checking for missing values and handling them appropriately.
- Understanding the distribution of key features such as `Age`, `Education`, and `Cognitive Test Score`.
- Examining the relationship between different features and the target variable.

### 2. **Visualizations**

Several visualizations were created to reveal insights and patterns in the dataset:
- **Correlation Heatmap**: Shows the relationships between the numerical features.
- **Boxplots**: Compare the distribution of features like `Age` and `Cognitive Test Score` for individuals with and without Alzheimer's.
- **Histograms**: Display the distributions of various continuous features.
- **Countplots**: Show the distribution of the target variable and categorical variables like `Gender`.
  
### 3. **Feature Engineering**

Feature engineering techniques were applied to better prepare the dataset for machine learning models. This may include:
- Handling missing values (if any).
- Normalizing or scaling features if necessary.

## Results and Insights

- **Feature Importance**: We observed that certain features like `Cognitive Test Score` had high importance in predicting Alzheimer's disease.
- **Age Factor**: Age was a significant feature, with older individuals showing a higher likelihood of Alzheimer's disease.
- **Gender Distribution**: There may be slight variations between male and female patients, though the disease affects both genders.
  