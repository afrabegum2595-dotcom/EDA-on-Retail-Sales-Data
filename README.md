📊 EDA on Retail Sales Data

«Turning raw retail data into meaningful business insights using Python.»

📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of a retail/e-commerce sales dataset containing 1,000 sales records.

The objective is to explore sales performance, customer characteristics, product performance, and revenue patterns, while demonstrating how data analysis can support data-driven business decisions.

The project uses Python-based data analysis and visualization techniques to transform raw sales data into structured insights.

---

🎯 Project Objectives

The main objectives of this project are to:

- Understand the structure and quality of the dataset
- Perform data cleaning and preprocessing
- Calculate descriptive statistics
- Analyze monthly and quarterly sales trends
- Explore customer demographics
- Identify the top 10 best-selling products
- Compare revenue across product categories
- Analyze relationships between numerical variables
- Compare average order value across customer groups
- Generate meaningful business insights
- Provide actionable recommendations

---

📂 Dataset

Dataset: "realistic_e_commerce_sales_data.csv"

The dataset contains 1,000 sales records with the following attributes:

Column| Description
"Customer ID"| Unique customer identifier
"Gender"| Customer gender
"Region"| Customer region
"Age"| Customer age
"Product Name"| Name of the purchased product
"Category"| Product category
"Unit Price"| Price of one unit
"Quantity"| Number of units purchased
"Total Price"| Total value of the purchase
"Shipping Fee"| Shipping cost
"Shipping Status"| Status of the shipment
"Order Date"| Date of the order

---

🛠️ Technologies & Tools

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 📈 Seaborn
- ☁️ Google Colab
- 🗂️ GitHub

---

🔍 Analysis Performed

1. 🧹 Data Inspection & Cleaning

The dataset was examined to understand:

- Dataset dimensions
- Column names
- Data types
- Missing values
- Duplicate records
- Overall data quality

Order dates were converted into an appropriate datetime format for time-based analysis.

2. 📊 Descriptive Statistics

The analysis includes:

- Mean
- Median
- Mode
- Standard deviation
- Summary statistics

These measures help understand the distribution and characteristics of the numerical variables.

3. 📈 Sales Trend Analysis

Sales performance was examined across:

- Monthly sales
- Quarterly sales

This helps identify changes and patterns in sales performance over time.

4. 👥 Customer Demographics

Customer characteristics were explored using:

- Age-group analysis
- Gender distribution

This provides a better understanding of the customer base represented in the dataset.

5. 🛍️ Product Performance

The analysis identifies the Top 10 best-selling products based on quantity sold.

This helps highlight products with strong sales volume.

6. 💰 Category Revenue Analysis

Revenue was compared across different product categories to identify categories contributing significantly to overall sales.

7. 🔗 Correlation Analysis

A correlation heatmap was created to examine relationships between numerical variables such as:

- Age
- Unit Price
- Quantity
- Total Price
- Shipping Fee

Correlation analysis helps identify patterns and relationships within the numerical data.

8. 👤 Average Order Value Analysis

Average order value was compared across customer gender groups to explore differences in purchasing value between customer segments.

---

📈 Key Insights

The analysis provides a business-oriented view of the dataset by identifying:

- 📅 Sales patterns across different time periods
- 👥 Customer demographic characteristics
- 🛍️ Best-performing products
- 💰 Revenue contribution across product categories
- 🔗 Relationships between numerical sales variables
- 👤 Differences in average order value between customer groups

The complete analysis and visualizations are available in the Jupyter Notebook included in this repository.

---

💡 Business Recommendations

Based on the analysis, several actions can be considered:

1. 🛍️ Prioritize High-Performing Products

Maintain adequate inventory for products with strong sales volume and consider targeted promotions to further improve their performance.

2. 💰 Focus on High-Revenue Categories

Product categories contributing significantly to revenue can receive greater attention in inventory planning, marketing, and promotional strategies.

3. 👥 Use Customer Demographics

Age and gender insights can help businesses develop more targeted marketing campaigns and improve customer engagement.

4. 📊 Use Sales Trends for Planning

Monthly and quarterly sales patterns can support better planning for inventory, promotions, and future sales strategies.

5. 🎯 Improve Customer Targeting

Customer-group analysis can help businesses develop more relevant offers and improve the overall customer experience.

---

📁 Project Structure

EDA-on-Retail-Sales-Data/
│
├── 📓 EDA_Retail_Sales_Data.ipynb
├── 🐍 eda_retail_sales_data.py
├── 📄 realistic_e_commerce_sales_data.csv
└── 📖 README.md

📓 "EDA_Retail_Sales_Data.ipynb"

Contains the complete exploratory data analysis, including data preparation, statistical analysis, visualizations, and insights.

🐍 "eda_retail_sales_data.py"

Python implementation of the analysis workflow.

📄 "realistic_e_commerce_sales_data.csv"

The retail/e-commerce dataset used for the analysis.

📖 "README.md"

Project documentation and overview.

---

▶️ How to Run the Project

Option 1 — Google Colab

1. Open "EDA_Retail_Sales_Data.ipynb"
2. Upload/open the notebook in Google Colab
3. Upload "realistic_e_commerce_sales_data.csv"
4. Run the notebook cells sequentially

Option 2 — Local Environment

Clone the repository:

git clone https://github.com/afrabegum2595-dotcom/EDA-on-Retail-Sales-Data.git

Navigate to the project directory:

cd EDA-on-Retail-Sales-Data

Install the required libraries:

pip install pandas numpy matplotlib seaborn

Run the Python file:

python eda_retail_sales_data.py

---

🚀 Future Improvements

This project can be extended by adding:

- 📊 Interactive dashboards using Power BI or Tableau
- 📈 Sales forecasting using machine learning
- 👥 Customer segmentation
- 🎯 Customer lifetime value analysis
- 📦 Inventory demand prediction
- 🌐 Deployment of an interactive analytics dashboard

---

📌 Conclusion

This project demonstrates how Exploratory Data Analysis can transform raw retail data into meaningful information for business decision-making.

By combining data cleaning, statistical analysis, visualization, and business interpretation, the project provides a foundation for understanding sales performance, customer behaviour, product trends, and revenue patterns.

«Data is not just numbers — it is a source of insights, patterns, and better decisions. 📊»

---

🔗 Repository

GitHub:
https://github.com/afrabegum2595-dotcom/EDA-on-Retail-Sales-Data

---

👩‍💻 Author

Afra Begum

Aspiring Data Analyst | Data Science Learner | Python Enthusiast
