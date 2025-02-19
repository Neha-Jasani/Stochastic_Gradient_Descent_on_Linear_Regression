# Stochastic Gradient Descent on Linear Regression

## Overview

This project applies Stochastic Gradient Descent (SGD) to predict gym crowdedness based on historical data. The dataset contains various features such as date, time, temperature, and semester status, which help determine the number of people at the gym. By leveraging linear regression with SGD, the model aims to provide insights into the best times to visit the gym with minimal crowding.

## Project Objectives

* Load and preprocess the "Crowdedness at the Campus Gym" dataset.
* Perform exploratory data analysis (EDA) to understand patterns and trends.
* Train an SGD-based linear regression model to predict gym occupancy.
* Evaluate model performance using key regression metrics.
* Visualize results to derive insights for gym-goers.

## Key Features

* **Data Preprocessing:** Handled missing values, converted categorical data, and normalized numerical features.
* **Exploratory Data Analysis:** Used visualizations to understand the distribution and impact of different variables on gym occupancy.
* **Model Training:** Implemented a linear regression model with Stochastic Gradient Descent using SGDRegressor from Scikit-learn.
* **Performance Evaluation:** Measured model accuracy using RMSE, MAE, and R-squared.
* **Data Visualization:** Created graphs to illustrate trends and insights from the model predictions.

## Tools & Technologies Used

* **Python** for data analysis and machine learning
* **Pandas & NumPy** for data manipulation
* **Scikit-Learn** for implementing the SGD-based regression model
* **Matplotlib & Seaborn** for data visualization

## Results & Insights

* Identified key factors influencing gym crowdedness, such as time of day, day of the week, and semester status.
* Demonstrated the effectiveness of Stochastic Gradient Descent in handling large datasets efficiently.
* Provided actionable insights for gym-goers to avoid peak hours and plan their workouts better.
