# Exploratory_Data_Analysis_In_DataWarehouse

## 📊 Project Overview

This project demonstrates **Exploratory Data Analysis (EDA) on a Star Schema Data Warehouse** using SQL. The objective is to explore and understand the structure, quality, and business insights hidden within fact and dimension tables before moving into advanced analytics and reporting.

The project covers a complete analytical workflow starting from database exploration and schema understanding to advanced analytical techniques using SQL window functions, aggregations, joins, and ranking methods.

---

## 🎯 Objectives

- Understand the overall Data Warehouse structure.
- Explore fact and dimension tables.
- Analyze business measures and key metrics.
- Identify trends, patterns, and anomalies.
- Generate actionable business insights using SQL analytics.
- Practice advanced SQL techniques commonly used in Data Warehousing and Business Intelligence projects.

---

## 🏗️ Data Warehouse Architecture

The analysis is performed on a **Star Schema Data Warehouse**, consisting of:

- **Fact Tables**
  - Store business transactions and measurable events.
  - Contain foreign keys referencing dimension tables.

- **Dimension Tables**
  - Store descriptive business attributes.
  - Enable filtering, grouping, and categorization.

---

## 🔍 Exploratory Data Analysis (EDA)

### 1. Database Exploration
- Explore databases, schemas, tables, and relationships.
- Understand the overall warehouse structure.
- Analyze metadata and table dependencies.

### 2. Dimension Exploration
- Investigate dimension tables.
- Analyze business entities, categories, and hierarchies.
- Validate data consistency and completeness.

### 3. Date Exploration
- Analyze available date ranges.
- Identify reporting periods.
- Validate temporal coverage.

### 4. Measures Exploration
- Explore key business measures.
- Analyze distributions and summary statistics.
- Understand the magnitude of metrics.

### 5. Magnitude Analysis
- Compare business metrics across dimensions.
- Measure contribution and scale.
- Identify major performance drivers.

### 6. Ranking Analysis
- Top-N and Bottom-N analysis.
- Best and worst performing products, customers, or regions.
- Ranking using SQL Window Functions.

---

## 🚀 Advanced Analytics

### 7. Change Over Time Analysis
- Year-over-Year (YoY) analysis.
- Month-over-Month (MoM) analysis.
- Trend identification and growth measurement.

### 8. Cumulative Analysis
- Running totals.
- Cumulative sales and performance metrics.
- Rolling aggregations.

### 9. Performance Analysis
- Compare actual performance across business dimensions.
- Identify high-performing and underperforming entities.
- KPI-based evaluation.

### 10. Part-to-Whole Analysis
- Contribution analysis.
- Percentage-of-total calculations.
- Market share and proportional insights.

### 11. Data Segmentation
- Customer segmentation.
- Product segmentation.
- Business category analysis.

### 12. Reporting
- Build analytical queries for reporting.
- Create reusable SQL scripts.
- Present business-ready insights.

---

## 🛠️ SQL Concepts Used

This project extensively utilizes:

### SQL Fundamentals
- SELECT Statements
- Filtering and Sorting
- Aggregations
- Group By
- Case Statements

### Joins
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL OUTER JOIN

### Advanced SQL
- Common Table Expressions (CTEs)
- Subqueries
- Derived Tables
- Set Operations

### Window Functions
- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- NTILE()
- LAG()
- LEAD()
- FIRST_VALUE()
- LAST_VALUE()
- SUM() OVER()
- AVG() OVER()

---

## 📈 Business Questions Answered

Examples of analyses performed:

- What are the top-performing products?
- Which customers generate the highest revenue?
- How do sales change over time?
- Which regions contribute most to total sales?
- What are the cumulative sales trends?
- Which product categories dominate the business?
- How are customers segmented based on behavior?

---

## 📂 Repository Structure

```text
Exploratory_Data_Analysis_In_DataWarehouse/
│
├── Database_Exploration/
├── Dimension_Exploration/
├── Date_Exploration/
├── Measures_Exploration/
├── Magnitude_Analysis/
├── Ranking_Analysis/
├── Change_Over_Time_Analysis/
├── Cumulative_Analysis/
├── Performance_Analysis/
├── Part_To_Whole_Analysis/
├── Data_Segmentation/
├── Reporting/
└── README.md
```

---

## 🎓 Skills Demonstrated

- Data Warehousing
- Star Schema Analysis
- Exploratory Data Analysis (EDA)
- Business Intelligence
- SQL Query Optimization
- Advanced SQL Analytics
- Window Functions
- Ranking & Trend Analysis
- Reporting & KPI Analysis

---

## 📌 Key Takeaway

This project represents a complete SQL-driven EDA and analytics workflow in a Data Warehouse environment. It showcases how to transform raw warehouse data into meaningful business insights through systematic exploration, analytical thinking, and advanced SQL techniques.
