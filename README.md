# SC1005 Mini Project 
## About this project
We are using the lovely **Credit Card Approval Prediction** dataset from Kaggle https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction

Our goal is to predict if a credit card applicant will make his/her future payments on time using information submitted by the applicant

## Notebooks in this project

| Notebook  | Description |
| ------------- | ------------- |
| [Data Preparation](https://github.com/SC8-Team-2/SC1015-Mini-Project/blob/main/Data%20Preparation.ipynb) | In this notebook, we processed the data from two datasets, the first one containing the applicant information and the second one containing the list of all credit card bill payments. We classify all credit payment records and decide if a applicant has a good or bad history of making payments on time. Then, we merge the two datasets together and do some basic data cleaning |
| [Data Visualization](https://github.com/SC8-Team-2/SC1015-Mini-Project/blob/main/Data%20Visualization.ipynb) | This is the visualization notebook, where we use charts and other tools to help give us a better understanding of our dataset, and find out if there are any notable trends that we can use for predicting |
| [Classification (Decision Tree and RandomForest)](https://github.com/SC8-Team-2/SC1015-Mini-Project/blob/main/Classification%20(Decision%20Tree%20and%20RandomForest).ipynb) | dse |
| [Models Analysis](https://github.com/SC8-Team-2/SC1015-Mini-Project/blob/main/Models%20Analysis.ipynb) | We tried experimenting with [PyCaret](https://pycaret.org/), which is a machine learning library. PyCaret allows us to easily compare different models to help us in deciding what model we should use for prediction |
| [Classification with SMOTE Over-sampling](https://github.com/SC8-Team-2/SC1015-Mini-Project/blob/main/Classification%20with%20SMOTE%20Over-sampling.ipynb) | dse |

## Models/Tools Used
- Synthetic Minority Over-sampling Technique (SMOTE)
- Random Forest Classifier

## Outcome
We have learnt different algorithms for classification of imbalanced datasets like SMOTE as well as improving accuracies by using the Random Forest model.
Banks can use the models that we tried to help decide whether or not to issue an applicant a credit card based on their on time payments
