# End-to-End Sales Analytics Solution | SQL + Power BI

## Overview
This project is an end-to-end sales analytics solution built to transform raw sales data into a business-ready reporting system for decision-makers.

It covers the full workflow of a reporting project: business requirement gathering, SQL-based data transformation, data modeling, dashboard development in Power BI, and slide presentation reporting for stakeholder communication.

The solution was designed to help sales managers and sales representatives monitor performance, compare actual sales against budget, identify top-performing customers and products, and support better decision-making through interactive reporting.

---

## Dashboard Preview
![Dashboard Overview](images/dashboard-overview.png)
![Dashboard Overview](images/dashboard-overview.png)
![Dashboard Overview](images/dashboard-overview.png)
---

## Business Problem
Sales teams need a clear and reliable way to monitor performance across customers, products, locations, and time periods. Raw transactional data alone is difficult to interpret and does not provide the visibility needed for fast decision-making.

This project was built to solve that problem by creating a structured reporting solution that answers key business questions such as:

- Are sales performing above or below budget?
- Which customers generate the most revenue?
- Which products are top-performing?
- How are sales trending over time?
- Which cities or regions contribute the most sales?

---

## Project Objectives
This solution was built to:

- transform raw sales data into analysis-ready tables
- create a clean and scalable data model for reporting
- develop an interactive Power BI dashboard for sales monitoring
- compare actual sales against budget performance
- provide presentation-ready reporting for stakeholders
- communicate insights in a clear and business-friendly format

---

## Tools Used
- **SQL Server** for data extraction, cleaning, and transformation
- **Power BI** for data modeling, DAX measures, and dashboard development
- **Excel** for budget and supporting report inputs
- **PowerPoint / Slide Reporting** for presentation-ready business reporting

---

## Business Requirements
The reporting solution was designed based on the following stakeholder needs:

### Sales Manager
- wants an overview dashboard of internet sales
- wants to track sales performance against budget
- wants visibility into top customers and products
- wants better monitoring of business performance over time

### Sales Representative
- wants a customer-focused view to identify high-value buyers
- wants a product-focused view to understand what sells best
- wants a simple and interactive report for monitoring sales activity

---

## Business Request Snapshot
![Business Request](images/business-request.png)

---

## Solution Summary
This project was completed in four major stages:

### 1. Business Understanding
Defined the reporting requirements based on stakeholder needs and translated them into measurable dashboard and reporting outputs.

### 2. Data Transformation in SQL
Prepared the necessary fact and dimension tables by extracting relevant columns, cleaning values, standardizing naming conventions, and shaping the data for reporting.

### 3. Data Modeling and Dashboard Development
Built a Power BI data model to connect sales, customer, product, date, and budget data into a reporting-ready structure. Created visualizations for KPI tracking, trend analysis, product performance, customer analysis, and geographic insights.

### 4. Presentation Reporting
Structured the final findings into a slide presentation format suitable for management reporting and business review discussions.

---

## SQL Data Preparation
The reporting dataset was prepared using SQL before loading into Power BI.

### Tables Created
- `FACT_InternetSales`
- `DIM_Products`
- `DIM_Customers`
- `DIM_Calendar`

### Key Transformation Steps
- selected only relevant business fields
- cleaned and renamed columns for readability
- joined product categories and subcategories
- created full customer names from first and last name fields
- standardized gender labels into business-friendly values
- created calendar attributes such as month, quarter, and year
- filtered the data to fit the reporting scope
- prepared the model for budget vs actual analysis

### SQL Preview
![SQL Transformation](images/sql-transformation.png)

---

## Data Model
A star-schema-inspired model was created to support flexible filtering and efficient reporting.

The model connects:
- sales fact data
- product dimension
- customer dimension
- calendar dimension
- budget data

This structure enables:
- time intelligence analysis
- customer and product drilldowns
- KPI reporting
- budget vs actual comparison
- cleaner dashboard performance

### Data Model Preview
![Data Model](images/data-model.png)

---

## Dashboard Features
The Power BI dashboard includes the following key features:

- **Total Sales KPI**
- **Budget KPI**
- **Sales vs Budget Variance**
- **Top 10 Customers by Sales**
- **Top 10 Products by Sales**
- **Sales by Product Category**
- **Monthly Sales Trend**
- **Map-Based Sales Distribution**
- interactive filtering by year, month, city, category, and product

---

## Sales Dashboard
![Sales Dashboard](images/sales-dashboard.png)

---

## Presentation Reporting
In addition to the dashboard, this project includes slide presentation reporting designed for executive or stakeholder review.

The presentation layer is intended to:
- summarize the business objective
- highlight the most important KPIs
- communicate key sales insights
- support management discussion and decision-making
- translate dashboard findings into a presentation-ready format

This strengthens the project by showing not only technical build skills, but also reporting and communication skills used in real business environments.

### Presentation Preview
![Presentation Preview](images/presentation-preview.png)

---

## Key Business Value
This solution helps stakeholders:

- monitor whether sales are meeting targets
- identify top-performing customers and products
- track sales patterns over time
- compare actual performance against budget
- improve visibility into sales operations
- support data-driven planning and decision-making

---

## Skills Demonstrated
This project highlights practical skills relevant to data analyst and BI analyst roles:

- business requirement analysis
- SQL data cleaning and transformation
- dimensional modeling
- Power BI dashboard development
- KPI and trend reporting
- budget vs actual analysis
- stakeholder-focused presentation reporting
- documentation and project communication

---

## Repository Structure
```text
end-to-end-sales-analytics-solution/
│
├── README.md
├── sql/
│   ├── fact_internet_sales.sql
│   ├── dim_products.sql
│   ├── dim_customers.sql
│   └── dim_calendar.sql
│
├── powerbi/
│   └── Sales_Analytics_Dashboard.pbix
│
├── presentation/
│   └── Sales_Analytics_Report.pptx
│
├── images/
│   ├── dashboard-overview.png
│   ├── business-request.png
│   ├── sql-transformation.png
│   ├── data-model.png
│   ├── sales-dashboard.png
│   └── presentation-preview.png
│
└── docs/
    └── business-requirements.md
