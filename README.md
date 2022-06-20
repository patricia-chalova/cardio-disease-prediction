# cardio-disease-prediction

## About
Cardiovascular disease prediction notebook is a final project assignment of a 4 months long Machine Learning course I took in 2019. The goal was to train a classification model to predict presence/absence of a cardiovascular disease based on a dataset consisting of both factual and subjective information about patients health.

Original dataset is available at Kaggle: https://www.kaggle.com/sulianova/cardiovascular-disease-dataset/downloads/cardiovascular-disease-dataset.zip/1 

## Assignment
Train a model for prediction presence or absence of cardiovascular disease based on provided objective, examination and subjective information about a patient. Don't forget to start with precise exploratory data analysis as it might be specifically helpful for this kind of dataset. In the end, we expect to see the best classifier you've been able to train with an explanation of why this one is performing so well. Adding comparison to at least 3 other types of the classifier is required.

## Dataset description

There are 3 types of input features:
  1.	Objective: factual information;
  2.	Examination: results of medical examination;
  3.	Subjective: information was given by the patient.

Features
 ![image](https://user-images.githubusercontent.com/60256130/174602803-29958918-bfbc-46e4-8fa0-fabaeadf2d39.png)

All of the dataset values were collected at the moment of medical examination. 

## Conclusion

3 different classifiers were trained: Decision Tree, Random Forest, Logistic Regression with similar accuracy of cca 72%. Dataset size - 70k and small number of features can be both attributed to this result.
