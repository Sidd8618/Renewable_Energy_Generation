# Renewable Energy Generation Prediction

## Overview
This project predicts solar power generation using machine learning techniques. It analyzes historical power generation and weather data, engineers meaningful features, and compares multiple regression models to identify the best-performing approach.

## Features
Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Feature engineering from weather and time-based data
Training and evaluation of multiple ML models
Model performance comparison using RMSE, MAE, and R²
Cross-plant generalization testing
Feature importance analysis

## Datasets used 
Dataset: Solar Power Generation Data
Source: Kaggle - https://www.kaggle.com/datasets/anikannal/solar-power-generation-data
Plant_1_Generation_Data.csv       
Plant_1_Weather_Sensor_Data.csv    
Plant_2_Generation_Data.csv        
Plant_2_Weather_Sensor_Data.csv    

## Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
XGBoost

## Project Workflow
1. Load and preprocess the data.
2. Perform exploratory data analysis.
3. Create time-based and weather-related features.
4. Split the dataset into training and testing sets.
5. Train multiple machine learning models.
6. Compare model performance.
7. Test model generalization on another solar plant.
8. Analyze feature importance.

## Results
The ensemble model achieved the best prediction performance on the test dataset. Cross-plant evaluation highlighted the importance of plant-specific characteristics for accurate forecasting.

## Future Improvements
Deploy the model as a web application.
Add real-time weather data integration.
Improve cross-plant prediction using domain adaptation techniques.
Automate model retraining with new data.
