# car-price-prediction-spark
Predicting Car MSRP Using Spark

## Resources
Data: https://www.kaggle.com/CooperUnion/cardataset

## Installation
Upload the jupyter notebook to Google Colab to follow the notebook's Spark installation. If Spark is available on your local machine, the notebook can be executed locally without re-installing Spark

## Steps
The goal of the project is to build a Spark pipeline that trains a random forest regression model. The best model is then selected and evaluated using cross-validation and grid search.

The notebook executes the following steps:
1 - Install Spark, load required libraries, set environment variables, initiate Spark, load file
2 - Explore/Clean the data
3 - Build the VectorAssembler and RandomForestRegressor pipeline
4 - Perform hyperparameter search and cross-validation
5 - Select the best model and output evaluation metrics


