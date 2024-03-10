# Capstone-Project-Salifort-motor

## Table of Contents
1. Overview
2. Methodology
3. Dataset
4. Model
5. Deliverables
6. Ethical Considerations
7. Required Packages
8. Useful Links

## Overview
The goal of this project is to answer the question "What is likely to make employees leave the company?". This is a critical question for businesses as employee turnover can be costly and disruptive.

## Methodology
The project involves several steps:
1. **Data Cleaning**: The first step in any data analysis project is to clean and preprocess the data.
2. **Exploratory Data Analysis (EDA)**: This involves understanding the distribution of the data, the correlation between different features, and identifying potential outliers.
3. **Data Visualization**: Visualizations are created to understand the data better and to find insights.
4. **Model Building**: A machine learning model is built to predict whether an employee will leave.
5. **Model Evaluation**: The model's performance is evaluated using appropriate metrics.
6. **Insights & Recommendations**: Based on the model's findings, insights are derived and recommendations are made.

## Dataset
The dataset used for this project is publicly available on Kaggle. It contains several features that are believed to be important in predicting employee turnover, such as salary, satisfaction level, number of projects, average monthly hours, time spent at the company, whether they have had a work accident, whether they have had a promotion in the last 5 years, departments, and salary.

## Model
An XGBoost model was used to predict whether an employee would leave. XGBoost is a decision-tree-based ensemble Machine Learning algorithm that uses a gradient-boosting framework. It is known for its performance and speed, which makes it a good choice for this project.

## Deliverables
The deliverables for this project include:
1. The completed Jupyter notebook that contains all the code.
2. An executive summary that explains the findings in a non-technical language.
3. The model that was built, is saved in a format that can be loaded later.

## Ethical Considerations
Throughout the project, ethical concerns were considered. One of the main concerns is that we are building a model that will be used to make decisions that will impact employees. It is important to ensure that the model is fair and does not discriminate against any group of employees.

## Required Packages
To run the Jupyter Notebook, you will need the following packages:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- pickle

