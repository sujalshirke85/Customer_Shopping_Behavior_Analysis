# Customer_Shopping_Behavior_Analysis

 This project focuses on analyzing customer shopping behavior to uncover insights that help businesses to make better decisions.
 The analysis includes data cleaning, exploratory data analysis (EDA), SQL-based insights extraction, and visualization through an interactive Power BI dashboard.
 The key objective was to identify spending patterns, customer preferences, and factors influencing purchase behavior such as gender, age, subscription status, and shipping type.

📂 Dataset:
File: customer_shopping_behavior.csv
Source: kaggle
Size: ~3,900 records

🧰 Tools & Libraries:
* Python (Jupyter Notebook)	
* PostgreSQL	
* Power BI	
* Pandas
* Numpy
* Matplot
* Seaborn

🧾 Project Steps:

1️⃣ Data Loading:-
 * Imported the dataset into Jupyter Notebook using Pandas.
 Verified column types and handled missing or inconsistent data.

2️⃣ Data Cleaning:-
 * Removed duplicates and standardized text columns (e.g., gender, category)
   
3️⃣ Exploratory Data Analysis(EDA):-
 * Analyzed distribution of purchase amounts, customer demographics, and ratings.
Visualized:
 * Top-selling categories
 * Average purchase by gender and age group
 * Correlation between subscription and spending habits
   
4️⃣ SQL Analysis (PostgreSQL):-
  Executed analytical SQL queries such as:
 * Total revenue by gender
 * Customers using discounts but spending above average
 * Top 5 products by review rating
 * Comparison of shipping types
 * Subscriber vs non-subscriber spending patterns
 * Revenue contribution by age group

5️⃣ Dashboard Building (Power BI):-
 * Integrated the cleaned dataset into Power BI and built an interactive dashboard for executives and business users.

📈 Dashboard Overview:

>Key Metrics:
* 3.9K Customers
* $59.76 Average Purchase Amount
* 3.75 Average Review Rating

Visuals Included:
🟠 Customer Subscription Status (Donut Chart)

🟠 Sales & Revenue by Category (Bar Charts)

🟠 Sales & Revenue by Age Group (Horizontal Bars)

🟠 Filter Panel: Subscription, Gender, Category, Shipping Type

The dashboard allows interactive filtering and provides an instant overview of how different demographics and behaviors influence purchase trends.

📊 Results & Insights:

* Clothing generated the highest sales and revenue among all categories.
* Subscribed customers contributed significantly higher average spending.
* Young Adults were the most active and profitable customer group.
* Express shipping users had slightly higher average purchase amounts.
