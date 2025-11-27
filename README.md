# Google-Play-Store-data-analysis
"Data analysis of the Google Play Store dataset using Python (NumPy, Pandas, Matplotlib). Includes data cleaning, preprocessing, visual exploration, and insights on app ratings, installs, and categories."


## 🔷 Introduction

The Google Play Store houses millions of apps across diverse categories, making it a rich ecosystem to analyze user behavior, app performance, and market trends.
This project performs a complete exploratory data analysis (EDA) on a Google Play Store dataset to uncover meaningful insights related to app categories, ratings, installs, pricing, and popularity trends.

The goal is to transform raw, inconsistent data into a structured and visually interpretable form using Python-based analysis and visualizations.

## 🎯 Objectives

The main objectives of the analysis were to:

Clean and preprocess a raw Google Play Store dataset.

Explore patterns in app ratings, installs, categories, and pricing.

Visualize key insights through charts (bar, pie, histogram, scatter).

Understand relationships between app performance metrics (e.g., ratings vs installs).

Build a reproducible, portfolio-ready analysis notebook.

## 🛠️ Tools & Technologies Used

Python
NumPy – Numerical processing
Pandas – Data cleaning, transformation, EDA



## 📚 Dataset Information: 



## 🛠️ Detailed Project Breakdown
#### 🔸 1. Data Cleaning & Preprocessing

Removed duplicates

Handled missing values (rating, type, size)

Converted installs from “10,000+” → 10000

Converted price from “$2.99” → 2.99

Standardized categories and content rating

Converted Size column to numerical by handling “M”, “k”, “Varies with device”

#### 🔸 2. Exploratory Data Analysis (EDA)

Used descriptive statistics and grouped insights to understand:

Most common categories

Rating distribution

Difference between Free and Paid apps

Trends in installs

Relationship between rating, price, and installs

#### 🔸 3. Data Visualization

Created multiple charts to visually understand and present findings.


### 📊 Charts
##### 📌 1. App Count by Category (Bar Chart)

Shows which categories dominate the Play Store (e.g., Family, Tools, Games).
Helps identify where competition is highest.

##### 📌 2. Rating Distribution (Histogram)

Displays how app ratings are spread from 1 to 5.
Shows that most apps are rated between 3.5 – 4.5.

##### 📌 3. Free vs Paid Apps (Pie/Bar Chart)

Compares number of free and paid apps.
Reveals that the majority of apps are free.

##### 📌 4. Installs Distribution (Histogram)

Visualizes frequency of installs across ranges.
Helps understand popularity trends and market reach of apps.

##### 📌 5. Price Distribution for Paid Apps (Histogram)

Shows pricing patterns — most paid apps cost under $10.
Useful for pricing strategy insights.

###### 📌 6. Rating vs Installs (Scatter Plot)

Plots app rating against install volume.
Highlights whether higher ratings correlate with more downloads.

###### 📌 7. Category-wise Average Rating (Bar Chart)

Shows rating differences across app categories.
Identifies best-performing categories in user satisfaction.

## 🧠 Learning Outcomes

Through this project, the following skills were strengthened:

###### 🔹 Data Cleaning

Handling missing values

Converting categorical/numerical formats

Standardizing text fields

Fixing inconsistent symbols (e.g., “+”, “M”, “$”)

##### 🔹 Exploratory Data Analysis

Grouping and aggregating data

Feature interpretation

Identifying outliers and trends

###### 🔹 Data Visualization

Designing clear and meaningful charts

Understanding chart selection (bar, histogram, scatter)

Interpreting visual trends for business insights

##### 🔹 Python Libraries

Pandas for data manipulation

NumPy for numerical operations

Matplotlib for visualization

## 📝 Conclusion

This Google Play Store data analysis project successfully demonstrates the complete workflow of transforming raw data into actionable insights.
The analysis revealed important trends such as:

Most apps belong to a few dominating categories

Majority of apps are free

Higher installs tend to align with better ratings

Paid apps follow predictable pricing patterns

The final notebook showcases strong analytical thinking, Python skills, and the ability to communicate insights through clean visualizations — making it a strong addition to a data analytics portfolio.

Matplotlib – Data visualization

Jupyter Notebook – Code execution & analysis
