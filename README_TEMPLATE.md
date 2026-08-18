# [Project Title]
  Ecommerce Sales Analysis 

---

## ⚙️ Project Type Flags

- [ ] SQL Analysis / Querying
- [ ] Dashboard / Data Visualization
- [ ] Data Cleaning 
- [ ] End-to-End project
      

---

## Table of Contents
1. [Project Overview](#1-project-overview)
2. [Objectives](#2-objectives)
3. [Dataset Info & Tools](#3-Dataset-Info--tools)
4. [Repository Structure](34-Repository-Structure)
5. [Project Workflow](#4-Project-workflow)
6. [Data Model & Schema](#5-data-model--schema)   
7. [Analysis & Metrics](#6-analysis--metrics)
8. [Key Insights](#7-key-insights)
9. [Recommendations](#8-recommendations)
10. [Future Enhancements](#9-future-enhancements)
11. [Conclusion](#10-Conclusion)
12. [Author](#11-author)

---

## 1. Project Overview
this project Analyze an ecommerce sales dataset to evaluate sales performance, customer purchasing behaviour, and product Profitablility. the Project Involves data cleaning using excel,sql and 
the development of a interactive power bi dashboard. the analysis focuses on identify sales trends, top performing products , customer segment, payment methods and regional performance. 

---

## 2. Objectives

  the objective is to generate actionable business insights and recommendations that help improve revenue, profitability and overall business Decision making.

---
## 3. Dataset Info & Tools

Source: Kaggle
Name: ecommerce
No. of Rows: 34502   
No. of Columns: 17
Types: Transactional sales data containing customer details, Product info, order details, pricing, discount, payment mode, shipping info and regional sales.

---
### Tools & Technologies
Tool(s) Used 
Excel, SQL, Power BI

Excel: Conducted initial data inspection and verified the dataset before analysis, also I changed some Column names and changed data types. 
SQL: Queried the dataset, performed aggregations, analyzed sales, customers, Products, and Regional Sales.
Power BI: Developed an interactive Dashboard to Visualize KPIS, sales trends, and Business insights.

---
## 4. Repository Structure


[project-root]/
│
├── data/
│   ├── raw/                  # Original, unmodified source data - never edited
│   ├── processed/            # Cleaned and transformed data            
│
├── queries/                  
| |exploratory/               # presentation queries
|                             
├── reports/                  # Final outputs: PDFs, Word docs
│
├── visuals/                  # Exported charts, dashboard screenshots 
│
└── README.md                 # Project

---
## 5. Project Workflow
  
  1. Source: Collected The ecommerce Dataset from Kaggle.
  2. Ingestion: "Loaded into Excel performed data inspection, changed columns names and Data types."
  3. Cleaning: "Performed Data Cleaning and analysis Business insights using SQL".
  4. Transformation: "Created Aggregation queries, Group by queries to Transformed data and Find Business Insights."
  5. Analysis: "Developed Interactive Dashboards, and KPIS using Power BI."
  6. Output: "Summary report (PDF), processed CSV."

---
## 6. Data Model & Schema  

### Dataset / Table: `[name]`

| Field Name | Data Type | Description | Example Value |
|------------|-----------|-------------|---------------|
|  [order_id] | [string / Text ] | [Unique identifier assigned to each other.] | [ORD1001] |
|  [customer_id] | [string / Text ] | [Unique Identifier assigned to each Customer.] | [CUS501] |
|  [product_id] | [string / Text ] | [Unique identifier to each Product.] | [PROD205] |
|  [category]  | [String / Text] | [Category or type of the product.] |[Electronics] |
|  [Price] | [Decimal / Float] | [Selling Price of the Product before applying Discount.] | [499.99] |
|  [discount] | [Decimal / Float] | [Discount applied to the product, usually represented as a percentage or amount.] | [10.00] |
|  [quantity] | [Integer] | [Number of units purchased in the order.] | [3] |
|  [payment_method] | [string / Text] | [Payment Method used by the Customers.] | [Credit Card] |
|  [order_date] | [Date] | [Date When the Customer Placed order.] | [2026-07-15] |
|  [delivery_time_days] | [Integer] | [Number of Days taken to deliver the order.] | [4] |
|  [region] | [string / Text] | [Geographic region associated with the Customer/order.] | [South] |
|  [returned] | [Boolean / string] | [Indicates Whether the product/order was returned.] | [Yes] |
|  [total_amount] | [Decimal / Float] | [Total amount paid for the order after considering price, quantity and discount.] | [1349.97] |
|  [shipping_codt] | [Decimal / Float] | [Cost Charged or incurred for shipping the order.] | [50.00] |
|  [profit_margin] | [Decimal / Float] | [Profit earned as a Percentage of the Total Sales amount.] | [18.50%] |
|  [customer_age] |  [Integer] | [Age of the Customer who placed the order.] |[20] |
|  [customer_gender] | [string / Text] | [Gender of the Customer.] | [Female] |

---
## 7. Analysis & Metrics

### Analytical Approach

1.[Analyzed overall sales and Revenue trends.]
2.[Identified Top Selling product Categories.]
3.[Compared Sales performance across different Region.]
4.[Identify Monthly and yearly sales trends.]
5.[Examined monthly and yearly sales trends.]
6.[Compared payment methods and their usage.]

### Key Metrics Defined

 [Total Revenue] [ Profit Margin] [Total Sales by Region] [Monthly Sales Trend] [Yearly Sales trend] [Monthly profit] [Top 5 Category]
 [High Revenue product] [Quantity ordered] [Total amount by Category] [Max Delivery Day] [Highest Payment Mode]
 [Which day customers Orderes the Most]

 --- 
## 8. Key Insights

Insight 1: [Total sales showed increasing in trend.]

Insight 2: [A few category and product generating high Revenue.]

Insight 3: [Monthly Sales varied, Indicating seasonal demand patterns.]

Insight 4 [Certain Payment methods were preferred by most customers.]

Insight 5 [Some regions Generating low Revenue.]

Insight 6 [Small Group of Repeated customers Contributed large portion of Total Revenue.]

---
## 9. Recommendations
 
 1.Increase inventory in high selling categories and product
 2.Give offers on low selling products
 3.Run marketing campaign to increase sales 
 4.Focus on these regions where sales in low
 
---
## 10. Future Enhancement 

-  [Enhancement 1 - integrate real time sales data to monitor business performance though a live dashboard]
-  [Enhancement 2 - Build a recommendation system to suggest product based on customer purchase history]
-  [Enhancement 3 -  Analyze customer reviews and feedback using sentiments analysis to understand customer satisfaction]


---

## 11. Conclusion

this project analyzed ecommerce sales data using excel, SQL, and power bi to understand business performance and customer purchasing patterns the data was cleaned, transformed, and analyzed to identify sales
trends, product performance, regional performance, profitablility and customer behaviour. interactive dashboard and key performance metrics were created to support data-driven decision-making.
the insights and recommendations from this analysis can help improve slaes performance, optimize product strategy, and increase overall business profitablility.

---

## 12. Author

**[Zeba Hajera]**
[Data Analyst ]

- 🔗 [https://www.linkedin.com/in/zeba-hajera-3a437a366?utm_source=share_via&utm_content=profile&utm_medium=member_android]
- 💼 [https://github.com/zeba318 ]
- 📧 [zebahajera715@gmail.com]

---


