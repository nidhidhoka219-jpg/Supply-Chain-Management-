# Supply-Chain-Management

**Project Overview**

This project analyzes supply chain performance using a dataset, a Power BI dashboard, and Python-based exploratory and predictive analytics. The goal is to uncover operational insights across demand, inventory, production, logistics, supplier quality, and profitability — and to translate those insights into a clear, business-ready view of supply chain efficiency.

**Data Overview**

The raw dataset contains 100 records and 24 columns, where each row represents one SKU. It captures the full supply chain journey, from product pricing and sales to manufacturing, shipping, and quality control.
The dataset includes information across the following business areas:
- **Product Information**: product type, SKU, price, and customer demographics  
- **Demand & Revenue**: number of products sold, revenue generated, and availability  
- **Inventory Management**: stock levels, lead times, order quantities, and inventory turnover  
- **Logistics & Shipping**: shipping times, shipping carriers, transportation modes, routes, and shipping costs  
- **Supplier & Manufacturing**: supplier name, location, production volumes, manufacturing lead time, manufacturing costs, and total costs  
- **Quality Control**: inspection results and defect rates

**Project Files**
- supply_chain_data.csv - Dataset
- supply_chain_analysis.pbix - Power BI dashboard file
- supply_chain_analysis.ipynb - Python analysis notebook

## Data Preparation
Before analysis, the dataset was cleaned and prepared in Python by:
- Checking for missing values
- Filling missing numeric values with the column mean
- Removing duplicate rows
- Creating new business metrics for deeper analysis

## Feature Engineering
To strengthen the analysis, the following derived metrics were created:

- **Profit** = Revenue Generated - Costs  
- **Profit Margin (%)** = Profit / Revenue Generated
- **Inventory Turnover** = Number of Products Sold / Stock Levels  
These calculated fields helped identify the most profitable product categories, assess stock efficiency, and analyze operational performance more effectively.

## Tools Used
- **Python** for cleaning, feature engineering, visualization, and predictive modeling
- **Power BI** for interactive dashboard development
- **Machine Learning**: Random Forest Regressor for sales prediction

## Power BI Dashboard
- An interactive Power BI dashboard was developed to provide a visual and intuitive understanding of supply chain performance.
- The dashboard enables stakeholders to quickly identify inefficiencies, compare performance across dimensions, and make informed operational decisions.
- Developed 12+ KPIs and designed a multi-page interactive dashboard (5 modules) covering Overview, Inventory, Logistics,Manufacturing, and Supplier performance  with slicers and filters, helping stakeholders drill down by region, product category, and transportation modes.  

## Conclusion
This project demonstrates how data analytics can be leveraged to gain end-to-end visibility into supply chain operations. By combining data cleaning, feature engineering, visualization, and predictive modeling, the analysis highlights key inefficiencies and optimization opportunities.

The insights derived can help businesses:
- Improve inventory planning and reduce stock imbalances  
- Optimize logistics and reduce transportation costs  
- Enhance supplier selection and quality control  
- Drive better decision-making using data-backed insights  

Overall, the project showcases strong capabilities in **data analysis, business intelligence, and problem-solving within a real-world supply chain context**.


**Author**

Nidhi D

