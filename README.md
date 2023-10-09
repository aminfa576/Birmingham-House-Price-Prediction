# Birmingham House Prices Prediction Project

## Course Information
This project is a university assignment for the Data Science Programming module, which is part of the Data Analytics MSc course at Aston University. The objective is to predict house prices using various machine learning models. The dataset includes several features related to house properties and sales, which have been cleaned, preprocessed, and analyzed to build predictive models.
## Introduction
This project focuses on predicting house prices using various machine learning models. The dataset includes several features related to house properties and sales, which have been cleaned, preprocessed, and analyzed to build predictive models.

## Data Source
For this project, the dataset named ‘Prices.csv’ was utilized. This file contains the prices paid for all houses sold in Birmingham over a 25-year period from 1st January 1995 to 31st December 2019. The data was obtained from the UK Land Registry website [UK Land Registry](https://landregistry.data.gov.uk/app/ppd).


## Technologies Used
- Python
- Pandas
- Matplotlib
- Sklearn
- PyTorch

## Data
`Prices.csv` contains information on house sales, including features like property type, transaction type, address, price paid, and date of sale. The data has undergone several preprocessing steps:
- Removal of unnecessary columns.
- Transformation of categorical data into numerical values.
- Creation of new feature columns (e.g., numerical postcode, normalized price).
- Conversion of dates into numerical format representing days since January 1, 1995.

## Methods
- Data visualization to understand the distribution of sales for different property types, new builds, estate types, and transaction categories.
- Time series analysis to examine the sales trends of detached houses over time.
- Implementation of linear regression models using both Sklearn and PyTorch.
- Development and training of a multi-layer perceptron (MLP) with PyTorch to capture complex patterns in the data.

## Results
- The linear regression models provided moderate predictive performance with reasonable training and testing errors.
- The MLP demonstrated better performance, with lower testing errors, suggesting improved generalization to unseen data.

## Conclusion 
- The project successfully implemented and compared different models for house price prediction.
- The MLP showed promising results, outperforming simple linear regression models.
-

## Installation/Usage
Clone the repository and ensure you have the necessary Python packages installed (Pandas, Matplotlib, Sklearn, PyTorch).



