# 📊 Smart Supply Chain Analytics – Power BI Project

A complete end-to-end Business Intelligence solution analyzing the DataCo Smart Supply Chain dataset using Power BI, covering data cleaning, modelling, KPI tracking, forecasting, and dashboarding.

# 🚀 Project Overview

This project delivers a full BI workflow—from data preprocessing to star-schema modelling, DAX measures, and interactive dashboards—to evaluate operational performance for DataCo Global’s supply chain during FY 2015–2016.

The goal is to help managers track sales, profits, delivery performance, customer behaviour, and category-level insights.

# 📂 Dataset

Source: DataCo Smart Supply Chain (Kaggle)

Rows: 180,519

Columns: 53 (later normalized into 7 tables)

Purpose: Analyse sales, shipping, production, and customer behaviour 

W9529921_Vaddepally.Rohith

# 🛠 Tools & Techniques

Power BI Desktop

Power Query Editor (M Language)

DAX Calculated Columns & Measures

Star Schema Data Modelling

Interactive BI Visuals (KPI cards, gauges, decomposition tree, timelines, maps)

# 🧹 Data Pre-Processing

Performed extensive transformations in Power Query, including:

Removing unusable columns (ex: Customer Email/Password) 



Replacing inconsistent text (DEBIT → DEBIT PAYMENT, etc.) 


Splitting & merging date/time columns

Fixing data type errors (date/time reconstruction) 


Handling missing values (elimination where <10%) 


Creating normalized tables: Products, Category, Department, Customers, Order Details, Shipment, Order Sales 


#🏗 Data Modelling

A fully structured Star Schema was created:

Fact Table: Order Sales

Dimension Tables: Products, Category, Department, Customers, Order Details, Shipment 



One-to-Many relationships with bi-directional filters

Duplicate removal to eliminate many-to-many issues

# 📏 Key DAX Measures

Total Sales

Total Orders Count

Cost of Making Order Item = Price – Profit 



Average Deliveries

Forecasting (Analytics Pane)

Delivery Speed Classification (Superfast, Medium, Slow) based on shipping days 



# 📊 Dashboard Highlights

Your final dashboards include:

✔ Sales & Profit KPIs

FY2015 Total Sales: $30.99M

Total Order Profit: $3.33M

Total Cost of Items: $17.38M

23K+ late deliveries 



✔ Customer & Product Insights

Highest-profit category: Fishing

Lowest-profit category: Electronics 



United States (EE.UU) generated highest sales (via decomposition tree)

✔ Delivery Performance

Most deliveries: Medium-Fast Delivery

Delivery behaviour categorized via DAX logic 



✔ Forecasting

2-year sales forecast from March 2016 → 2018

Predicted sales on 1 Feb 2018: $25,088.42 



✔ Seasonality Analysis

Sales dipped in Jan–Feb due to specific underperforming regions (Brazil, Mexico, Colombia)

Sales rose in Nov–Dec due to spikes in categories like Kids Golf Clubs & Fishing 



✔ Discount Behaviour

Detailed segmentation of discount ranges (0–25%) using custom M-coded table and DAX ranking logic 



✔ Timeline Slicer (Advanced Visual)

Used to analyze Q4 sales activity

 

