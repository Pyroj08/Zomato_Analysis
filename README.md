🍽️ Zomato Data Analysis Project

This project is a complete data analytics pipeline built to analyze Zomato’s restaurant dataset. It demonstrates a full workflow from data ingestion and cleaning to SQL-driven analysis and interactive visualization, using MySQL, Python (Pandas, SQLAlchemy), and Power BI.

💼 Key Business Questions

This project was designed to answer critical questions in the food & restaurant industry:

Which restaurant chains dominate the market?

What are the top 10 most popular cuisines?

Which cuisines have the highest average cost?

How has online ordering impacted restaurant performance?

What are the most popular restaurants by type (e.g., casual dining, cafes)?

🎯 At a Glance: Key Results
KPI	Result
Largest Restaurant Chain	Domino’s Pizza
Most Popular Cuisine	North Indian
Avg. Highest Cost Cuisine	Continental
Online Ordering Impact	Improved order volume by ~22%
Top Restaurant Type	Casual Dining
🔄 Project Workflow

The project follows a structured data analytics workflow, moving from raw data to actionable insights.

Database Creation: A relational schema was designed in MySQL using Schema_and_Table_creation.sql
.

Data Cleaning & ETL: A Python ETL pipeline in Data_Cleaning_and_Storage.ipynb
 cleaned raw data, handled duplicates, and loaded structured data into MySQL.

Exploratory SQL Analysis:

Top_10_Restaurant_Chains.sql

Top_10_Most_Popular_Cuisines.sql

Average_Cost_for_Top_Cuisines.sql

Impact_of_Online_Ordering.sql

Most_Popular_Restaurant_by_Type.sql

Dashboard Visualization: An interactive Power BI dashboard was built (Zomato_Dashboard.pbix).

📊 Power BI Dashboard Preview
Page 1: Market & Cuisines Overview

Page 2: Chains & Ordering Insights

💡 Key Insights Uncovered

Restaurant Chains: Domino’s Pizza leads in outlets, followed by Café Coffee Day.

Cuisines: North Indian and Chinese dominate customer preference.

Cost Trends: Continental cuisine has the highest average cost per order.

Online Ordering: Boosts orders by nearly 22%, making it a critical sales channel.

Restaurant Types: Casual Dining emerges as the most popular business model.

🛠️ Tools & Technologies

Database: MySQL ``

Data Processing: Python (with Pandas & SQLAlchemy)

Visualization: Power BI ``

Environment: Jupyter Notebook ``

🚀 How to Run This Project

Setup MySQL Database:

Run Schema_and_Table_creation.sql
.

Import cleaned data into MySQL.

Run Python ETL Script:

Install dependencies:

pip install pandas sqlalchemy pymysql


Execute Data_Cleaning_and_Storage.ipynb
.

Run SQL Queries:

Execute the provided .sql scripts for insights.

View Dashboard:

Open Zomato_Dashboard.pbix
 in Power BI Desktop.

📜 License

This project is licensed under the MIT License.
