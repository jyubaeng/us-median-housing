# Predicting Median Housing Prices by State in the USA Using Machine Learning

## Overview

This project leverages machine learning techniques to predict median housing prices across different states in the USA over the next three years. The model utilizes various macroeconomic indicators such as interest rates, inflation, and unemployment rates to provide accurate forecasts. The aim is to assist real estate investors, policymakers, and financial institutions in making informed decisions by providing reliable predictions of housing market trends.

## Project Structure

1. Data
- data/: Contains all datasets used in the project.
  - cpi.xlsx: Consumer Price Index data.
  - fed_interest_rate.csv: Federal interest rates.
  - house_rental_index.csv: House rental index data.
  - house_value_index.csv: House value index data.
  - pop_unemployment.xlsx: Population and unemployment data.
  - data.csv: Joined and cleansed dataset combining all the above tables.
2. Code
- us-housing-price.ipynb: Jupyter notebook containing all the code for data wrangling, preprocessing, EDA, model training, and prediction.
3. Documentation
docs/: Contains all project documentation.
Predicting_USA_Median_Housing_Prices.pdf: The detailed white paper.
Presentation_Slides.pptx: PowerPoint presentation of the project.
Installation
Clone the repository

sh
Copy code
git clone https://github.com/yourusername/housing-price-prediction.git
cd housing-price-prediction
Create a virtual environment and install dependencies

sh
Copy code
python3 -m venv housing-price-venv
source housing-price-venv/bin/activate
pip install -r requirements.txt
Usage
Run the Jupyter Notebook

sh
Copy code
jupyter notebook us-housing-price.ipynb
This notebook includes:

Data wrangling and preprocessing
Exploratory Data Analysis (EDA)
Model training and evaluation
Predictions for future median housing prices
Project Highlights
Executive Summary
This project develops a machine learning model to predict median housing prices across US states, leveraging economic indicators, demographic data, and historical housing prices.

Business Problem
Predicting housing prices by focusing on macroeconomic indicators to help stakeholders make informed decisions.

Data Explanation
Sources: Consumer Price Index, Federal Reserve Economic Data, Zillow, public housing databases, U.S. Census Bureau.
Preparation: Handling missing values, scaling, and encoding.
Methods
Models Used: Linear Regression, Random Forest, XGBoost.
Evaluation Metrics: R-squared, MAE, RMSE.
Analysis and Results
Feature Importance: Key features include rent, CPI index, total population, interest rates, and inflation.
Model Performance: High accuracy with R-squared of 0.9988, MAE of 1817, and RMSE of 4093.
Future Work
Real-Time Analysis: Integrate with real-time data feeds.
Local Predictions: Extend to city or neighborhood levels.
Policy and Planning: Aid in sustainable development.
Ethical Considerations
Data Privacy: Ensure compliance with regulations.
Bias and Fairness: Regular audits to prevent bias.
Transparency: Use interpretable models.
Contributors
Your Name - your.email@example.com
License
This project is licensed under the MIT License - see the LICENSE file for details.