# CO2 Emissions Prediction using Random Forest Regressor

## Overview

This project utilizes machine learning to predict CO2 emissions based on various factors such as country life expectancy, energy consumption, and other relevant features. A **Random Forest Regressor** model is applied to the dataset to predict the amount of CO2 emissions in different countries. The dataset includes multiple features that can influence CO2 emissions, and the model is trained to predict CO2 emissions based on these features.

## Requirements

Ensure the following Python libraries are installed to run the code:

- `pandas`: For data manipulation and analysis.
- `scikit-learn`: For machine learning models and metrics.
- `numpy`: For numerical computations.

# Dataset
The dataset used, CO2Emission_LifeExp.csv, includes the following columns:

Code: Country code (which is dropped for prediction).
Country: Country name (also dropped for prediction).
CO2Emissions: The target variable representing CO2 emissions.
Other Features: Various socio-economic and environmental factors such as energy consumption, life expectancy, etc.
Project Steps
# Data Loading and Preprocessing:
The data is loaded from a CSV file.
Irrelevant columns (Code and Country) are dropped as they are not needed for prediction.
Missing values are removed to ensure clean data for training.
# Data Splitting:
The data is split into training and testing sets using an 80/20 split.
# Model Training:
A Random Forest Regressor model is trained using the preprocessed training data to predict the CO2 emissions target variable.
Model Prediction and Evaluation:
The model makes predictions on the test data, and its performance is evaluated using the R-squared score, which shows how well the model explains the variance in CO2 emissions.
# Output
The model's performance is measured using the R-squared score, which indicates how well the model can predict CO2 emissions. A score closer to 1 suggests that the model is performing well in explaining the variance in the target variable.
