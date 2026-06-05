# House sales price prediction project

## Problem Statement
This project predicts house sales price using machine learning models to help users identify key factors influencing the sales price.

## How to Run
- 1. Install dependencies: 
- ```bash
- pip install -r requirements.txt
- 2. Open `House_Sales_Price_Analysis.ipynb` and run all cells sequentially.

## Dataset
Week 9_Graded Mini Project_Dataset_houseprice.csv

## Workflow
- Data Loading & Cleaning & Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Visual Engineering
- Model Training & Selection
- Evaluation using multiple metrics
- Saving the model to pickle file
- Report Generation
- Key factors Analysing

## Models USed

- XGBoost
- LightGBM
- CatBoost

Best model is selected based on R2 score.

## Evaluation Metrics

- MAE
- RMSE
- R2 Score

## Output
- `house_price_best_model.pkl`: Trained model
- `cleaned_house_prices.csv`: Cleaned data set