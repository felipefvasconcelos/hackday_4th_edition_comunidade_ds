# hackday_4th_edition_comunidade_ds

In March 25 and 26 of 2023, the DS Community promoted a Hackday event with a machine learning competition (https://www.kaggle.com/competitions/cdshackdays4).

This repository contains the notebooks and the final model developed by my team (The Last of NaN’s), which reached F1-Score of 0.97143 and assured the 5th position in the competition.

## 1. Business Problem – Challenge

A European Hotel Chain is concerned about the increasing cancellation rate after pandemics. It wants to know the reason why the customers are increasingly cancelling their reservations and understand what might have change in the customers behavior.

The challenge: build a machine learning model to predict whether the reservation will be cancelled or not and get the best performance.

Performance Metric: F1-Score

## 2. Data

The datasets used in the competition can be found at https://www.kaggle.com/competitions/cdshackdays4/data

## 3. Solution Strategy

Since the objective was to get highest F1-Score to win the competition, our team adopted the following strategy:

1. Do a quick end-to-end run with a tree-based model (no need of rescaling) following the structure:

  * Data Description Analysis
  * Feature Engineering
  * Data Filtering
  * Feature Selection
  * Machine Learning Modeling
  * Understand Model Performance
  * Sumbit Predicions into Kaggle Competition
  
2. Test different encoding methods and machine learning models.
3. Further work on feature engineering.
4. Tuning model parameters.

## 4. Tools and Machine Learning Models

* Python 3.11.2
* Linear Regression
* SVM
* Gradient Boosting
* Random Forest Regressor
* XGBoost Regressor

## 5. Models Performance

Final performance:
* Precision: 0.96321
* Recall: 0.96631
* F1 Score: 0.97193

## 6. Conclusion

The final model was an ensemble of the predictions given by XGBoost, Gradient Boosting and Random Forest Classifier.

## 7. Next Steps
There are several further steps that could be applied to the project. Some of them listed below:
* Perform deeper data analysis.
* Join train and test data and train the model again before submission.
* Apply a feature selector (such as Boruta).
* Implement cross-validation.
* Test more Machine Learning models (such as KNN).
* Try different weights in the voting system of the ensemble model.
<br>

---
## References:

* Datasets Hotel Chain Cancellation Rating from [Kaggle](https://www.kaggle.com/competitions/cdshackdays4)
* Blog [Seja um Data Scientist](https://sejaumdatascientist.com/os-5-projetos-de-data-science-que-fara-o-recrutador-olhar-para-voce/)

