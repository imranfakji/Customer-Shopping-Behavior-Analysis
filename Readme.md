✅ Customer Trend & Behavior Analysis – End-to-End Data Project

📌 Project Overview
This project analyzes customer purchasing behavior using a realistic, industry-style data pipeline:

✅ Load raw dataset into SQL
✅ Clean & transform using SQL + Python
✅ Perform Exploratory Data Analysis (EDA)
✅ Reload the cleaned dataset into SQL
✅ Build an interactive Power BI dashboard for insights
This workflow simulates how data moves in real analytics environments used in companies.

🎯 Business Goal
To identify:
Which products and categories drive revenue
How discounts influence customer behavior
What customer segments purchase the most
Payment preferences and seasonal trends
Key metrics that support business decisions

🧩 Project Structure
10.CUSTOMER_TREND_ANALYSIS
│
├── Datasets
│   └── customer_shopping_behavior.csv
│
├── Docs
│   ├── Business Problem Document.pdf
│   └── Customer Shopping Behavior Analysis.pdf
│
├── Notebooks
│   └── Data_Import_And_EDA.ipynb
│
├── Power BI Dashboard
│   ├── Customer_Behavior_Analysis.pbix
│   └── Customer_Behavior_Analysis.pdf
│
├── SQL EDA
│   └── EDA_And_Knowing_The_Dataset.sql
│
└── img
    ├── dashboard.png
    ├── sales_by_category.png
    ├── top_products.png
    ├── payment_method.png
    └── age_group.png


✅ The img folder contains all dashboard screenshots used in this README.

🛠️ Tech Stack
Phase	Tools Used
Database	MySQL
Cleaning & EDA	Python (Jupyter Notebook), SQL
Visualization	Power BI
Documentation	PDF, GitHub

📥 1️⃣ Data Import into SQL
Designed MySQL database schema
Selected appropriate data types
Imported raw CSV into SQL tables
✅ Real-world skill gained: Database structuring & data ingestion

🧹 2️⃣ Data Cleaning & Transformation
Performed using SQL + Python:
Renamed inconsistent columns
Fixed spacing & formatting issues
Standardized categorical values
Created derived features like age_group
Segmented customers using previous_purchases

Example SQL fix:
ALTER TABLE fact_customer_behavior 
CHANGE `Age Group` age_group VARCHAR(20);
✅ Real-world skill gained: Data quality improvement & feature engineering

🔎 3️⃣ Exploratory Data Analysis (EDA)
Conducted in Data Import_And_EDA.ipynb
Key steps:
Summary statistics
Value distributions
Category behavior patterns
Discount vs non-discount purchases
Product-level insights
✅ Real-world skill gained: Insight discovery from raw data

📤 4️⃣ Export & Reload to SQL
After cleaning, the transformed dataset was exported and reloaded into SQL to prepare for BI integration.
✅ Real-world skill gained: Analytics pipeline thinking

📊 5️⃣ Power BI Dashboard
📌 Customer Behavior Analysis Dashboard
Key Metrics Displayed:
231K Total Sales
3863 Total Orders
$59.70 Average Order Value
42.45% Discounted Customers

📈 Dashboard Visuals
✅ Sales by Category
✅ Top 5 Products Sold
✅ Revenue by Payment Method
✅ Age Group Distribution
✅ Real-world skill gained: Business storytelling with visuals

⭐ Key Insights
Clothing drives the highest revenue
Almost half of customers rely on discounts
PayPal & Credit Card dominate payments
Young adults form the largest buying segment
AOV suggests medium-ticket purchases

🚀 Key Learnings
Through this project, I gained practical experience in:
✅ SQL for cleaning & transformation
✅ Python for EDA
✅ Power BI for dashboarding
✅ Building a structured data pipeline
✅ Turning data into business insights

🔜 Next Steps
Add cohort & RFM analysis
Publish dashboard online
Explore predictive modeling (customer churn / CLV)

🏁 Conclusion
This project showcases a complete, end-to-end analytics workflow — starting from raw data and ending with actionable insights. It reflects real industry practices used by data analysts and data engineers.

🔗 Connect With Me
LinkedIn: www.linkedin.com/in/imranfakji9764267487
GitHub: https://github.com/imranfakji/Customer-Shopping-Behavior-Analysis