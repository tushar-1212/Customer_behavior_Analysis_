## Overview

This project analyzes customer shopping behavior using transactional data to identify purchasing patterns, customer segments, product preferences, and revenue trends. The analysis combines Python for data processing, SQL for business insights, and Power BI for interactive data visualization.

The objective is to transform raw customer purchase data into actionable business recommendations that can support marketing, sales, and customer retention strategies.

---

## Dataset

The dataset contains customer purchase transactions and shopping behavior information.

### Dataset Information

* Records: 3,900+
* Features: 18 columns
* Data Includes:

  * Customer Demographics (Age, Gender, Location)
  * Purchase Details (Product, Category, Amount, Season)
  * Subscription Information
  * Discounts and Promotions
  * Shipping Preferences
  * Customer Reviews and Ratings

---

## Tools & Technologies

| Tool                            | Purpose                     |
| ------------------------------- | --------------------------- |
| Python                          | Data Cleaning & EDA         |
| Pandas                          | Data Manipulation           |
| NumPy                           | Numerical Operations        |
| Matplotlib / Seaborn            | Data Visualization          |
| PostgreSQL / MySQL / SQL Server | Data Storage & SQL Analysis |
| SQL                             | Business Querying           |
| Power BI                        | Interactive Dashboard       |
| Gamma                           | Presentation Creation       |
| GitHub                          | Project Documentation       |

---

## Project Workflow

### 1. Data Loading

* Imported dataset using Python and Pandas.
* Examined dataset structure and data types.

### 2. Data Cleaning

* Handled missing values.
* Standardized column names.
* Removed redundant fields.
* Improved data consistency.

### 3. Exploratory Data Analysis (EDA)

* Customer demographic analysis.
* Purchase amount distribution.
* Category-wise sales analysis.
* Subscription behavior analysis.
* Product rating analysis.

### 4. Feature Engineering

* Created customer age groups.
* Generated purchase frequency metrics.
* Prepared data for SQL and dashboard analysis.

### 5. SQL Analysis

Performed business-focused SQL queries such as:

* Revenue by Gender
* High-Spending Discount Users
* Top Rated Products
* Shipping Type Comparison
* Subscriber vs Non-Subscriber Analysis
* Customer Segmentation
* Revenue by Age Group
* Top Products by Category
* Repeat Buyer Analysis

### 6. Power BI Dashboard

Built an interactive dashboard to visualize:

* Total Customers
* Average Purchase Amount
* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Subscription Distribution
* Customer Segmentation Insights

### 7. Reporting & Presentation

* Created a detailed business report.
* Summarized insights and recommendations.
* Designed a professional presentation using Gamma.

---

## Dashboard Highlights

Key KPIs displayed:

* Total Customers
* Total Revenue
* Average Purchase Amount
* Average Review Rating
* Revenue by Product Category
* Revenue by Age Group
* Subscription Status Analysis
* Sales Performance Metrics

---

## Key Findings

* Clothing category generated the highest revenue.
* Young Adult customers contributed the most revenue.
* Loyal customers formed the largest customer segment.
* Several products showed strong dependence on discounts.
* Subscription users demonstrated valuable engagement patterns.
* Express shipping customers showed slightly higher spending behavior.

---

## Business Recommendations

1. Increase subscription adoption through exclusive benefits.
2. Implement customer loyalty programs for repeat buyers.
3. Optimize discount strategies to maintain profitability.
4. Promote highly rated products through targeted campaigns.
5. Focus marketing efforts on high-revenue customer segments.

---

## Project Structure

```bash
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── shopping_data.csv
│
├── Python/
│   └── eda_analysis.ipynb
│
├── SQL/
│   └── business_queries.sql
│
├── PowerBI/
│   └── dashboard.pbix
│
├── Report/
│   └── Customer_Shopping_Report.pdf
│
├── Presentation/
│   └── Project_Presentation.pdf
│
└── README.md
```

## How to Run

### Python Analysis

```bash
pip install pandas numpy matplotlib seaborn
```

```bash
python analysis.py
```

### SQL Analysis

1. Import the cleaned dataset into PostgreSQL, MySQL, or SQL Server.
2. Execute the SQL scripts from the SQL folder.
3. Review business insights generated from queries.

### Power BI Dashboard

1. Open the `.pbix` file in Power BI Desktop.
2. Refresh the data source.
3. Explore interactive visuals and filters.

---

## Author
Tushar Patil

Skills: Python, SQL, Power BI, Data Analysis, Data Visualization, PostgreSQL

---

⭐ If you found this project useful, consider giving it a star on GitHub.
