# Optimize Pricing Predictions with Feature Engineering
## Overview
This project develops and refines a multiple linear regression model to estimate used car prices based on various features. Originally using 17 predictors, the goal was to simplify the model by reducing the number of features while maintaining similar performance, measured by R^2 and RMSE. The analysis explores feature selection, transformation, and model evaluation to optimize performance and efficiency.

This project was completed as part of a DataCamp R project to enhance proficiency in data wrangling, modeling, and evaluation using the tidymodels framework.(https://app.datacamp.com/learn/projects/2169)

## Project Objectives
- Build a baseline multiple linear regression model using all 17 features.
- Reduce feature count to 10 or fewer by removing low-importance variables.
- Transform and engineer features to improve model performance.
- Compare baseline and optimized model performance using R^2 and RMSE.

## Technologies Used
- R
- tidyverse
- tidymodels
- vip
- broom

## Files Included
- car_price_prediction.Rmd – Main R Markdown file with code, analysis, and outputs.
- README.md – Project overview and instructions.
- train.csv – Training dataset with 2005 model year GM cars and associated features.
- test.csv – Test dataset to evaluate model performance.

## How to Run
- Clone the repository.
- Open car_price_prediction.Rmd in RStudio.
- Knit the file to HTML or run all chunks to reproduce the analysis and visualizations.

## Results Summary
- Baseline Model Performance --> R^2 = 0.9135, RMSE = 2693.56
- Enhanced Model Performance --> R^2 = 0.9164, RMSE = 2658.87
- Final Retained Features --> Efficiency, Cylinder, Doors, Cadillac, Saab, convertible, hatchback, sedan
The optimized model used fewer features while achieving slightly better performance, demonstrating that a simpler, faster, and more efficient model can still yield accurate price predictions.
