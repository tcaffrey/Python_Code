# Python_Code

## Projects included within this Python repository

### 1. Classification of Online Shoppers intention
Based on the Kaggle data set uploaded [here](https://www.kaggle.com/roshansharma/online-shoppers-intention). This is an example of building a binary classification solution and tuning a variety of different models. <br/> <br/>
A binary classification problem that looks to model if an online shopper will make a purchase or not based on some online behaviours. A variety of classification models are tested (Logistic Regression, SVM, RF and Xgboost for example).  <br/> <br/>
91% validation accuracy and 0.68 F1 score achieved, which is higher than found on any other uploads on the Kaggle website. 

### 2. Predicting Future Sales
Based on the Kaggle challenge [Predicting Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales/overview). This is an example of a regression problem, with heavy use of manipulating data to create features. <br/> <br/>
A rank of 2416 / 6284 (at time of submission) with an RMSE value of 0.96224 was achieved, with an Xgboost model. Due to the size of the dataset I wasn't able to run a model using the full dataset on my laptop so believe with the full dataset I could achieve a better score. 

### 3. Segmentation Project 
Contains 2 files: 
- Segmentation Project
- Decision Tree Segmentation
The first file contains a notebook for a segmentation project worked on in the past during a previous role. It goes through the process of creating a segmentation and coming to a solution on the chosen number of clusters. 
The second contains the segmentation and then fits a decision tree to the clusters so a series of rules could be generated so that future customers can be assigned to a cluster and existing customers can be reassigned if their behaviour has changed without re running the python script. These rules were implemented within SQL so they could be re-run at a specified time (weekly, monthly etc.) and then the original segmentation and decision tree updated at a larger interval (half yearly, yearly, etc.).
