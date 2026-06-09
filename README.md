# Task3-Titanic-Survival-Prediction
Titanic Survival Prediction using Machine Learning with feature engineering, model training, evaluation, and explainability.
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
