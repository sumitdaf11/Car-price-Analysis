# Car Price Analysis

This project analyzes various car features and their impact on car prices using Python and data visualization techniques.
The analysis focuses on exploring relationships between features and price to find out which factors significantly affect the value of a car.

## Overview
The goal of this project is to identify key factors that affect car prices, such as engine size, horsepower, and drive wheel type, by performing Exploratory Data Analysis (EDA) and visualization.

## Dataset
- **Source:** [URL of Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/Data%20files/auto.csv)
- **Rows:** 205
- **Columns:** 26

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Data Cleaning:
- Handled missing values
- Converted categorical variables into appropriate formats
- Removed duplicates for consistency

## Exploratory Data Analysis
- **Regression Plots (regplot)** – To analyze linear relationships between price and numerical features.
- **Correlation** – To measure the strength of relationships between variables.
- **Box Plots** – To study price distribution across different categories.

## Project Insights: Factors Influencing Car Prices
Based on correlation analysis and visualizations:
- **Engine Size** – Larger engine size strongly increases price.
- **Horsepower** – Strong positive correlation with price.
- **Drive Wheel Type** – RWD cars tend to be more expensive.
- **highway-L/100** – Slight negative correlation with price.
