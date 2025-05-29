# 📊 AdventureWorks Sales Analytics (Power BI)

This repository contains a comprehensive Power BI project focused on analyzing sales performance using the AdventureWorks sample database. The dashboard provides key insights into orders, revenue, product performance, and sales territories, built on a robust data model with advanced DAX measures and interactive visualizations.

<img src="https://github.com/user-attachments/assets/52be78fd-cdd6-4642-90d1-974ceb2f4e18" width="700"/>

---

## 🚀 Project Overview

The main objective of this project was to transform raw sales data from AdventureWorks into actionable insights. This involved:
* Connecting to the SQL Server database in DirectQuery mode.
* Performing extensive data cleaning and transformation using Power Query.
* Designing a robust Star Schema data model.
* Creating a rich set of DAX measures, including advanced KPIs.
* Developing interactive and insightful dashboards with drill-down, drill-through, and tooltip capabilities.

---

## ✨ Key Features & Insights

* **Sales Trend Analysis:** Track total orders and revenue over time, comparing Order Date, Ship Date, and Due Date impacts.
* **Product Performance:** Analyze order quantity by product category, subcategory, and individual products.
* **Territory Performance:** Evaluate sales and orders by sales territory, including top performers.
* **Sales Person Performance:** Identify top sales persons based on orders or total sales amount.
* **Shipping & Order Status Analysis:** Insights into order fulfillment and shipping methods.
* **Advanced KPIs:** Monitor key metrics like Year-over-Year Sales Growth, Average Order Value, Gross Profit Margin, and Average Days to Ship.

---

## 🛠️ Technologies & Tools

* **Microsoft Power BI Desktop:** For data connection, transformation, modeling, DAX, and visualization.
* **SQL Server:** As the data source (AdventureWorks database).
* **Power Query (M Language):** For data ingestion and transformation.
* **DAX (Data Analysis Expressions):** For creating calculated columns and measures.

---

## 📁 Project Structure
### 1. Data Connection & DirectQuery Mode
### 2. Data Transformation with Power Query
Extensive data cleaning, reshaping, and merging were performed in Power Query Editor to prepare the data for modeling. Key transformations included:
* **Renaming Tables and Columns:** For clarity and ease of use in the reporting layer.
* **Removing Unused Columns:** To optimize performance and reduce model size.
* **Merging Product Tables:** `Production.Product`, `Production.ProductSubcategory`, and `Production.ProductCategory` were merged into a single `Products` dimension table containing `ProductID`, `Product Name`, `SubCategory`, and `Category`.
* **Creating a Dates Table:** A dedicated date dimension table was generated using Power Query to support time-intelligence functions.
* **Adding Order Status:** A custom column for readable order status text was added based on the `ufnGetSalesOrderStatusText` logic (or a conditional column mapping).
### 3. Data Modeling (Star Schema)
<img src="https://github.com/user-attachments/assets/c55ce986-c896-4d66-9b19-112b0fff2d9c" width="700"/>

### 4. DAX Measures & Advanced KPIs
<p align="left">
  <img src="https://github.com/user-attachments/assets/a3e0c611-d71c-471d-a626-33166fdaecbc" alt="Image 1" width="500"/>
  <img src="https://github.com/user-attachments/assets/073732da-3031-44fe-b207-59715227bacf" alt="Image 2" width="500"/>
</p>
<img src="https://github.com/user-attachments/assets/75166cde-659c-49b4-82a8-bea5ee79c572" width="300"/>

### 5. Interactive Dashboards & Visualizations
<p align="center">
  <img src="https://github.com/user-attachments/assets/0a6a7704-fe00-4580-9686-8fd0cea45cb0" width="600" style="margin-right: 10px;"/>
  <img src="https://github.com/user-attachments/assets/b93bf2bb-08ae-4f50-b663-654800c1868d" width="600"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b0de66a7-a428-4910-ad62-5857640e10a0" width="600" style="margin-right: 10px;"/>
  <img src="https://github.com/user-attachments/assets/3a6ed2e7-ccc7-4834-ad19-3713c115b20c" width="600"/>
</p>





