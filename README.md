# Predicting California Housing Prices using Classical Machine Learning Models

## Description

This project aims to predict the median house value for California districts using various classical machine learning regression techniques. It involves exploring the dataset, preprocessing the data, training multiple models, evaluating their performance using standard regression metrics, and comparing the results to identify the most effective algorithms for this task.

**Goal:** To build and evaluate regression models for predicting housing prices and compare the performance of Linear Regression, Ridge, Lasso, Decision Trees, Random Forest, and XGBoost.

## Dataset

The project utilizes the **California Housing dataset**, available through Scikit-learn.

* **Source:** Derived from the 1990 U.S. census data.
* **Instances:** 20,640
* **Features:** 8 numerical/continuous features:
    * `MedInc`: Median income in block group (in tens of thousands of US Dollars)
    * `HouseAge`: Median house age in block group
    * `AveRooms`: Average number of rooms per household
    * `AveBedrms`: Average number of bedrooms per household
    * `Population`: Block group population
    * `AveOccup`: Average number of household members
    * `Latitude`: Block group latitude
    * `Longitude`: Block group longitude
* **Target:** `MedHouseVal`: Median house value for California districts (in hundreds of thousands of US Dollars - $100,000s).
