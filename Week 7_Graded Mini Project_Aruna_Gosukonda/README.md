
# Employee attrition prediction project

## Problem Statement
This project predicts employee attrition using machine learning models to help HR teams identify employees at risk of leaving the organization.

## How to Run
- 1. Install dependencies: 
- ```bash
- pip install -r requirements.txt
- 2. Open `Employee_Attrition_Prediction_SupervisedLearning.ipynb` and run all cells sequentially.

## Dataset
WA_Fn-UseC_-HR-Employee-Attrition.csv

## Workflow
- Data Loading & Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Preprocessing (Encoding, Scaling)
- Model Training & Selection
- Evaluation using multiple metrics

## Models USed

- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting (if used)

Best model is selected based on ROC-AUC, F1, Recall score.

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

## Output
- `model.pkl`: Trained model
- `model_report.csv`: Model summary
- `cleaned_employee_attrition.csv`: Cleaned data set

