# Titanic Survival Prediction

## Overview

The Titanic Survival Prediction project uses the Titanic dataset to build a predictive model that determines whether a passenger on the Titanic survived or not. This is a classic beginner project that introduces the basics of data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning model building.

## Dataset

The dataset contains information about individual passengers on the Titanic, including:

- **PassengerId**: Unique ID for each passenger
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings or spouses aboard the Titanic
- **Parch**: Number of parents or children aboard the Titanic
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- **Survived**: Survival status (0 = No, 1 = Yes) [Target Variable]

## Key Steps

1. **Data Preprocessing**:
    - Handling missing values.
    - Converting categorical variables to numerical format.
    - Normalizing and scaling features.
  
2. **Exploratory Data Analysis (EDA)**:
    - Analyzing the distribution of different features.
    - Identifying correlations between features.
    - Visualizing data using plots.

3. **Feature Engineering**:
    - Creating new features from existing ones (e.g., family size from SibSp and Parch).
    - Encoding categorical variables.
    - Selecting relevant features.

4. **Model Building**:
    - Splitting the data into training and testing sets.
    - Training various machine learning models (e.g., Logistic Regression, Random Forest, etc.).
    - Evaluating model performance using metrics like accuracy, precision, recall, and F1 score.
    - Fine-tuning models using hyperparameter optimization.

5. **Model Evaluation**:
    - Comparing different models.
    - Selecting the best model based on performance metrics.
    - Making predictions on the test dataset.

## Results

The final model's performance will be evaluated based on its ability to accurately predict the survival of passengers in the test dataset. Detailed results and visualizations can be found in the notebooks.

