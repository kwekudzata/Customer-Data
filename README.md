# 📊 Customer Behavior Analysis — Data Cleaning, EDA & Segmentation

A full end-to-end data analysis project showcasing data cleaning, exploration, segmentation, and visualization using Python.
This project uses a synthetic dummy dataset (5,000 rows) to simulate real-world customer analytics.

## 📝 Overview

This project walks through the complete data analysis workflow: <br>
Importing and inspecting raw data <br>
Cleaning (missing values, duplicates, outliers, consistency checks) <br>
Feature engineering <br>
Exploratory Data Analysis (EDA) <br>
Rule-based customer segmentation <br>
Data visualization using Matplotlib & Seaborn <br>
Insights & business interpretation <br>

## The dataset includes the following columns:
customer_id <br>
age <br>
gender <br>
country <br>
monthly_visits <br>
amount_spent <br>
joined_year <br>

## 🔧 Technologies Used
Python 3 <br>
Pandas <br>
NumPy <br>
Matplotlib <br>
Jupyter Notebook <br>


## 🧹 Data Cleaning
 Missing & Duplicate Checks
Used .isnull().sum() to scan for missing values
Used .duplicated().sum() to detect duplicates
Removed or handled issues where necessary

 Outlier Detection
Identified extreme values in amount_spent, age, and monthly_visits
Used boxplots & Z-scores to highlight unusual data points

 Categorical Consistency
Ensured standardization of:
gender (Male/Female/Other)
country (from a fixed list: Ghana, Nigeria, Kenya, etc.)

 Date Conversion
Converted joined_year into a proper date and computed:
Customer’s account age
Year-over-year signup trends


## 📊 Exploratory Data Analysis (EDA)

Key questions explored:
What is the age distribution of customers?

Which country has the highest number of customers?

Which gender spends the most on average?

Does higher visit frequency mean higher spending?

What is the signup trend over the years?

Visualizations include:
Histograms
Bar charts
Line plots
Scatter plots

## 🧩 Customer Segmentation

Segmentation used percentile-based rules:

Low Spenders
Bottom 25% of customers by amount spent

Medium Spenders
25th–75th percentile

High Spenders
Top 25%

This enables deeper analysis such as:
Which group visits most?
Which group generates the most revenue?
Which country produces the most high spenders?


