# MEDICAL INSURANCE COST ANALYSIS & PREDICTION SYSTEM

## Project Overview

The **Medical Insurance Cost Analysis & Prediction System** is a data analytics and machine learning project developed using a real-world healthcare insurance dataset obtained from Kaggle. The project focuses on understanding the factors that influence medical insurance charges and building predictive models that help estimate insurance costs accurately.

By combining **Exploratory Data Analysis (EDA)**, **Regression Models**, **Classification Techniques**, and **Interactive Dashboard Visualizations**, this system provides valuable insights for insurance companies to improve premium estimation, customer risk assessment, and business decision-making.

---

## Problem Statement

Insurance providers manage large volumes of customer information, including age, gender, BMI, number of dependents, smoking habits, geographical region, and medical expenses. Analyzing these factors manually is inefficient and may lead to inaccurate premium calculations and poor risk management.

Common challenges include:

* Inaccurate insurance premium estimation
* Difficulty identifying high-risk customers
* Increased financial risk for insurance providers
* Inefficient policy planning and decision-making
* Lack of data-driven insights into healthcare costs

This project addresses these challenges by implementing automated analysis and predictive modeling techniques to estimate insurance charges and classify customers based on risk levels.

---

## Dataset Information

**Dataset Name:** Medical Cost Personal Dataset

**Source:** Kaggle

**Dataset Link:**
https://www.kaggle.com/datasets/mirichoi0218/insurance

### Dataset Features

| Feature  | Description                  |
| -------- | ---------------------------- |
| age      | Age of the customer          |
| sex      | Gender of the customer       |
| bmi      | Body Mass Index              |
| children | Number of dependents covered |
| smoker   | Smoking status               |
| region   | Residential region           |
| charges  | Medical insurance charges    |

---

## Project Objectives

The primary objective of this project is to analyze insurance customer data and build predictive models that can estimate insurance charges and classify customer risk categories.

### Key Goals

* Analyze customer demographics and insurance costs
* Identify major factors affecting medical insurance charges
* Perform comprehensive Exploratory Data Analysis
* Build Simple Linear Regression models
* Develop Multiple Linear Regression models
* Implement Logistic Regression for customer classification
* Perform customer risk segmentation
* Create interactive visual dashboards
* Generate actionable business insights

---

## Technologies Used

### Programming Language

* Python

### Libraries & Frameworks

#### Data Analysis

* Pandas
* NumPy

#### Data Visualization

* Matplotlib
* Seaborn
* Plotly

#### Machine Learning

* Scikit-Learn

---

## Project Workflow

### 1. Data Collection

* Load insurance dataset from Kaggle
* Understand dataset structure
* Explore available features
* Identify target and predictor variables

### 2. Data Cleaning & Preprocessing

* Missing value detection
* Duplicate record removal
* Data type verification
* Label encoding of categorical variables
* Feature transformation

### 3. Exploratory Data Analysis

Detailed analysis performed on:

* Customer age distribution
* BMI distribution
* Insurance charge distribution
* Smoking habits
* Gender demographics
* Regional customer distribution

### 4. Insurance Cost Analysis

Comparison of insurance charges across:

* Smokers vs Non-Smokers
* Male vs Female customers
* Different age groups
* BMI categories
* Regions
* Number of children

### 5. Relationship Analysis

Investigation of relationships between:

* Age and Charges
* BMI and Charges
* Children and Charges
* Smoking Status and Charges
* Demographic Factors and Premium Costs

---

## Data Visualization

The project includes multiple visualization techniques such as:

### Histograms

* Age Distribution
<img width="521" height="346" alt="image" src="https://github.com/user-attachments/assets/8ac83168-f7f8-49c5-aa34-cbe07d6fc615" />

* BMI Distribution
<img width="508" height="351" alt="image" src="https://github.com/user-attachments/assets/7a41e825-1155-40a4-ad90-30c91da12b0c" />

* Insurance Charges Distribution
<img width="510" height="344" alt="image" src="https://github.com/user-attachments/assets/fed3a708-fedc-4ddf-8c6e-bf0da72b7b95" />


### Scatter Plots

* Age vs Charges
<img width="538" height="337" alt="image" src="https://github.com/user-attachments/assets/d26f1433-45ff-41f0-98a4-8721107bc7cc" />

* BMI vs Charges
<img width="532" height="343" alt="image" src="https://github.com/user-attachments/assets/daa57270-b1d2-42c5-8801-c4d85718d908" />


### Box Plots

