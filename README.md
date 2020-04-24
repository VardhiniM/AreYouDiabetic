# AreYouDiabetic
Predicting if someone is diabetic or not based on their health history and parameters such as Insulin and Glucose levels

## Business Problem
Diabetes is one of the deadliest and chronic diseases. About one in seven U.S. adults has diabetes now. By 2050, as many as one in three may become diabetic. Many complications occur if diabetes remains untreated and unidentified. Identifying patients who are at high-risk of becoming diabetic allows early medical interventions.

## CRISP-DM
CRISP-DM breaks the process of data mining into six major phases:
1) Business Understanding
2) Data Understanding
3) Data Preparation
4) Modeling
5) Evaluation
6) Deployment

I have applied the CRISP-DM process to this use case and developed a predictive model that classifies users as diabetic prone or non-diabetic. This will help the physicians to do early intervention if the user is prone to be diabetic based on the model predictions.

Data source: https://www.kaggle.com/uciml/pima-indians-diabetes-database

I have tried different models to improve my prediction accuracy while having a good recall metric. Since false positives for this use-case is a costly mistake and leads to a missed opportunity for early intervention. The random forest model gives an accuracy of 90% with a 91% recall value.
