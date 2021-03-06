# Supervised Learning
A project space in which I explore Machine Learning concepts and algorithms related to **Regression** and **Classification** problems. In this space I explore
- Supervised Learning Algorithms
- Practical applications of Linear Regression with Maximum Liklihood and Bayesian Estimators
- Model Prediction Evaluation
- Bootstrapping
- Cross-Validation
- Classification Algorithms including: Bayesian Formulations, Logistic Regression, and kNN (k-nearest neighbors)
- Handling Incomplete Data
- Univariate/Bivariate Analysis
- Feature Engineering

## Product_Sales_Prediction.ipynb
In this project, I learn and explore the basics of **Regression Modeling**.  I begin with a large sales dataset and aim to train a model that can accurately predict sales on a testing dataset.  In this project I learn how to handle incomplete data by **imputing values for missing/null entries** and perform **Univariate/Bivariate Analysis** across all variables, both numerical and categorical.  I also start exploring the **Linear Regression** modeling process, involving *scaling data*, *feature engineering*, *feature selection*, *checking assumptions of linear models*, and *rebuilding the model* to fit the assumptions of linear models.  I then continue on to use the model that I have trained to find an accurate prediction on the testing data.

#### Test.csv / Train.csv
These contain the testing and training sales data (respectively) which are used to create and test the linear regression model.

## Loan_Eligibility_Classification.ipynb
In this project we explore a **Logisitic Regression** problem using **supervised machine learning techniques**. The objective of the project is to use the credit history of previous lenders to train a model using classification algorithms (such as **kNN**) to help the bank prevent potential losses, and focus more on eligible customers.

#### CreditRisk.csv
Contains credit risk information on prior customer loans to be used to train and test the model.

## Boston_House_Price_Prediction.ipynb
In this project I explore a **Linear Regression** problem using supervised machine learning techniques to predict the price of a house in a given town or suburb of Boston based upon features of the locality by using regression techniques.  Using the provided data set, I am able to find a relatively accurate regression function to predict a house's price based upon the dependent variables provided.

#### Boston.csv
This is the training/testing data set used to create the linear regression model for the Boston house price prediction.

## Effects_of_Advertising_on_Sales.ipynb
In this project, I explore both **Simple Linear Regression** and **Multiple Linear Regression** models and evaluate their performance. I also experiment with **Regularization** methods and **Bootstrap sampling** in an attempt to better fit the model. The data set used in the experiment looks into advertising data for ads run on different media and we seek to connect a linear combination of each feature to the sales for the company.

#### Advertising.csv
This is the file containing the advertising and sales data for the company in question.

## Predicting_Loan_Default.ipynb
In this project, I explore **Linear Discriminant Analysis** and **Logistic Regression** methods.  I also explore an implementation of a **k Nearest Neighbors** algorithm to classify the data points.

#### Default.csv
This is a dataset containing a small amount of data on individuals that have received loans and either have or have not defaulted.
