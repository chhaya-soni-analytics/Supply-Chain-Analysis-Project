# 🚚 Supply Chain Analysis Project


# 📌 Project Overview

This project focuses on analyzing supply chain operations using Python-based data analysis, 
exploratory data analysis (EDA), and machine learning techniques.

The objective of this project is to identify delivery delays, analyze operational bottlenecks, 
understand profitability impact, and build a predictive model to detect late delivery risks.

The analysis helps businesses improve fulfillment efficiency, reduce delays, and support 
data-driven operational decisions.


---

# 🎯 Business Problem

A global e-commerce organization faced challenges related to inconsistent order fulfillment performance.

Actual shipping times were different from scheduled delivery timelines, resulting in:

- Late deliveries
- Customer dissatisfaction
- Operational inefficiencies
- Profit impact

The goal was to analyze delay patterns, identify major causes, and develop a predictive system 
for improving delivery performance.


---

# 📂 Dataset Overview

The original dataset contained:

- 180,519 rows
- 53 columns

After data cleaning and preprocessing:

- 172,765 orders
- 20 analytical features

Data preparation included:

- Removing unnecessary identifiers
- Removing personal and irrelevant fields
- Removing cancelled shipments
- Converting date columns
- Creating new analytical features


---

# 🛠️ Tools & Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data Analysis & Modeling |
| Pandas | Data Cleaning & Transformation |
| NumPy | Numerical Analysis |
| Matplotlib | Data Visualization |
| Seaborn | Exploratory Data Analysis |
| Scikit-Learn | Machine Learning |
| Jupyter Notebook | Development Environment |


---

# 🔄 Project Workflow


## 1. Data Loading

- Imported dataset
- Checked data structure
- Reviewed columns and data types
- Understood business variables


## 2. Data Cleaning

Performed:

- Missing value handling
- Duplicate removal
- Data type conversion
- Removal of irrelevant columns
- Filtering cancelled orders


## 3. Feature Engineering

Created new features:

- Order Processing Time
- Delivery Delay
- Delay Flag
- Order Month
- Order Day
- Order Hour
- Profitability Classification


---

# 🔍 Exploratory Data Analysis (EDA)


## Delivery Performance Analysis

Analyzed delivery performance to understand operational efficiency.

Key findings:

- Total orders analyzed: 172,765
- Late deliveries: 94,523
- On-time deliveries: 78,242

Late Delivery Rate:

54.71%

On-Time Delivery Rate:

45.29%


The analysis shows delivery delays are a major operational challenge.


---

# 💰 Profitability Analysis


Business impact analysis:

- Total Profit: $7.5M
- Estimated loss due to delays: $2.1M


Profitability Distribution:

- Profit Orders: 80.66%
- Loss Orders: 18.69%
- Break-even Orders: 0.64%


The analysis shows delivery performance directly impacts profitability.


---

# 📊 Business Analysis Performed


Analyzed delay patterns across:

- Regions
- Customer Segments
- Shipping Modes
- Product Categories
- Departments
- Order Status


Identified categories with higher delay percentages 
to help prioritize operational improvements.


---

# ⏱️ Time-Based Analysis


Analyzed delivery trends based on:

- Monthly order patterns
- Day-wise order behavior
- Hourly order trends


This helped identify periods where delay risk increases.


---

# 🤖 Machine Learning Model


## Objective

Predict whether an order will experience late delivery.


## Algorithm Used

Random Forest Classifier


## Features Used:

- Product Type
- Shipping Mode
- Customer Segment
- Region
- Department
- Scheduled Shipping Days
- Time-based Features


## Data Balancing

SMOTE technique was applied to handle class imbalance.


---

# 📈 Model Performance


Model Results:

| Metric | Score |
|---|---|
| Accuracy | 74% |
| Precision | 79% |
| Recall | 75% |


The model can be used for early identification of high-risk shipments.


---

# 💡 Key Business Insights


✔ More than half of the orders were delayed.

✔ Delivery delays significantly affect profitability.

✔ Some regions and shipping methods have higher delay risk.

✔ Delay prediction can help operations teams take preventive actions.

✔ A targeted logistics strategy performs better than a one-size-fits-all approach.


---

# 🚀 Recommendations


- Create alerts for high-risk shipments.
- Monitor delay-prone regions and categories.
- Improve dispatch planning.
- Optimize carrier assignment.
- Track delay-related profit loss as a KPI.
- Use predictive analytics for proactive decision-making.



