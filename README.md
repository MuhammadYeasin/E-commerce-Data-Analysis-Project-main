# E-commerce Data Analysis Project


This project analyzes an e-commerce dataset to gain insights into user behavior and item popularity. The analysis includes cleaning the dataset, handling missing values, detecting and removing outliers, and exploratory data analysis.

**Project Structure**

Portfolio_1_questions.ipynb: The Jupyter notebook containing the code and analysis for the project.

The E-commerce Dataset.csv: The dataset used for the analysis.

**Getting Started**

**Prerequisites**

1.Python 3.x

2.Jupyter Notebook

3. Required Python libraries: pandas, numpy, matplotlib, seaborn

**Analysis Overview**

**Data Cleaning:**
This process involves handling missing values, detecting and removing outliers, and ensuring the dataset is ready for analysis.

**Detect and Remove Outliers**
We define outliers using three rules:

1.Reviews with helpfulness no more than 2.

2.Users who rate less than 7 items.

3.Items that receive less than 11 ratings.

***Exploratory Data Analysis (EDA)***

1.Visualize the distribution of ratings.

2.Analyze user and item rating patterns.

3.Identify trends and patterns in the data.

***Results***

-Initial dataset length: 19916 

-After removing reviews with helpfulness ≤ 2: 13643 

-After removing users who rated less than 7 items: 2741 

-Final cleaned dataset length after removing items with less than 11 ratings: 2685
