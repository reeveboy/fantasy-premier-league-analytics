# Using Machine Learning and Data Analytics to Predict Fantasy Premier League Points

*This repo is to store the code and dataset for the following project.*

Abstract: This paper investigates the potential of machine learning models to predict Fantasy Premier League (FPL) player points for each gameweek. We explore feature engineering techniques, data pre-processing steps, and compare the performance of various models including Linear Regression, Random Forest, XGBoost, and Neural Networks. The proposed models achieve a Root Mean Squared Error (RMSE) of around 1.97 and a Mean Absolute Error (MAE) of around 1.03, outperforming existing approaches found in the literature. These findings suggest that machine learning can be a valuable tool for informed decision-making in FPL.

The Dataset was initially collected from this repo:
Vaastav, “GitHub - vaastav/Fantasy-Premier-League: Creates a .csv file of all players in the English Player League with their respective team and total fantasy points,” GitHub. https://github.com/vaastav/Fantasy-Premier-League/tree/master

You can find all the datasets here: https://drive.google.com/drive/folders/1imsGjM61RuHRqVMnEZufwBQ49p8-BDqx?usp=sharing

Then data preprocessing steps like handling null values, and combining datasets were done.
- Check data_cleaning_&_preprocessing.ipynb file

The clean data was then utilized to create new features and make predictions.
- Check feature_engineering_&_modelling.ipynb file
