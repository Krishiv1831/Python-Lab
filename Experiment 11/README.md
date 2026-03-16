# 📊 Experiment 11: Categorical Data Analysis using Python

Name: Krishiv Sharma
Branch: EnTC A3
PRN: 25070123065
Batch: A-3
Date: 06-03-2026

📘 Title Page

Project Title: Categorical Data Analysis using Python
Objective: To study and perform categorical data analysis using the Pandas library in Python.
Programming Language: Python
Libraries Used: Pandas

🎯 Aim of the Study

The aim of this experiment is to analyze categorical datasets using Python.
The experiment demonstrates how to create a dataset and perform categorical data analysis using Pandas functions such as value_counts(), unique(), nunique(), crosstab(), filtering, grouping, and sorting.

📌 Introduction

Categorical data represents data that can be grouped into categories or labels rather than numeric values.

Examples include:

Product Category

Payment Method

Delivery Type

Customer Type

Categorical data analysis helps in:

Understanding distribution of categories

Identifying patterns between variables

Performing statistical summaries of categorical variables

Python’s Pandas library provides efficient tools for performing categorical data analysis.

📂 Dataset Description

The dataset used in this experiment represents customer order information.

Column Name	Description
Order_ID	Unique identifier of each order
Category	Type of product purchased
Payment_Method	Payment method used by customer
Delivery_Type	Type of delivery selected
Customer_Type	Type of customer (New or Regular)

Example Categories:

Electronics

Clothing

Grocery

Payment Methods:

Credit Card

Debit Card

PayPal

Delivery Types:

Standard

Express

Customer Types:

New

Regular

📖 Study of Dataset Operations

The following operations are performed in this experiment:

Creating categorical dataset using dictionary

Converting dictionary to Pandas DataFrame

Displaying dataset

Frequency count of categories

Finding unique values

Counting number of unique values

Cross tabulation between variables

Percentage distribution of categories

Filtering dataset

Grouping dataset

Sorting dataset

📘 THEORY & ALGORITHMS WITH FLOWCHARTS
🔹 Part 1: Creating the Dataset
Algorithm

Start

Import pandas library

Create dictionary containing categorical data

Convert dictionary into DataFrame

Display DataFrame

Stop

Flowchart
Start
  ↓
Import pandas
  ↓
Create Data Dictionary
  ↓
Convert to DataFrame
  ↓
Display Dataset
  ↓
Stop
🔹 Part 2: Frequency Count of Categories
Algorithm

Start

Select categorical column

Apply value_counts()

Display frequency of each category

Stop

Flowchart
Start
  ↓
Select Column
  ↓
Apply value_counts()
  ↓
Display Frequency
  ↓
Stop
🔹 Part 3: Finding Unique Values
Algorithm

Start

Select categorical column

Apply unique()

Display unique categories

Stop

Flowchart
Start
  ↓
Select Column
  ↓
Apply unique()
  ↓
Display Unique Values
  ↓
Stop
🔹 Part 4: Counting Unique Values
Algorithm

Start

Select categorical column

Apply nunique()

Display number of unique categories

Stop

Flowchart
Start
  ↓
Select Column
  ↓
Apply nunique()
  ↓
Display Count
  ↓
Stop
🔹 Part 5: Cross Tabulation

Cross tabulation helps analyze the relationship between two categorical variables.

Algorithm

Start

Select two categorical columns

Apply pd.crosstab()

Display cross-tabulation table

Stop

Flowchart
Start
  ↓
Select Two Columns
  ↓
Apply Crosstab
  ↓
Generate Table
  ↓
Display Result
  ↓
Stop
🔹 Part 6: Percentage Distribution
Algorithm

Start

Select categorical column

Apply value_counts(normalize=True)

Multiply result by 100

Display percentage distribution

Stop

Flowchart
Start
  ↓
Select Column
  ↓
Calculate Proportion
  ↓
Convert to Percentage
  ↓
Display Result
  ↓
Stop
🔹 Part 7: Filtering Dataset

Filtering helps extract specific records from dataset.

Algorithm

Start

Define filtering condition

Apply condition to dataset

Store filtered data

Display filtered dataset

Stop

Flowchart
Start
  ↓
Define Condition
  ↓
Filter Dataset
  ↓
Store Filtered Data
  ↓
Display Result
  ↓
Stop
🔹 Part 8: Grouping Dataset

Grouping helps analyze data across multiple categories.

Algorithm

Start

Select grouping columns

Apply groupby()

Apply aggregation or counting

Display grouped data

Stop

Flowchart
Start
  ↓
Select Columns
  ↓
Apply groupby()
  ↓
Aggregate Data
  ↓
Display Result
  ↓
Stop
🔹 Part 9: Sorting Dataset
Algorithm

Start

Select column for sorting

Apply sort_values()

Display sorted dataset

Stop

Flowchart
Start
  ↓
Select Column
  ↓
Apply sort_values()
  ↓
Display Sorted Data
  ↓
Stop
🛠 Tools Used

Python

Pandas Library

Jupyter Notebook

VS Code

GitHub

📊 Applications of Categorical Data Analysis

Market basket analysis

Customer segmentation

Business analytics

E-commerce analysis

Survey data analysis

🎯 Conclusion

Categorical Data Analysis using Python enables efficient analysis of non-numerical data. Using Pandas functions such as value_counts(), unique(), nunique(), crosstab(), filtering, grouping, and sorting, we can easily analyze categorical variables and understand patterns in datasets.

These techniques are widely used in data science, business analytics, and machine learning applications to extract meaningful insights from categorical datasets.

✨ End of README
