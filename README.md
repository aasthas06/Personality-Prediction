# Personality-Prediction

## Overview

This project uses a Decision Tree Classifier to predict whether an individual is an **Introvert** or **Extrovert** based on behavioural and social characteristics. The goal was to explore how factors such as social activity, time spent alone, stage fear, and online engagement relate to personality type.

## Dataset Features

* Time Spent Alone
* Stage Fear
* Social Event Attendance
* Going Outside Frequency
* Drained After Socialising
* Friends Circle Size
* Social Media Post Frequency

## Methodology

* Cleaned and preprocessed missing values
* Encoded categorical variables into numerical values
* Split data into training and testing sets (80/20)
* Trained a Decision Tree Classification model using Scikit-learn
* Evaluated performance using Accuracy, Precision, Recall, F1-Score, and a Confusion Matrix

## Results

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 87.4% |
| Precision | 86.4% |
| Recall    | 86.7% |
| F1-Score  | 86.5% |

The model correctly classified **507 out of 580** test samples, demonstrating strong predictive performance with balanced results across both personality classes.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook

## Author

Aastha Singhal
