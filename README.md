# Data Scientist Salary Prediction – Machine Learning Final Project

This is the **final group project for the Machine Learning course** at BINUS University.  
Our objective is to build a reliable machine learning model to **predict data scientist salaries in USD** based on job-related and company attributes, using the [Data Science Salary 2021–2023 dataset](https://www.kaggle.com/datasets/harishkumardatalab/data-science-salary-2021-to-2023).

## Project Overview
Understanding factors that influence data scientist salaries is crucial in a rapidly evolving job market.  
However, accurate prediction is challenging due to varying roles, company sizes, locations, and remote work ratios.  
This project aims to create a robust salary prediction model and uncover the most important factors that drive salary differences.

![Demo](images/screenshot.png)

## Methodology
We followed a complete machine learning pipeline:
- **Problem & Data Understanding**: Analyzed features such as work year, experience level, employment type, job title, salary, employee residence, company location, remote ratio, and company size.
- **Feature Engineering**: Cleaned data by removing missing values and duplicates; applied ordinal encoding to `experience_level`, `employment_type`, and `company_size`.
- **Model Training**: Built a baseline Linear Regression model and a Random Forest Regressor.
- **Evaluation & Analysis**: Random Forest outperformed Linear Regression by capturing non-linear patterns, achieving lower prediction errors and higher R².

## Key Findings
- **Critical factors** influencing salaries include experience level, employment type, and company size.
- Remote work ratio and company location also significantly affect salary variation.
- Random Forest proved to be the best model for this prediction task.

## Team Members
- Renata Aqila R P
- Farren Angelica D
- Naira Faizanoor
- Vionita Lesia


This project demonstrates how machine learning can provide actionable insights into salary trends and help employers and professionals understand key compensation factors in the data science industry.
