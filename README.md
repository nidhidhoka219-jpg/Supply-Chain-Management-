# Supply Chain Management

## Project Overview

This project analyzes supply chain performance using a dataset, a Power BI dashboard, and Python based exploratory and predictive analytics. The goal is to uncover operational insights across demand, inventory, production, logistics, supplier quality, and profitability and to translate those insights into a clear, business ready view of supply chain efficiency.

## Data Overview

The raw dataset contains 100 records and 24 columns, where each row represents one SKU. It captures the full supply chain journey, from product pricing and sales to manufacturing, shipping, and quality control.
The dataset includes information across the following business areas:
- **Product Information**: product type, SKU, price, and customer demographics  
- **Demand & Revenue**: number of products sold, revenue generated, and availability  
- **Inventory Management**: stock levels, lead times, order quantities, and inventory turnover  
- **Logistics & Shipping**: shipping times, shipping carriers, transportation modes, routes, and shipping costs  
- **Supplier & Manufacturing**: supplier name, location, production volumes, manufacturing lead time, manufacturing costs, and total costs  
- **Quality Control**: inspection results and defect rates

## Executive Summary
This project analyzes supply chain performance across **product type, customer segment, location, supplier, route, carrier, transportation mode, inventory, manufacturing, and quality inspection** dimensions.

The analysis shows that:

- **Skincare** is the strongest product category by both revenue and sales volume.
- **Mumbai** leads revenue contribution, while **Kolkata** leads sales volume.
- **Carrier B** handles the highest volume and is the fastest carrier on average.
- **Route A** delivers the highest revenue and the lowest shipping cost, while **Route C** is the fastest but most expensive.
- **Supplier 1** is the best performing supplier on quality and lead time, while **Supplier 5** shows the highest defect rate.
- Quality control is a concern because **41%** of records are marked **Pending** and **36%** are **Fail**.
- Customer data has a segmentation gap because **31%** of records are labeled **Unknown**.
- The notebook’s baseline Random Forest model is exploratory only; with this small dataset, it does **not** perform well enough for production forecasting.

## Business Problem
The objective is to convert raw supply chain data into actionable insights for leadership and operations teams by answering questions such as:
- Which products, cities, and suppliers drive revenue and profit?
- Where are inventory and demand mismatches happening?
- Which logistics options are cost efficient versus time efficient?
- Which suppliers need review based on defect rate and lead time?
- How can the business improve service levels, reduce cost, and prevent stockouts?

## Project Files
- supply_chain_data.csv - Dataset
- supply_chain_analysis.pbix - Power BI dashboard file
- supply_chain_analysis.ipynb - Python analysis notebook

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

## Business interpretation
- Skincare is the clear revenue leader and should remain a strategic category. Haircare contributes strongly as a secondary growth driver, while cosmetics still provides meaningful volume but trails in overall value creation.
- Mumbai generates the most revenue, while Kolkata handles the highest sales volume. Delhi has relatively high sales volume compared with its revenue, which suggests a lower average order value or stronger price pressure.
- Route C and Sea transport are time efficient or cost efficient in different ways, but not both. Route A and Carrier B provide the best overall operational balance for most business use cases.

## Business suggestion
- Prioritize stock availability, supplier reliability, and marketing support for **skincare**, then scale **haircare** as the next most valuable category. Review cosmetics pricing and assortment to improve margin contribution.
- Use city level assortment strategies:
  - Push **skincare** harder in **Kolkata** and **Chennai**
  - Push **haircare** in **Bangalore**
  - Keep **cosmetics** strong in **Mumbai** and **Delhi**
  - Investigate Delhi’s revenue gap to improve average transaction value
- Use **Carrier B** as the default carrier for high volume operations
- Use **Route A** for cost-efficient fulfillment
- Reserve **Route C** and **Air** only for urgent orders or premium service levels
- Use **Sea** only when delivery speed is not critical
- Shift more volume to **Supplier 1**
- Improve planning with **Supplier 3** because long lead time can create stockouts

## Power BI Dashboard
- An interactive Power BI dashboard was developed to provide a visual and intuitive understanding of supply chain performance.
- The dashboard enables stakeholders to quickly identify inefficiencies, compare performance across dimensions, and make informed operational decisions.
- Developed 12+ KPIs and designed a multi-page interactive dashboard (5 modules) covering Overview, Inventory, Logistics, Manufacturing, and Supplier performance  with slicers and filters, helping stakeholders drill down by region, product category, and transportation modes.  

## Conclusion
This project demonstrates how data analytics can be leveraged to gain end-to-end visibility into supply chain operations. By combining data cleaning, feature engineering, visualization, and predictive modeling, the analysis highlights key inefficiencies and optimization opportunities.

The insights derived can help businesses:
- Improve inventory planning and reduce stock imbalances  
- Optimize logistics and reduce transportation costs  
- Enhance supplier selection and quality control  
- Drive better decision-making using data backed insights  

Overall, this project demonstrates:
- Data cleaning and quality validation
- KPI design
- EDA and business insight generation
- Operational storytelling with Power BI
- Supplier, logistics, inventory, and manufacturing analysis
- Baseline predictive modeling
- Business recommendation writing

This project shows how a small supply chain dataset can be transformed into a meaningful business dashboard and analytical story. The strongest opportunities are in:
- scaling **skincare**
- improving **supplier quality**
- reducing logistics cost through smarter route/carrier selection
- fixing **inventory imbalance**
- enriching customer data for better segmentation

The result is a supply chain analytics portfolio project that combines **Python, Power BI, KPI thinking, and business decision support**.



## Author

Nidhi D

Aspiring Data Analyst 

LinkedIn: www.linkedin.com/in/
nidhidhoka
