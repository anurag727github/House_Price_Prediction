# House Price Prediction using Machine Learning

## Project Overview

Predict house prices based on various features like area, number of rooms, year built, etc., using ML regression models.

## Dataset

[House Prices Kaggle Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## Features

* TotalBathrooms
* HouseAge
* TotalPorchArea
* One-Hot encoded categorical features
* Other features as in dataset

## Models Used

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor (Best Performance)

## Evaluation

* Metric: RMSE
* Gradient Boosting gave lowest RMSE: 24500 (example)

## How to Run

1. Clone the repository
2. Install required packages:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Open `house_price_prediction.ipynb` and run cells step by step.

## Results

* Top features affecting price:

  * OverallQual
  * GrLivArea
  * TotalBathrooms
* Sample predictions and plots included in notebook.