* Gender vs Charges
<img width="532" height="349" alt="image" src="https://github.com/user-attachments/assets/f06eb17d-3f84-47b0-b12e-acd399ca1741" />

* Smoker vs Charges
<img width="532" height="338" alt="image" src="https://github.com/user-attachments/assets/58cd2f1b-eb4d-4ae4-b84e-4afcd8ccdf27" />


### Pie Charts

* Gender Distribution
<img width="290" height="296" alt="image" src="https://github.com/user-attachments/assets/c902eb22-3f22-4f57-9a41-d7b5c687db90" />

* Smoking Status Distribution
<img width="294" height="307" alt="image" src="https://github.com/user-attachments/assets/1c67f3cf-9722-421a-b06c-4fa64c93ed39" />


### Heatmaps

* Correlation Analysis
<img width="567" height="399" alt="image" src="https://github.com/user-attachments/assets/fdfe62ae-b305-459b-92b6-d51cedb47825" />


### Bar Charts

* Region-wise Average Charges
* Smoker-wise Average Charges

---

## Risk Analysis

Customers are categorized into risk groups based on insurance charges:

### Low Risk Customers

Customers with lower medical insurance expenses.

### Medium Risk Customers

Customers with moderate insurance expenses.

### High Risk Customers

Customers likely to generate higher medical claims and healthcare costs.

This classification helps insurance providers identify customers requiring special premium planning and risk management strategies.

---

# Machine Learning Models

## Simple Linear Regression

### Objective

Predict insurance charges using a single predictor variable.

### Input Variable

* Age

### Target Variable

* Insurance Charges

### Process

* Data splitting
* Model training
* Prediction generation
* Performance evaluation

### Evaluation Metrics

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

## Multiple Linear Regression

### Objective

Predict insurance charges using multiple influencing factors.

### Input Variables

* Age
* BMI
* Number of Children
* Smoking Status

### Target Variable

* Insurance Charges

### Process

* Feature encoding
* Data splitting
* Model training
* Prediction
* Performance comparison

### Evaluation Metrics

* R² Score
* MAE
* MSE
* RMSE

---

## Logistic Regression

### Objective

Classify customers as High-Cost or Low-Cost policyholders.

### Target Variable

Insurance Category

* 0 → Low Cost Customer
* 1 → High Cost Customer

### Input Variables

* Age
* BMI
* Number of Children
* Smoking Status

### Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

## Interactive Dashboard

An interactive dashboard is created using Plotly to provide real-time visual exploration of insurance data.

### Dashboard Components

* Insurance Charges Distribution
* Age vs Charges Analysis
* BMI vs Charges Analysis
* Smoker Cost Comparison
* Region-wise Insurance Charges
* Gender-wise Insurance Charges
* Correlation Heatmap
* Risk Category Distribution
  

### Interactive Filters

* Age Filter
* Gender Filter
* Region Filter
* Smoking Status Filter
* Children Count Filter

<img width="1815" height="502" alt="image" src="https://github.com/user-attachments/assets/86fd987d-7fa4-4318-bda1-647eddc02b79" />


<img width="1818" height="268" alt="image" src="https://github.com/user-attachments/assets/ddc95cbf-66ca-4a9e-bd6f-d19c0ae1905d" />


---

## Project Outcomes

The project successfully:

* Identifies key drivers of insurance costs
* Evaluates the impact of smoking on medical expenses
* Analyzes the relationship between age, BMI, and insurance premiums
* Predicts future insurance charges using regression models
* Classifies customers into cost categories
* Supports customer risk assessment
* Assists insurance companies in premium estimation
* Enables data-driven policy planning

---

## Key Insights

* Smoking status is one of the strongest predictors of insurance charges.
* Older customers generally incur higher medical expenses.
* Higher BMI values often contribute to increased insurance costs.
* Multiple Linear Regression provides better prediction accuracy than Simple Linear Regression.
* Logistic Regression effectively classifies customers into cost-based categories.
* Data visualization reveals valuable trends for business decision-making.

---

## Future Enhancements

* Advanced machine learning algorithms
* Random Forest and Gradient Boosting models
* Hyperparameter optimization
* Automated premium recommendation system
* Web-based dashboard deployment
* Real-time customer risk prediction
* Integration with cloud platforms

---

## Conclusion

The Medical Insurance Cost Analysis & Prediction System demonstrates how data analytics and machine learning can improve insurance premium estimation and customer risk evaluation. Through statistical analysis, predictive modeling, and interactive visualizations, the project provides valuable insights that help insurance organizations make informed and data-driven decisions.
