# Customer_Behavior_Analysis
Data Analsysis project showing customer behavior analysis using Python, Power Bi and Postgresql.


## Overview

This project focuses on analyzing customer shopping behavior to understand purchasing patterns, customer preferences, and subscription trends.

The project follows an end-to-end data analytics workflow, starting with data exploration and cleaning in Python, performing business-related SQL queries using PostgreSQL, and finally building an interactive dashboard in Power BI to present meaningful insights.

The main objective is to transform raw customer data into useful business insights that can help understand customer behavior and support better business decisions.

## Dataset

The project uses a Customer Shopping Behavior dataset containing information about customer purchases and shopping preferences.

**Key attributes include:**
- Customer ID
- Age and Gender
- Item Purchased
- Category
- Purchase Amount
- Discount Applied
- Previous Purchases
- Subscription Status
- Shipping Type
- Review Rating
- Payment Method
- Season and Location

## Tools & Technologies

- **Python:** Data analysis and manipulation
- **Pandas & NumPy:** Data cleaning and data processing
- **Matplotlib & Seaborn:** Exploratory Data Analysis and visualization
- **PostgreSQL:** Database management and SQL analysis
- **SQL:** Business queries and customer behavior analysis
- **Power BI:** Interactive dashboard development
- **Jupyter Notebook:** Python development environment
- **GitHub:** Project documentation and version control

## Project Steps

### 1. Data Loading & Exploratory Data Analysis (EDA) – Python

- Imported the dataset using Pandas.
- Explored the dataset structure, columns, and data types.
- Checked missing values and duplicate records.
- Analyzed numerical and categorical variables.
- Identified customer purchasing patterns and trends.
- Used visualizations to understand the data distribution.

### 2. Data Cleaning & Preprocessing – Python

- Handled missing values.
- Checked and removed duplicate records where required.
- Corrected data types.
- Prepared data for further analysis.
- Created additional features where needed for better analysis.

### 3. SQL Analysis – PostgreSQL

Loaded the processed dataset into PostgreSQL and performed SQL queries to answer business-related questions.

**Key business questions explored:**

- What are the most purchased products in each category?
- Which products have the highest discount rates?
- What is the average purchase amount across different shipping types?
- Who are the new, returning, and loyal customers?
- Are repeat buyers (more than 5 previous purchases) more likely to subscribe?
- Which categories generate the highest revenue?

SQL concepts used:
- SELECT, WHERE, GROUP BY, ORDER BY
- Aggregate Functions (SUM, AVG, COUNT)
- CASE WHEN statements
- Common Table Expressions (CTEs)
- Window Functions (ROW_NUMBER)
- Subqueries

### 4. Power BI Dashboard

Developed an interactive Customer Behavior Dashboard to present key business metrics and insights.

**Dashboard Highlights:**
- Total Customers
- Average Purchase Amount
- Average Review Rating
- Maximum Customer Age
- Maximum Previous Purchases
- Customer Subscription Status
- Category-wise Revenue
- Sales by Category

**Interactive Features:**
- Customer subscription filters
- Gender filters
- Product category filters
- Shipping type filters

The dashboard helps users explore customer purchasing patterns and compare business performance across different categories.

## Results & Business Insights

The analysis helps identify:

- Customer purchasing patterns and product preferences.
- Top-performing product categories.
- Customer loyalty and repeat purchasing behavior.
- Relationships between repeat purchases and subscription status.
- Discount usage across different products.
- Revenue distribution across product categories.
- Differences in customer purchasing behavior.

These insights can help businesses improve customer retention, understand product demand, and develop better marketing strategies.

## How to Run the Project

Follow these steps to run the project on your local system.

### Step 1: Clone the Repository

```bash
git clone <your-github-repository-url>
```

### Step 2: Navigate to the Project Folder

```bash
cd Customer-Shopping-Behavior-Analysis
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary jupyter
```

### Step 4: Run Jupyter Notebook

```bash
jupyter notebook
```

Open the project notebook and execute the cells step by step.

### Step 5: PostgreSQL Setup

- Install PostgreSQL.
- Create a database for the project.
- Configure your database connection.
- Load the cleaned dataset into PostgreSQL.
- Execute the SQL queries to perform business analysis.

**Note:** Update your PostgreSQL username, password, host, port, and database name according to your local setup. Do not upload database passwords or other sensitive credentials to GitHub.

### Step 6: Open Power BI Dashboard

- Open the `.pbix` file in Power BI Desktop.
- Connect to the required dataset or PostgreSQL database.
- Refresh the data if required.
- Explore the interactive dashboard.

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_shopping_behavior.csv
├── SQL_Queries.sql
├── Customer_Behavior_Dashboard.pbix
├── Dashboard_Screenshot.png
└── README.md
```

*Note: The SQL file, Power BI file, and dashboard screenshot should be added to the repository if you have created them.*

## Conclusion

This project demonstrates an end-to-end data analytics workflow using Python, PostgreSQL, SQL, and Power BI.

It helped strengthen practical skills in data cleaning, exploratory data analysis, SQL querying, business problem-solving, and dashboard development.

The project showcases the ability to work with raw data, extract meaningful insights, and communicate findings through interactive visualizations.
