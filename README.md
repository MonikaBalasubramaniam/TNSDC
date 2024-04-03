# House Price Prediction using California Housing Dataset

This project aims to predict house prices based on various features using the California Housing dataset available in scikit-learn. The project involves data analysis, machine learning model training, and creating endpoints for fetching dataset statistics and predicting house prices.

## Project Overview
The project follows the following steps:

## Import Libraries: 
Import necessary libraries such as `pandas`,` numpy`, and `scikit-learn` for data manipulation, analysis, and machine learning model implementation.

## Dataset Import: 
Fetch the California Housing dataset from scikit-learn and split it into training and testing sets.

## Data Analysis:
Analyze the dataset to understand its structure, features, and correlations between variables. Compute basic statistics and correlations.

## GET Endpoint:
Create an endpoint to fetch basic statistics about the dataset, such as total number of houses, maximum and minimum prices, and most important feature affecting house prices.


## Machine Learning: 
Train a machine learning model using RandomForestRegressor to predict house prices based on the input features.

## POST Endpoint:
Create an endpoint to accept user input features and return the predicted house price using the trained model.

## Files Included
house_price_prediction.ipynb: Jupyter Notebook containing the code for data analysis, model training, and endpoint creation.
README.md: Markdown file explaining the project overview, steps, and usage instructions.
requirements.txt: File listing all dependencies required to run the project.

## Setup and Usage Instructions
Install the required dependencies listed in requirements.txt using pip:

Copy code
`pip install -r requirements.txt`
Open and run `house_price_prediction.ipynb` in Jupyter Notebook or Jupyter Lab.

Follow the instructions in the notebook to analyze the dataset, train the machine learning model, and set up the GET and POST endpoints.

Test the GET and POST endpoints using tools like Postman or by making HTTP requests.
## References
California Housing dataset:` scikit-learn` documentation

RandomForestRegressor: `scikit-learn` documentation
