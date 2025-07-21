# SQL_Data_Exploration

# 📊 SQL Data Exploration Project

This project showcases a structured SQL data exploration process performed on a retail dataset. The goal was to understand the data through profiling, aggregations, and advanced analytical queries.

---

## 🔍 Project Overview



## 📊 Power BI Dashboard

To visualize the insights gained from SQL exploration, a Power BI dashboard was created. It presents key metrics and visual breakdowns by country, category, and product.

![Power BI Dashboard Screenshot](/SQL_Data_Exploration.png)



The following tasks were completed to explore and gain insights from the dataset:

### 1. Data Understanding
- **Basic Queries**: Performed simple `SELECT` statements to view the structure and contents of the dataset.
- **Data Profiling**: Examined attributes such as data types, null values, min/max values, and unique counts.
- **Simple Aggregations**:
  - `SUM`, `COUNT`, `AVG`, `MIN`, `MAX` functions used to summarize data.
- **Subqueries**: Implemented nested queries to refine analysis and filtering.

---

## 🧩 Data Modeling

The data was categorized into:

- **Dimensions**: Categorical variables used for slicing and dicing data.
  - `Country`
  - `Category`
  - `Product`
- **Measures**: Numerical variables used for aggregations.
  - `Total Sales`
  - `Total Number of Orders`
  - `Number of Items Sold`
  - `Average Selling Price`
  - `Total Number of Products`
  - `Total Number of Orders` *(deduplicated)*
  - `Total Number of Customers Who Placed an Order`

---

## 📅 Temporal Analysis

- Identified the **Oldest and Latest**:
  - Order Dates
  - Customer Birthdates

---

## 📈 Analytical Techniques

### 🔹 Magnitude Analysis
- Compared **measure values** across different **product categories** and other dimensions to identify trends and high-performing segments.

### 🔹 Ranking Analysis
- Used **SQL Window Functions** (`RANK()`, `ROW_NUMBER()`) to:
  - Rank dimensions (e.g., products or countries) based on various measures such as total sales or number of orders.

---

## 🛠️ Tools & Technologies

- **SQL**
- **RDBMS**: [SQL Server]
- **Power BI**

---

## 📌 Conclusion

This project demonstrated a methodical approach to SQL data exploration, transforming raw data into meaningful insights through profiling, aggregations, categorization, and analytical querying.

---


│   ├── ranking_analysis.sql
├── README.md
