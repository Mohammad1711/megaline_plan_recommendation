# Megaline Plan Recommendation

## Project Overview
This project develops a machine learning model for Megaline, a telecom company. 
The model analyzes user behavior and recommends the most suitable mobile plan: 
Smart or Ultra.

## Objective
Build a classification model with accuracy higher than 0.75.

## Dataset
The dataset contains monthly behavior information about users including:
- number of calls
- call duration in minutes
- number of messages
- internet usage (MB)

## Tools and Libraries
- Python
- pandas
- numpy
- matplotlib
- scikit-learn

## Project Workflow
1. Load and explore the dataset
2. Split the data into training, validation, and test sets
3. Train multiple models
4. Compare model performance
5. Select the best model
6. Test the final model

## Final Result
The Random Forest model achieved the best performance with accuracy around **0.81**, which exceeds the required threshold of **0.75**.

## Files in this Repository
- `megaline_plan_recommendation.ipynb` – main notebook
- `users_behavior.csv` – dataset
- `project_description.pdf` – assignment description
