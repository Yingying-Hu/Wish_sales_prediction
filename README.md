# Sales of Summer Clothes in E-commerce Wish
This repoitory contains code and associated files for building ML models to predict the product sales on Wish using AWS SageMaker.

## Data
The data is from an open dataset on Kaggle: https://www.kaggle.com/jmmvutu/summer-products-and-sales-in-ecommerce-wish/notebooks

## Software
- Python 3

## Python Libraries
- os
- pandas
- numpy
- sagemaker
- scipy
- sklearn
- xgboost
- collections 
- re
- matplotlib
- seaborn
- s3fs
- pickle
- tarfile

## Notebook Instruction
There are 5 notebooks, and their sequence is indicated by the number in their file names. 
- ```1_Data_Cleaning.ipynb```: Handle missing values and duplicated entries in the dataset. There's some work for data exploration as well. 
The result dataset is saved in ```data/wish_sales_clean.csv```
- ```2_Deep_Data_Exploration_and_Feature_Engineering.ipynb```: Deep exploratory data analysis, feature engineering and feature selection. 
The result dataset is saved in ```data/wish_sales_explore.csv```
- ```3_Modelling_Experiments.ipynb```: Scaling numerical features and build 3 expermential models, including RandomForest, XGBoost, and Neural Network. 
- ```4_XGBoost.ipynb```: Continue building the XGBoost by adding hyperparameter tuning. Select the model with the best performance and test the model's RMSE. 
- ```5_XGBoost_Final_Evaluation and_Validation.ipynb```: Check and interpret the features importance
