🍔 Food Delivery Data Analysis Project
📌 Project Overview

This project focuses on analyzing a food delivery platform dataset by combining multiple data sources in different formats (CSV, JSON, and SQL). The main goal is to create a unified dataset and perform business analytics to extract meaningful insights related to orders, revenue, user behavior, restaurant performance, and membership trends.

The project simulates a real-world industry data integration workflow where data comes from multiple systems and needs to be merged before analysis.

📂 Dataset Description

The project uses three datasets:

1️⃣ orders.csv

Contains transactional order data such as:

Order ID

User ID

Restaurant ID

Order amount

Order date

2️⃣ users.json

Contains customer information including:

User ID

City

Membership type (Gold / Regular)

3️⃣ restaurants.sql

Contains restaurant-related data such as:

Restaurant ID

Cuisine type

Rating

🔄 Data Processing Workflow

The following steps were performed:

Loaded CSV, JSON, and SQL datasets using Pandas and SQLite

Created a local SQLite database to execute SQL scripts

Merged orders and users data using LEFT JOIN on user_id

Merged restaurant details using LEFT JOIN on restaurant_id

Generated the final combined dataset

Saved the merged dataset as:

final_food_delivery_dataset.csv


This final dataset was used as the main source for all analysis.

📊 Analysis Performed

The project includes three types of analysis:

✅ Numerical Analysis

Total orders by Gold members

Total revenue from Hyderabad city

Distinct users who placed orders

Average order value for Gold members

Orders placed at highly rated restaurants

Orders in the top revenue city among Gold members

✅ Multiple Choice Insights

Highest revenue generating city

Best performing cuisine based on average order value

Revenue distribution by rating range

Membership-wise order percentage

Quarterly revenue trends

Restaurant performance analysis

✅ Data Integration Checks

Verified join keys

Identified missing values after LEFT JOIN

Validated column mappings

Confirmed dataset consistency

🛠 Tools & Technologies Used

Python

Pandas (Data manipulation & analysis)

SQLite3 (SQL dataset handling)

Jupyter Notebook / Kaggle Notebook

GitHub (Project hosting)

📁 Project Structure
Food-Delivery-Data-Analysis/
│
├── orders.csv
├── users.json
├── restaurants.sql
├── final_food_delivery_dataset.csv
├── Food_Delivery_Data_Analysis.ipynb
└── README.md

🚀 How To Run This Project
Step 1: Clone Repository
git clone <your-repository-link>

Step 2: Install Required Libraries
pip install pandas


(SQLite is included by default in Python)

Step 3: Open Notebook

Open the notebook file:

Food_Delivery_Data_Analysis.ipynb


Run all cells sequentially.

Step 4: Output

Final merged dataset will be generated

Analysis results will be displayed in notebook output

📈 Key Learning Outcomes

Through this project, you will learn:

Multi-source data integration

Handling CSV, JSON, and SQL datasets

LEFT JOIN operations using Pandas

Business analytics using groupby and aggregation

Real-world data preprocessing techniques

Data-driven decision analysis

🎯 Use Case

This analysis can help:

Food delivery companies understand customer behavior

Identify high performing cities and cuisines

Optimize marketing strategies for premium members

Improve restaurant partnership decisions

📌 Conclusion

This project demonstrates how real-world datasets from multiple formats can be combined and analyzed to generate valuable business insights. It reflects practical industry-level data analytics workflows and improves hands-on experience with data processing and exploratory analysis.

👨‍💻 Author

Name: Guntireddygari Medha Reddy
Project Type: Data Analytics / Internship Assignment
Platform: Kaggle / GitHub
