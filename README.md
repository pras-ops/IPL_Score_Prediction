# IPL_Score_Prediction
#   IPL Score Prediction using ML and TPOT Auto ML Library

This repository contains the code and analysis for predicting the final score of an IPL match using Machine Learning (ML) models and the TPOT Auto ML library.

## Project Overview

The Indian Premier League (IPL) is a popular cricket tournament that garners attention from cricket enthusiasts worldwide. This project aims to analyze IPL match data and predict the final score of a match given certain conditions. The project involves data cleaning, analysis, and comparison of different ML models. Additionally, it explores the usage of TPOT Auto ML library for automated model selection and optimization.

## Timeline

1.  Importing Libraries and DataSet
2.  Data Analysis and Cleaning
3.  Data Preprocessing
4.  Model Building using ML models
5.  Model Building and Predictions using Auto ML Library (TPOT)

## Installation

To run the code in this repository, you need to have the following dependencies installed:

-   pandas
-   numpy
-   seaborn
-   matplotlib
-   scikit-learn
-   tpot

You can install the required libraries using pip:

bashCopy code

`pip install pandas numpy seaborn matplotlib scikit-learn tpot` 

## Dataset

The dataset used in this project contains the following columns:

-   mid: The match id to uniquely identify each match.
-   date: The date on which the match was held.
-   venue: The name of the stadium.
-   bat_team: The batting team name.
-   bowl_team: The bowling team name.
-   batsman: The name of the batsman.
-   bowler: The name of the bowler.
-   runs: The runs scored till now.
-   wickets: The wickets taken till now.
-   overs: The number of overs bowled.
-   runs_last_5: The number of runs scored in the last 5 overs.
-   wickets_last_5: The number of wickets taken in the last 5 overs.
-   striker: The name of the batsmen on the batting end.
-   non-striker: The name of the batsmen on the bowling end.
-   total: The total number of runs scored in the match.

## Data Analysis and Cleaning

The data analysis and cleaning process involve the following steps:

1.  Removing unwanted columns from the dataset.
2.  Selecting popular teams for analysis.
3.  Removing the first 5 overs of each match.
4.  Converting the date column to a datetime object.

## Data Preprocessing

The data preprocessing steps include one-hot encoding for categorical variables and rearranging the columns for model input.

## Model Building using ML Models

In this project, the following ML models are used:

1.  Lasso Regression
2.  Random Forest Regression

Grid Search CV is employed for hyperparameter tuning of the Lasso Regression model.

## Model Building and Predictions using Auto ML Library (TPOT)

TPOT, a Python Automated Machine Learning tool, is used for optimizing machine learning pipelines using genetic programming. The TPOTRegressor class from TPOT library is utilized for this purpose.

## Please note that running TPOT Auto ML may take a significant amount of time.

## Conclusion

In conclusion, this project demonstrates the application of ML models and TPOT Auto ML library for IPL score prediction. The models built in this project can be further improved and fine-tuned to enhance their predictive capabilities. The findings and analysis provided here serve as a starting point for future research and exploration in this domain.
