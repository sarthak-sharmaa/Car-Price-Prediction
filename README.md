# Car Price Prediction Using Machine Learning

## Overview
This project predicts the selling price of used cars based on features such as fuel type, transmission type, kilometers driven, and more. The goal is to help users estimate the price of a car based on various parameters using machine learning models.

The model is built using **Linear Regression**, and the dataset is preprocessed to handle categorical variables. The performance of the model is evaluated using R-squared error, and visualizations are provided to compare actual prices with predicted values.

## Dataset
The dataset used in this project contains the following columns:
- `Car_Name`: Name of the car.
- `Year`: The year the car was purchased.
- `Present_Price`: Current ex-showroom price of the car (in lakhs).
- `Kms_Driven`: Number of kilometers the car has driven.
- `Fuel_Type`: Type of fuel used by the car (Petrol/Diesel/CNG).
- `Seller_Type`: Whether the seller is a dealer or an individual.
- `Transmission`: Transmission type (Manual/Automatic).
- `Owner`: Number of previous owners of the car.
- `Selling_Price`: The price at which the car is being sold (target variable).

The dataset was sourced from a CSV file and is included in the `data/` folder.
