# Medical Insurance Cost Analysis
## Overview

This project is an in-depth analysis of a simulated real-world dataset containing medical insurance info.

The goal of this project was to identify what variables contributed most to insurance charges. Using statistical analysis and regression modeling, I uncover relationships between demographics (age, sex, BMI, number of children, region, and smoking status) and insurance costs. 

This is a fundamental skill used by Data Analysts and Scientist who are working to model and predict trends in real-world data sets.

## Dataset Information

Source: [https://www.kaggle.com/datasets/mirichoi0218/insurance](https://www.kaggle.com/datasets/mirichoi0218/insurance)

Number of records: 1336 Rows

Variables includes:

1) age (int)
2) sex (binary string)
3) bmi (float)
4) children (int)
5) smoker (binary string)
6) region (categorical string)
7) charges (float - insurance cost in USD)

## Key Questions

What factors influence insurance charges? How do they influence charges? And can we model or predict those charges?

## Methodology

- Exploratory Data Analysis (EDA)
- Data Visualization (Seaborn and Matplotlib)
- T-tests and ANOVA
- Turkey's HSD Post-Hoc Tests
- Simple and Multiple Linear Regression (Ordinary Least Squares)
- Model comparison (R<sup>2</sup>, p-values, and F-statistic)

## Key Findings

- Smoking habit has the biggest effect on insurance charges.
- Age and BMI also contribute to insurance charges
- Region, number of children, and sex all show minimal impact.
- Using a multiple regression model with age, BMI, and smoking status we explain ~75% of the variance in insurance charges.

## How to run this code

1) Clone this repo
2) Make sure insurance.csv is in the root directory
3) Open us-medical-insurance-costs.ipynb in Jupyter Notebook
4) Run all cells sequentially

## About me
Created by Sky - an aspiring Data Analyst based in L.A.
Feel free to connect with me on [LinkedIn](www.linkedin.com/in/sky-nelson-5b480b241)!
