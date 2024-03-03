# Superstore Analysis

This repository contains a Python script for analyzing Walmart store sales data. The script utilizes various data visualization techniques to explore sales trends, identify key insights, and build predictive models.

## Features

- **Data Loading**: Load Walmart store sales data from a CSV file using pandas.
- **Data Preprocessing**: Preprocess the data by converting date columns to datetime format, handling missing values, and splitting date components.
- **Exploratory Data Analysis (EDA)**: Explore the dataset through visualizations to understand sales trends, store performance, and seasonal patterns.
- **Feature Engineering**: Create new features such as day, month, and year from the date column.
- **Visualization**: Utilize seaborn and matplotlib to create insightful visualizations including bar plots, scatter plots, and box plots.
- **Outlier Detection**: Identify and handle outliers in the dataset using box plots.
- **Model Building**: Build predictive models using linear regression and random forest regressor to forecast weekly sales.
- **Model Evaluation**: Evaluate model performance using metrics such as mean absolute error, mean squared error, and root mean squared error.
- **Interactive Plots**: Visualize the model predictions using interactive scatter plots.

## Dataset 
The dataset has been downloaded from https://www.kaggle.com/datasets/aditya6196/retail-analysis-with-walmart-data

## Requirements

- Python 3.x
- pandas
- seaborn
- numpy
- matplotlib
- scikit-learn
