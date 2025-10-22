🛍️ Sales Data Analysis

📊 Project Overview

This project focuses on analyzing customer purchasing behavior and sales performance using a real-world sales dataset. The goal was to uncover meaningful insights about demographics, spending trends, and regional performance to guide data-driven business decisions.

By leveraging Python (Pandas, NumPy, Matplotlib, Seaborn), I performed data cleaning, transformation, and exploratory data analysis (EDA) to identify key sales drivers, visualize trends, and summarize actionable insights.

🧩 Objectives

Understand customer demographics and purchasing patterns.

Identify the most profitable product categories and customer segments.

Explore how factors like gender, age group, occupation, and region affect sales.

Visualize trends to support data-driven decision-making.

🗂️ Dataset Overview

The dataset contains 11,251 records with information about customers, orders, and sales amounts.

Feature	Description
User_ID	Unique customer ID
Cust_name	Customer name
Gender	Customer gender
Age Group, Age	Demographic information
Marital_Status	0 = Single, 1 = Married
State, Zone	Geographical information
Occupation	Type of occupation
Product_Category	Purchased product category
Orders	Number of items ordered
Amount	Total purchase amount (₹)
🧹 Data Cleaning

Removed null columns (Status, unnamed1).

Handled missing values in the Amount column.

Standardized categorical variables and formatted column names.

Verified data consistency (e.g., valid age ranges and order quantities).

🔍 Exploratory Data Analysis (EDA)
🧠 Key Insights

Customer Profile:
Majority of customers were female buyers (≈55%) from the 26–35 age group, indicating strong mid-age purchasing power.

Regional Performance:
Highest sales came from Western and Southern India, led by Maharashtra and Karnataka.

Top Occupations:
Consumers working in IT, Healthcare, and Aviation spent the most per order.

Product Categories:
The Electronics and Clothing categories drove the largest portion of total sales revenue.

Marital Influence:
Married customers made more purchases on average, hinting at family-oriented buying behavior.

📈 Visualizations

Gender and age group distribution charts.

State-wise and zone-wise revenue heatmaps.

Occupation vs. spending bar plots.

Product category-wise sales comparisons.

Correlation analysis between numerical variables.

All visualizations were built using Matplotlib and Seaborn, styled for professional readability.

🧭 Tools & Libraries Used

Python 3.x

NumPy – numerical computation

Pandas – data manipulation and analysis

Matplotlib & Seaborn – visualization and trend analysis

🚀 Results & Business Impact

Identified high-value customer segments for targeted marketing.

Revealed underperforming regions for potential promotional focus.

Helped optimize product strategy by understanding category-wise revenue splits.

💡 What I Learned

Improved data cleaning and EDA workflow using Pandas.

Gained hands-on experience visualizing categorical and numerical data effectively.

Learned how to communicate analytical findings through clear, insight-driven visuals.

🔮 Future Enhancements

Build an interactive dashboard using Plotly or Power BI.

Perform predictive modeling to forecast sales.

Integrate customer segmentation using clustering algorithms.

📁 Project Structure
├── Sales Data.csv          # Dataset
├── sales.ipynb             # Jupyter Notebook (EDA & Visualization)
└── README.md               # Project Documentation
