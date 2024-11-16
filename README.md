# DataMining
# Linear Regression - Mini-Project 1

## Project Overview

This project explores the application of linear regression to predict car prices using a dataset of historical car auction sales. The dataset contains information about various car features, including year, make, model, trim, body type, transmission, mileage, condition, and selling price.

## Dataset

The dataset used in this project is "car_prices.csv" and it contains historical car auction sales prices, scraped from external internet sources and collected in 2015. Each row represents a sale at a used car auction, with columns describing the car's features and sale price. A detailed description of each column can be found within the Jupyter Notebook.


## Project Workflow

1. **Data Inspection:** The project starts with data inspection to understand the dataset's structure, identify potential issues, and gain insights into the data.
2. **Data Pre-Processing & Cleaning:** Data cleaning and pre-processing steps are applied to handle missing values, correct data types, and prepare the data for modeling. This includes steps like:
    *   Removing rows with null values
    *   Changing data types to appropriate ones
    *   Data reduction
    *   One-hot encoding
    *   Normalization
    
3. **Exploratory Data Analysis:**  Visualizations and statistical analysis are used to explore the relationships between different variables and gain a deeper understanding of the data. This helps to answer questions like identifying the most popular car brands, determining the correlation between mileage and sale price, and examining the distribution of selling prices by car make.
4. **Data Preparation for Modeling:** Further data preparation steps, such as feature engineering and selection, are performed to prepare the data specifically for the linear regression model.
5. **Modeling:** The linear regression model is applied to the prepared data to learn the relationship between the car features and selling price.
6. **Model Evaluation & Validation:** The model's performance is evaluated and validated using metrics like Root Mean Squared Error (RMSE), R-squared (R²), Mean Absolute Percentage Error (MAPE), and Median Absolute Error (MAE). Diagnostic checks are performed to assess the model's assumptions.
7. **Conclusion and Recommendations:**  The project concludes with a discussion of the model's accuracy, findings, and recommendations for improvement. It also addresses any potential limitations and suggests possible solutions.
