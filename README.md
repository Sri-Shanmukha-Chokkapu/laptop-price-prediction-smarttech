# Laptop Price Prediction for SmartTech Co.

## Project Type
Client-style machine learning capstone project

## Problem Statement
SmartTech Co. wants to estimate laptop prices based on specifications such as brand, processor, RAM, storage, GPU, operating system, screen features, and weight.

## Business Objective
The goal is to support pricing decisions, understand feature influence, and identify how brand and specifications affect laptop prices.

## Dataset
Rows: 1,303  
Columns: 13  
Target: Laptop price  
Source: OdinSchool capstone dataset

## Tools Used
Python, Pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

## Workflow
1. Data cleaning
2. Exploratory data analysis
3. Feature engineering
4. Encoding categorical variables
5. Model training
6. Model comparison
7. Error analysis
8. Feature importance analysis

## Models Compared
Linear Regression  
KNN Regression  
Decision Tree Regression  
SVR Regression  
Random Forest Regression

## Result
Random Forest performed best with an R2 score of approximately 0.88 on the test set.

## Key Insights
Brand, RAM, storage type, CPU category, GPU category, and laptop type were important factors influencing price.

## Limitations
The model depends on the dataset quality and may require retraining for newly released laptops or changing market conditions.

## Future Improvements
Add real-time prediction interface, deploy with Streamlit, add SHAP analysis, and update dataset with newer laptop models.
