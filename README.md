🛒 Zomato Data Analysis Project
This project is a complete data analytics pipeline built to analyze a dataset of Zomato restaurant information. It demonstrates a full workflow from data ingestion and cleaning to analysis and visualization, using MySQL, Python (Pandas, SQLAlchemy), and Power BI.

💼 Key Business Questions
This project was designed to answer critical, industry-level questions that drive business strategy:

What is the impact of online ordering on customer ratings?

Which restaurant types are the most popular by customer votes?

What is the average cost for the top cuisines?

🎯 At a Glance: Key Results
The analysis uncovered several key performance indicators:

KPI

Result

Restaurants with Online Ordering Avg. Rating

3.75

Top Cuisine by Average Cost

Chinese

Most Popular Restaurant (by votes)

Byg Brewski Brewing Company

🔄 Project Workflow
The project follows a standard data analytics workflow, moving from raw data to actionable insights.

Database Creation: A relational schema was designed and created in MySQL to structure the raw data from a single CSV file.

Data Cleaning & ETL: A Python script using Pandas and SQLAlchemy was developed to connect to the database, clean inconsistencies, handle missing values, and populate the tables with the analysis-ready dataset.

Dashboard Visualization: The cleaned data was connected to Power BI to build a multi-page, interactive dashboard for visual analysis and insight generation.

📊 Power BI Dashboard Preview
The final dashboard provides a comprehensive overview of restaurant performance, cuisine trends, and the impact of business decisions.

Page 1: Overview & Top Cuisines
Page 2: Restaurant & Online Ordering Analysis
💡 Key Insights Uncovered
Online Ordering Impact: Restaurants with the option for online ordering have a slightly higher average rating of 3.75 compared to restaurants without, which have an average rating of 3.70.

Cuisine Costs: Chinese cuisine has the highest average cost for two people among the top five most common cuisines.

Vote Leaders: The most popular restaurants, based on customer votes, are microbreweries, with Byg Brewski Brewing Company leading the chart with over 16,000 votes.

🛠️ Tools & Technologies
Database: MySQL

Data Processing: Python (with Pandas & SQLAlchemy)

Visualization: Power BI

Environment: Jupyter Notebook

🚀 How to Run This Project
Setup MySQL Database:

Create the database and tables using the Schema_and_Table_creation.sql script.

Run Python ETL Script:

Install necessary libraries: pip install pandas sqlalchemy pymysql

Run the Data_Cleaning_and_Storage.ipynb notebook to clean the data and save it to the database tables.

View Dashboard:

Open the Power BI dashboard file (not included, but images are provided as examples) and connect it to your local MySQL database.
