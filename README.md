# Energy-Consumption-Analysis
Global Emissions, GDP & Energy Analysis (SQL Project)
 Overview

This project analyzes global environmental and economic data using SQL. The analysis focuses on carbon emissions, GDP, population, energy production, and energy consumption across different countries and years.

The goal of this project is to derive meaningful insights by writing optimized SQL queries using joins, aggregations, window functions, and grouping techniques.

 Objectives

Analyze total emissions per country and year

Identify year-over-year emission growth

Compare energy production vs energy consumption

Find top countries by GDP

Study the relationship between population and emissions

Apply advanced SQL concepts like GROUP BY, HAVING, JOIN, and WINDOW FUNCTIONS

 Dataset Used

The project includes the following datasets:

emission_3 – Country-wise carbon emissions data

gdp_3 – GDP data by country and year

population – Population statistics

production – Energy production data

consumption – Energy consumption data

🛠️ SQL Concepts Used

SELECT statements

WHERE clause

GROUP BY & HAVING

ORDER BY

JOINS (INNER JOIN)

Aggregate Functions (SUM, AVG)

Window Functions (LAG(), ROW_NUMBER())

Subqueries & CTEs

 Key Analysis Performed
1️ Total Emissions Per Country

Calculated total carbon emissions for each country and identified the most recent year data.

2️ Year-over-Year Emission Change

Used LAG() window function to measure emission growth compared to the previous year.

3️ Top 5 Countries by GDP

Ranked countries based on GDP values for the most recent year.

4️ Energy Production vs Consumption

Compared production and consumption trends by country and year to identify energy gaps.

5️ Population vs Emissions

Analyzed how population growth impacts total emissions.

 Sample Query Example
SELECT 
    country, 
    SUM(emission) AS total_emission
FROM emission_3
GROUP BY country
ORDER BY total_emission DESC;

 Project Outcomes

Identified emission growth patterns globally

Determined high GDP contributing countries

Compared renewable and non-renewable energy trends

Improved understanding of environmental data analysis using SQL

 Skills Gained

Data Cleaning & Transformation

Writing Complex SQL Queries

Analytical Thinking

Data Interpretation

Working with Relational Databases

 Technologies Used

MySQL / PostgreSQL

SQL

Relational Databases

 Conclusion

This project demonstrates strong SQL fundamentals and analytical skills by solving real-world environmental and economic data problems. It showcases the ability to work with large datasets and extract actionable insights using structured query language.
