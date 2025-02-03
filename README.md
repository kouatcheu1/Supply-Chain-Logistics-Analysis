# Supply Chain Logistics Analysis Using SQL 📦📊

## 📌 Introduction
This project focuses on analyzing supply chain logistics using SQL. The dataset includes information on order management, freight rates, warehouse operations, and plant-to-port logistics. The goal is to optimize transportation costs, inventory management, and supplier performance.

## ❓ Problem Statement
Inefficiencies in supply chain logistics can lead to high costs, delays, and inventory mismanagement. This project aims to:

- 🔍 Analyze order distribution trends.
- 🚚 Optimize freight and warehouse costs.
- 🏢 Assess warehouse capacities and inventory management.
- 📦 Improve supply chain logistics by optimizing plant-to-port shipping.

## 📂 Dataset
The dataset consists of multiple sheets, each capturing a specific aspect of supply chain operations:

### Key Tables & Features:
- **OrderList**: `Order_ID`, `Customer_ID`, `Product_ID`, `Quantity`, `Order_Date`, `Delivery_Date`
- **FreightRates**: `Mode_of_Transport`, `Origin`, `Destination`, `Cost_per_Unit`
- **WhCosts**: `Warehouse_ID`, `Fixed_Cost`, `Variable_Cost_per_Unit`
- **WhCapacities**: `Warehouse_ID`, `Max_Capacity`, `Current_Utilization`
- **ProductsPerPlant**: `Plant_ID`, `Product_ID`, `Production_Capacity`
- **VmiCustomers**: `Customer_ID`, `Inventory_Level`, `Reorder_Threshold`
- **PlantPorts**: `Plant_ID`, `Port_ID`, `Shipping_Capacity`

## 🛠 Technologies Used
- **SQL (Structured Query Language)**: For data extraction, transformation, and analysis.
- **Database Management Systems**: MySQL / PostgreSQL / SQL Server
- **Visualization Tools**: Power BI / Tableau (for further analysis)

## 🔬 Methodology
### 1️⃣ Data Exploration & Cleaning
- Handling missing values and standardizing formats.
- Removing duplicate records and ensuring referential integrity.

### 2️⃣ SQL Query Implementation
- **📊 Order Analysis**: Identifying high-demand products and order fulfillment trends.
- **🚛 Freight Cost Optimization**: Comparing transportation costs across different modes.
- **🏭 Warehouse Efficiency**: Analyzing storage utilization and cost optimization.
- **🌎 Plant-to-Port Logistics**: Evaluating shipping efficiency and identifying bottlenecks.

### 3️⃣ Performance Optimization
- 🔹 Using **Indexes** to speed up query execution.
- 🔹 Implementing **Stored Procedures** for automated reporting.
- 🔹 Leveraging **Joins and Subqueries** for advanced insights.

## 📊 Results & Insights
- ✅ **Top-Selling Products**: Identified demand trends for better inventory planning.
- ✅ **Freight Cost Reduction**: Optimized transport routes to lower costs.
- ✅ **Warehouse Utilization**: Balanced inventory allocation to prevent overstocking.
- ✅ **Supply Chain Optimization**: Improved plant-to-port shipping efficiency.

## 🎯 Key Features and Functionality
- 🚀 **Comprehensive SQL queries** for logistics insights.
- 🎯 **Optimization strategies for cost efficiency**.
- 📈 **Data-driven decision-making for inventory and supplier management**.
- 🔍 **Advanced SQL techniques, including CTEs, Window Functions, and Stored Procedures**.

##🚀 Explore the SQL script for detailed query implementations! Supply Chain Logistics Analysis with SQL  ![Supply Chain Logistics Analysis](https://github.com/kouatcheu1/Supply-Chain-Logistics-Analysis/blob/main/Suppy%20Chain%20Analysis.sql)
