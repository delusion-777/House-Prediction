# House Price Prediction
A regression-based project for predicting house 🏠 price💲.

## Project objective
The purpose of this project is to study the relationship between various factors (dependent variables) that influence the price (target variable) of houses in India and to predict  house prices using different Machine Learning algorithms.

### Technology and libraries used
- Python
- matplotlib
- seaborn
- numpy
- pandas
- scikit-learn
- scipy
- etc.

## Overview
This is an Indian house price predicting regression based project. 
### Data source
Dataset can be downloaded from [kaggle](https://www.kaggle.com/anmolkumar/house-price-prediction-challenge/tasks?taskId=2304)

### ⚡Exploratory data analysis
- First, the data set is checked for any missing or null values. If there's any, then they are either dropped or replaced with the mean or median as per analysis.

- We can see that of all the features, **Area** has maximum influence on the target variable i.e **price**.
- Then we analyse the categorical variables.

<img width = "400" src = "https://github.com/Dipankar-Medhi/House_Price_prediction/blob/main/property.jpg" > <img width = "450" src = "https://github.com/Dipankar-Medhi/House_Price_prediction/blob/main/categorical_features.jpg" >

- Then we remove the outliers.
- Visualizing the area feature using a boxplot.

<img width="500" src = "https://github.com/Dipankar-Medhi/House_Price_prediction/blob/main/area.jpg" >

### ⚡Feature engineering
- To select the fetures that influence the target variable,  corr() command is used to look into the relationship of the dependent variables with the target variable.
- And heatmap is used for proper visual representation.¶
![correlation](https://github.com/Dipankar-Medhi/House_Price_prediction/blob/main/heatmap.jpg)

### ⚡Data preprocessing
- The features that have the maximum influence on the target variable (price) are considered, and the rest all are dropped.
- Then the outliers are removed using the IQR(Interquantile Range) method. 
- The dataset is then scaled using StandardScaler.
- And dataset is split into train and test sets using the train_test_split method.

### ⚡Model training and evaluation
- Using sklearn to train the model on the training dataset and test on the test dataset.
- Metrics used: RMSE for evaluation of the model.






