# Student Performance Prediction
## Overview
This project aims to predict student performance ( Passed or Failed) based on various features such as Study hours, Attendance Rate, Previous Grades, Parental Education Level.

The process involves data preprocessing, data analysis, visualization, feature engineering, model training and evaluation using 2 models: Logistic Regresison and Random Forest.

## Project structure:
- `Data\`: directory contains dataset (student_performance_prediction.csv)
- `main.ipynb`: jupyter notebook to process data and evaluate performance
- `readme.md`: project overview and set up instruction

## Dataset
The dataset used in this project contains the following columns:
- `Study Hours per Week`: The number of hours a student studies per week.
- `Attendance Rate`: The student's attendance rate.
- `Previous Grades`: The student's grades in previous terms.
- `Participation in Extracurricular Activities`: Indicates whether the student participates in extracurricular activities (Yes/No).
- `Parent Education Level`: The education level of the student's parents.
- `Passed`: The target variable indicating whether the student passed or failed.

## Set up environment:
```bash 
python3 -m venv/polars_env
source ./polars_env/bin/activate
pip install jupyter notebook
```
## Results:
After tuning the hyperparameters, the performance metrics for the Logistic Regression model are as follows:

- Accuracy: 50%
- Precision: 51%
- Recall: 44%
- F1 Score: 47%
