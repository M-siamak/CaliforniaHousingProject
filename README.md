# California Housing Price Prediction

This repository contains a Jupyter notebook that demonstrates how to predict housing prices in California using the **California Housing dataset**. The notebook performs **data preprocessing**, trains a **Linear Regression** model and **ElasticNet**, and evaluates the models' performance.

## Overview

The notebook covers the following steps:
1. **Loading the Dataset**: The **California Housing dataset** is loaded using **Scikit-learn's `fetch_california_housing`** function.
2. **Data Preprocessing**:
   - Splitting the data into training and test sets using **train_test_split**.
   - Feature scaling using **StandardScaler**.
3. **Training the Models**:
   - **Linear Regression**: A basic regression model is trained to predict housing prices.
   - **ElasticNet**: A regularized regression model that combines both Lasso and Ridge regression.
4. **Model Evaluation**:
   - The models' performance is evaluated using the **R² score** and **MSE**.

## Files in this Repository

- **`california_housing_regression.ipynb`**: The main Jupyter notebook where the **California Housing dataset** is loaded, preprocessed, and regression models are trained and evaluated.

## Features

- **California Housing Dataset**: Contains features like `MedInc`, `HouseAge`, `AveRooms`, and `AveOccup` for predicting housing prices in California.
- **Linear Regression & ElasticNet**: Implements basic regression models for price prediction.
- **Data Preprocessing**: Standardization and splitting of data into training and testing sets.
- **Model Evaluation**: Evaluate models using **R² score** and **Mean Squared Error (MSE)**.

## Requirements

To run this notebook, you will need the following Python libraries:
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**

You can install them using `pip`:

```bash
pip install pandas numpy scikit-learn matplotlib
