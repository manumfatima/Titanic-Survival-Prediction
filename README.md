# Titanic-Survival-Prediction

## Overview

This project uses supervised machine learning to predict whether a passenger survived the Titanic disaster based on passenger information such as age, gender, ticket class, fare, and family relationships.

The goal is to build a classification model that learns patterns from historical Titanic data and predicts survival outcomes for unseen passengers.

## Dataset

The dataset contains information about Titanic passengers, including:

* Passenger Class (Pclass)
* Sex
* Age
* Fare
* Number of Siblings/Spouses Aboard (SibSp)
* Number of Parents/Children Aboard (Parch)
* Embarked Port
* Survival Status (Target Variable)

## Project Workflow

1. Data Cleaning and Preprocessing

   * Handle missing values
   * Encode categorical variables
   * Prepare features for training

2. Exploratory Data Analysis (EDA)

   * Analyze survival patterns
   * Visualize feature distributions
   * Examine relationships between features and survival

3. Model Training

   * Split data into training and testing sets
   * Train classification models
   * Evaluate model performance using appropriate metrics

4. Feature Analysis

   * Compare the influence of different passenger attributes on survival predictions
   * Identify the most informative features

## Results

The model successfully learned patterns from the Titanic dataset and achieved reliable classification performance.

One notable finding from the analysis was that **Passenger Class (Pclass)** was the strongest predictor of survival, outperforming other features such as **Gender (Sex)**. This suggests that a passenger's socioeconomic status and cabin location had a significant impact on survival probability.

Key observations:

* First-class passengers had a higher likelihood of survival.
* Lower passenger classes showed reduced survival rates.
* Passenger class contributed more predictive power than gender in this implementation.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Future Improvements

* Hyperparameter tuning
* Ensemble learning methods
* Feature engineering
* Cross-validation
* Model deployment using Flask or Streamlit

## Conclusion

This project demonstrates the application of supervised machine learning to a real-world classification problem. Through data preprocessing, exploratory analysis, and model training, the model was able to identify important survival patterns within the Titanic dataset, with Passenger Class emerging as the most influential feature in the final predictions.
