# Task3-Titanic-Survival-Prediction
Titanic Survival Prediction using Machine Learning with feature engineering, model training, evaluation, and explainability.

##Executive Summary:---
Titanic Survival Prediction using Machine Learning

This project predicts passenger survival on the Titanic using machine learning classification techniques. Data preprocessing included handling missing values, encoding categorical variables, and feature engineering such as title extraction, family size calculation, and cabin presence detection. Logistic Regression and Random Forest classifiers were trained and evaluated. Model performance was assessed using accuracy, confusion matrix, and classification reports. Feature importance analysis was used to explain model decisions, showing that gender, title, age, and fare were among the most influential factors. The final model was saved and tested using an example prediction, demonstrating a complete end-to-end classification workflow.


# Titanic Survival Prediction

## Objective
Predict whether a passenger survived the Titanic disaster using Machine Learning.

## Feature Engineering
- Title Extraction
- Family Size Creation
- Cabin Presence Indicator

## Models Used
- Logistic Regression
- Random Forest Classifier

## Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report

## Explainability
Feature Importance analysis using Random Forest.

## Files
- Task3_Titanic_Survival_Prediction.ipynb
- titanic_model.pkl

## Example Prediction

```python
import joblib

model = joblib.load('titanic_model.pkl')

prediction = model.predict(sample)

print(prediction)
```
