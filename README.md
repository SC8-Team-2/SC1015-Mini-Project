# SC1005 Mini Project 
![Header Photo](https://res.cloudinary.com/jiawoi/image/upload/v1650712074/banner.jpg)\
Photo by [CardMapr](https://unsplash.com/@cardmapr?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
  
  
## 🎨 About this project
Our project will try to predict if a credit card applicant is 'good' or 'bad'. We are using the lovely **Credit Card Approval Prediction** dataset from Kaggle https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction

What defines 'good' or 'bad'? An applicant is 'good' when he/she has their credit card application approved by the bank, while getting rejected by the bank is considered as 'bad'. By looking at an applicant's records, which contains information such as age, no. of family members, income, no. of years working, we aim to predict the the likelihood of a bank issuing a particular applicant a credit card. 

Additionally, we would also be predicting if a credit card applicant will continue to make his/her payments on time in the future. 

## 📔 Notebooks in this project

| Notebook  | Description |
| ------------- | ------------- |
| [Data Preparation](https://github.com/SC8-Team-2/SC1015-Mini-Project/blob/main/Data%20Preparation.ipynb) | In this notebook, we processed the data from two datasets, the first one containing the applicant information and the second one containing the list of all credit card bill payments. We classify all credit payment records and decide if a applicant has a good or bad history of making payments on time. Then, we merge the two datasets together and do some basic data cleaning |
| [Data Visualization](https://github.com/SC8-Team-2/SC1015-Mini-Project/blob/main/Data%20Visualization.ipynb) | This is the visualization notebook, where we use charts and other tools to help give us a better understanding of our dataset, and find out if there are any notable trends that we can use for predicting |
| [Classification (Decision Tree and RandomForest)](https://github.com/SC8-Team-2/SC1015-Mini-Project/blob/main/Classification%20(Decision%20Tree%20and%20RandomForest).ipynb) | xxxxxxxx |
| [Models Analysis](https://github.com/SC8-Team-2/SC1015-Mini-Project/blob/main/Models%20Analysis.ipynb) | We tried experimenting with [PyCaret](https://pycaret.org/), which is a machine learning library. PyCaret allows us to easily compare different models to help us in deciding what model we should use for prediction |
| [Classification with SMOTE Over-sampling](https://github.com/SC8-Team-2/SC1015-Mini-Project/blob/main/Classification%20with%20SMOTE%20Over-sampling.ipynb) | xxxxxxx |

## ⚙️ Models/Tools Used
- Decision Tree Classification
- Random Forest Classifcation
- Synthetic Minority Oversampling Technique (SMOTE)

## 💡 Outcome
We have learnt different algorithms for classification of imbalanced datasets like SMOTE as well as improving accuracies by using the Random Forest model.
Banks can use the models that we tried to help decide whether or not to issue an applicant a credit card based on their on time payments

## 🙋‍♂️ Contributions
- Isaac Wong (EDA, GridSearchCV, Synthetic Minority Oversampling Technique, Data Resampling)
- Lim Jia Wei (EDA, Models Analysis, Data Visualization)
- Ang Teck Yee (EDA, DecisionTreeClassifier)
- Darren Lee (EDA, RandomForestClassifier, GridSearchCV)

## 📃 References
https://www.analyticsvidhya.com/blog/2021/06/5-techniques-to-handle-imbalanced-data-for-a-classification-problem/
https://www.section.io/engineering-education/introduction-to-random-forest-in-machine-learning/
