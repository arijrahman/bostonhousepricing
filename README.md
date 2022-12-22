# Boston House Price Prediction
![house_pricing](https://user-images.githubusercontent.com/42798629/209130132-6503a213-800b-4de3-8e35-4e1f9bd6454c.png)



Introduction project is based on the boston dataset. The data to be analyzed were collected by Harrison and Rubinfeld in 1978 for the purpose of discovering whether or not clean air influenced the value of houses in Boston. Their results are documented in a paper titled Hedonic prices and the demand for clean air, published in J. Environ. Economics and Management 5, 81-102.

# Overview
This report seeks to examine the influence of several neighborhood attributes on the prices of housing, in an attempt to discover the most suitable explanatory variables. The specific neighborhood attributes to be considered are proximity to the Charles River, distance to the main employment centers, pupil-teacher ratio in schools, and levels of crime. Whereas the original study focused on air pollution using nitrogen oxide concentrations as an explanatory variable, this report examines whether or not there are other, better explanatory variables for the median value of houses in Boston. The R programming language will be used to conduct this analysis.

# Data
The dataset (Boston Housing Price) was taken from the StatLib library which is maintained at Carnegie Mellon University and is freely available for download from the UCI Machine Learning Repository. The dataset consists of 506 observations of 14 attributes. The median value of house price in $1000s, denoted by MEDV, is the outcome or the dependent variable in our model. Below is a brief description of each feature and the outcome in our dataset:

CRIM – per capita crime rate by town
ZN – proportion of residential land zoned for lots over 25,000 sq.ft
INDUS – proportion of non-retail business acres per town
CHAS – Charles River dummy variable (1 if tract bounds river; else 0)
NOX – nitric oxides concentration (parts per 10 million)
RM – average number of rooms per dwelling
AGE – proportion of owner-occupied units built prior to 1940
DIS – weighted distances to five Boston employment centres
RAD – index of accessibility to radial highways
TAX – full-value property-tax rate per $10,000
PT – pupil-teacher ratio by town
B – 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT – % lower status of the population
MV – Median value of owner-occupied homes in $1000’s
# Objective
The prime objective of this project is to construct a working model which has the capability of predicting the value of houses, make an application of the same and deploy it using HEROKU as CONTAINER.
# Softwares and Tools Requirements
GithubAccount
HerokuAccount
VSCodeIDe
GitCLI
Create a New Environment
/// conda create -p venv python==3.7 -y ///
# Result
Succesfully built the app and deployed the same.
Link for the Application
https://bostonhouse-price-prediction.herokuapp.com/

# NOTE
Check the MASTER branch for notebook,flask app code.
