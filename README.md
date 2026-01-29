# Supply-Chain-Inventory-Logistics-Analytics

This project explores key performance indicators and operational patterns within a company’s supply chain using Python-based data analysis and visualization.
It focuses on understanding relationships among price, revenue, inventory, transportation, defect rates, and product performance to support business decisions.

# Business Context
Supply chain performance plays a critical role in operational efficiency, revenue generation, and cost optimization.
Manual assessment of supply chain data is slow and inconsistent. This project demonstrates how analytics can reveal actionable insights about product sales, logistics, and inventory behaviour, helping businesses make data-backed decisions.

# Data Overview
The dataset includes multiple fields relevant to supply chain operations such as:

	• Product attributes (type, SKU, price)
	• Sales figures and revenue generated
	• Inventory metrics (stock levels, order quantities)
	• Transportation data (carriers, costs, modes)
	• Lead times and manufacturing costs
	• Defect rates and inspection results
  
This rich dataset allows comprehensive analysis across sourcing, sales, and logistics dimensions. 

# Analytical Approach
1. Data Preparation & Overview
#
	• Loaded the dataset using Pandas
	• Inspected descriptive statistics to understand distribution of key metrics
	• Handled basic data quality checks
3. Revenue & Sales Analysis
#
	• Examined the relationship between product price and revenue generated
	• Compared product type contributions to total sales
	• Visualized distribution of products sold by category
  
5. Transportation & Logistics Evaluation
#
	• Compared total revenue by shipping carriers
	• Analyzed transportation costs distribution across modes
	• Assessed defect rates by product type and transportation mode
  
7. Inventory & SKU Analysis
#
	• Visualized revenue, stock levels, and order quantities by SKU
	• Identified patterns in stock and demand levels
	• Explored relationships between lead times and manufacturing costs

# Key Insights

	• Revenue patterns vary by product type, with some categories generating higher returns at higher prices. 
	• Carrier performance differs: some carriers generate more revenue but also greater costs. 
	• Inventory metrics, such as stock levels and order quantities, show operational patterns that may influence future supply decisions. 
	• Defect rates vary by mode of transportation and product type, providing insight into quality risk areas. 


# Business Impact
This analysis equips stakeholders with evidence-based insights that can be used to:

	• refine inventory planning and reorder decisions
	• optimize transportation and logistics costs
	• adjust pricing and SKU strategies based on revenue contribution
	• detect quality risk areas and improve operational controls

# Tech Stack

	• Python
	• Pandas, NumPy
	• Plotly (visualization)
	• Jupyter Notebook

# Limitations & Future Work

	• Analysis is exploratory and descriptive — no predictive modeling is included
	• Correlation does not imply causation — deeper causal analysis may be warranted
	• Future work could extend to:
		○ machine-learning–based demand forecasting
		○ optimization modeling (inventory or pricing)
		○ real-time dashboarding
