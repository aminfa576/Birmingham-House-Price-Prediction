# Birmingham House Prices Prediction Project

## Course Information
This project was completed as part of the Data Science Programming course at [Your University]. It serves as a hands-on application of data science and machine learning concepts learned during the course.

## Introduction
This project focuses on predicting house prices using various machine learning models. The dataset includes several features related to house properties and sales, which have been cleaned, preprocessed, and analyzed to build predictive models.

## Data Source
The dataset used for this project, named `Prices.csv`, contains information on house prices paid for all houses sold in Birmingham over a 25-year period from 1st January 1995 to 31st December 2019. The data was obtained from the UK Land Registry website ([UK Land Registry](https://landregistry.data.gov.uk/app/ppd)) and is used for educational purposes in this project.

## Technologies Used
- Python
- Pandas: For data manipulation and analysis.
- Matplotlib: For creating static, animated, and interactive visualizations.
- Sklearn: For implementing machine learning algorithms.
- PyTorch: An open-source machine learning framework.

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

## Conclusion and Future Work
- The project successfully implemented and compared different models for house price prediction.
- The MLP showed promising results, outperforming simple linear regression models.
- Future work may involve experimenting with different neural network architectures, further hyperparameter tuning, and exploring other advanced modeling techniques.

## Installation/Usage
Clone the repository and ensure you have the necessary Python packages installed (Pandas, Matplotlib, Sklearn, PyTorch).

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

