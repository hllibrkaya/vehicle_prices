# Vehicle Prices Prediction

## Overview
This project aims to predict vehicle prices using the provided dataset. Selected dataset contains **13** features related to a car
such as _name_, _year_, _milage_, _fuel type_ etc.


## Project Structure


- **[vehicle_prices.ipynb](vehicle_prices.ipynb)**: The Jupyter Notebook file where the data is processed, prediction model is built, optimized, evaluated 
- **[Car Price Predictions.pdf](Car%20Price%20Predictions.pdf)**: The presentation file explaining the project and its results
- **[explanation.html](explanation.html)**: Feature importance analysis with XAI for a sample
- **[Dataset](dataset/Car%20details%20v3.csv)**: Dataset used for predictions.

## Project Stages

- Data Preprocessing (Handling Missing Values, Type conversions with *regex*, Scaling etc.)
- Feature Engineering (New features created from data and also with the help of little domain knowledge)
- Explanatory Data Analysis and Visualizations
- Feature Selection
- Model Selection and Automated Hyper-Parameter Optimization (_A Voting Model Created_)
- Performance Evaluation
- Feature Importance Observation via *XAI* (LIME Library used)

## Model Evaluation

| Metric                  | Value          |
|-------------------------|----------------|
| **R²**                  | 0.90           |
| **MAPE**                | 15             |
| **MAE**                 | 58.307         |
| **Confidence Interval (95%)** | 76.341 - 98.524 |


