# Megaline Plan Recommendation

## Project Overview
This project develops a machine learning model for Megaline, a telecom company.  
The model analyzes user behavior and recommends the most suitable mobile plan: **Smart** or **Ultra**.

## Objective
Build a classification model that predicts the best plan for users with accuracy greater than **0.75**.

## Tools and Libraries
- Python
- pandas
- numpy
- matplotlib
- scikit-learn

## Project Workflow
1. Load and explore the dataset
2. Split the data into training, validation, and test sets
3. Train multiple machine learning models
4. Compare model performance
5. Select the best model
6. Evaluate the final model on the test set

## Results
The best performing model was **Random Forest**.

Model accuracy on the test set: **0.81**

This exceeds the required accuracy threshold of **0.75**.

## Project Structure

```
megaline-plan-recommendation
│
├── megaline_plan_recommendation.ipynb   # main machine learning notebook
├── users_behavior.csv                   # dataset
├── Project_Description.pdf              # assignment description
├── README.md                            # project documentation
├── LICENSE
└── .gitignore
```
