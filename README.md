# Diabetes – Data Analysis

A **Exploratory Data Analysis (EDA) project** implemented in **Python**, focusing on understanding diabetes outcomes and analyzing key health features such as age, BMI, glucose levels, blood pressure, and their correlations.

---

## Overview
This project implements an **Exploratory Data Analysis (EDA)** on a diabetes dataset to identify patterns, distributions, and relationships among clinical features.  
The analysis aims to understand how different health indicators vary between diabetic and non-diabetic individuals.  
A structured EDA workflow is followed to generate insights using Python data analysis and visualization libraries.

---

## Core Features
- Counting and comparison of diabetes outcomes  
- Distribution analysis of age, BMI, glucose, and blood pressure  
- Feature-wise comparison by diabetes outcome  
- Correlation analysis between features and diabetes outcome  
- Visualization of key trends and relationships  
- Extraction of meaningful insights

---

## Technology Stack
- **Language:** Python  
- **Libraries Used:** NumPy, Pandas, Matplotlib, Seaborn  
- **Execution Environment:** Jupyter Notebook    

---

## Application Mechanics
- Data is loaded and cleaned using **Pandas DataFrames**  
- Numerical and statistical analysis is performed using **NumPy**  
- Distribution plots and comparison charts are created using Matplotlib and Seaborn  
- Grouping and filtering are applied to compare diabetic and non-diabetic cases  
- Correlation analysis is used to measure relationships between features  
- The analysis answers the following questions:
  - Count of diabetic vs non-diabetic outcomes  
  - Distribution of age, BMI, glucose, and blood pressure  
  - Feature distributions by diabetes outcome  
  - Correlation between features and the diabetes outcome  

---

## Key Insights
- The dataset contains more non-diabetic cases than diabetic cases  
- Age and BMI distributions are right-skewed, with most individuals in younger to middle-age and overweight ranges  
- Diabetic individuals generally exhibit higher glucose levels than non-diabetic individuals  
- Blood pressure shows a slight increase in median values for diabetic individuals  
- Glucose has the strongest positive correlation with diabetes outcome, followed by BMI and insulin  

---

## Dataset Information
- **Dataset Name:** Diabetes  
- **Source:** Kaggle  

---

## Project Structure

- **diabetes-data-analysis/**  
  - `Diabetes_EDA.ipynb` → Jupyter Notebook containing the complete EDA  
  - `diabetes.csv` → Dataset used for analysis  
  - `README.md` → Project documentation  
