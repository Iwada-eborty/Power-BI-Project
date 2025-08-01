# Maven Toy Store Business Analysis

## Project Overview
This analysis evaluates sales and inventory data from Maven Toy Store, a toy retail chain in Mexico.
Using Microsoft Power BI, key insights were derived on product profitability, store performance,
seasonal trends, and inventory management. Findings revealed that Toys and Electronics drive the
highest profits, with Downtown stores performing best. Sales peak between March and July, while
October sees the lowest revenue. Inventory analysis indicates stock will last 15-17 days.
Recommendations include optimizing inventory, investing in high-performing locations, and
addressing, seasonal sales fluctuations to enhance profitability and business growth.

![image alt](https://github.com/Iwada-eborty/Power-BI-Project/blob/210f0cbe20e08b0e6f5115326225b1fca3956035/MTS%20Dashboard.png)

## Objectives of the Analysis
The primary goal of this analysis is to generate actionable insights into Maven Toy Store's overall sales
performance and profitability by evaluating:
1. Store location performance
2. Seasonal sales trends
3. Product profitability and sales effectiveness
Based on these findings, recommendations will be provided to optimize business strategies.

## Key Business Questions
1. Which product categories yield the highest profits, and how do these trends vary across
different store locations?
2. Are there identifiable seasonal sales patterns?
3. What is the company's current market reach in terms of store distribution and geographic
presence?
4. What is the total inventory value, and how long can it sustain current sales levels?
5. Which stores perform best and worst in terms of revenue and profitability?

## Tools Used and Methodologies
**Tool used** [website](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads?ocid=ORSEARCH_Bing&msockid=0acc0d4f8b506ede0e1818758a566f56)

## Techniques
• Data Cleaning & Transformation using Power Query
• Data Modeling to establish structured relationships between tables
• DAX Implementation for advanced calculations and metrics
• Data Visualization for interactive and insightful dashboards
• Comprehensive Project Documentation for clear reporting of insights

## Data Processing

### Data Importation and Cleaning Process:
• Data was ingested using Power BI’s Excel connector.

## Cleaning Steps:
• Promoted headers for consistent column naming.
• Converted ID columns from whole numbers to text (as they serve as unique identifiers rather
than numerical values).
• Added calculated fields for total product cost, total product price, and profit in the sales
dataset.
• Corrected data types to ensure consistency.
• Trimmed redundant store names in the Stores Table for clarity.
• Created a Dates Table using CALENDARAUTO() to facilitate temporal analysis, extracting
year, quarter, month, and day attributes.

## Data Modeling
Effective data modeling structures raw data into an analytical framework, allowing seamless
relationship-building between tables. In this project, Power BI automatically identified table
relationships, forming a star schema model

![image alt](https://github.com/Iwada-eborty/Power-BI-Project/blob/35b21f1f6a78b07259582ae3e95219ed0d9f1592/Schema.png)

• Fact Table: Sales Table, Inventory
• Dimension Tables: Products, Stores, and Dates


## Key Insights

## Product Analysis
1. **Which product categories generate the highest profits?**
• Toys are the most profitable, contributing $1.08M (26.89%) of total profits.
• Electronics follow closely with $1M (25%).
• Sports & Outdoor products generate the lowest profit at $500K.
2. **Are these profit trends location-dependent?**
• Electronics dominate in Airport and Commercial locations.
• Toys perform best in Downtown and Residential areas.
3. **Top Performing Products**
   
    **Highest Profit-Generating Products**
   1. Colorbuds - $835K
   2. Action Figure - $348K
   3. Lego Bricks - $298K
   4. Deck of Cards - $252K
   5. Glass Marbles - $190K
5. **Most Sold Products**
   1. Colorbuds - 104K units (23.5%)
   2. Playdoh Can - 103K units (23.2%)
   3. Barrel O’Slime - 91K units
   4. Deck of Cards - 84K units
   5. Magic Sand - 61K units

• Notably, Playdoh Can ranks high in sales volume but not in profitability.

![image alt](https://github.com/Iwada-eborty/Power-BI-Project/blob/cad0a0c5232ac891b91c6941a6294be3e8941d48/salesreport.png)

## Store & Location Analysis
1. **Which locations generate the highest profits?**
• Downtown stores lead with over $2M in profits.
• Airport stores yield the lowest profit at $378K.
2. **Most Profitable Stores?**
    1. Maven Toys Ciudad de Mexico 2 - $170K
    2. Maven Toys Guadalajara 3 - $121K
    3. Maven Toys Ciudad de Mexico 1 - $111K
    4. Maven Toys Monterrey 2 - $107K
    5. Maven Toys Toluca - $105K
3. **Least Profitable Stores?**
• Maven Toys Cuernavaca 1 - $57K
• Maven Toys La Paz 1 - $57K

![image alt](https://github.com/Iwada-eborty/Power-BI-Project/blob/ac224a31572c28977f6bbccad11e724aadc8aa38/storereport.png)

## Seasonal Trends & Patterns
**• Peak Sales & Profits: March–July**
o Highest Sales: April (112K units)
o Highest Profit: March ($406K)
• Lowest Sales & Profits: October
o Sales: 48K units
o Profit: $179K
• Quarterly Trends:
o Q2 (April–June): Highest sales
o Q4 (October–December): Lowest sales

Yearly Trends:
• 2017: Sales peaked towards year-end.
• 2018: Stronger sales from February–July, with March leading.

![image alt](https://github.com/Iwada-eborty/Power-BI-Project/blob/f70dc239fac23b59c15540c89290ee5c4a30a45b/TandP.png)

## Inventory Analysis
**Current Inventory Value & Turnover:**
• Total Inventory Value: $300K
• Total Stock: 29,742 units
• Average Daily Sales: 1,709 units
• Estimated Inventory Duration: 15-17 days before restocking is required.

![image alt](https://github.com/Iwada-eborty/Power-BI-Project/blob/1c5e8c30a3f66f0c7a8595e00f3133a0a9161c17/Inventorymts.png)

## Summary
**Summary of Key Findings:**
1. Downtown stores are the most profitable.
2. Toys lead in profitability, followed by Electronics.
3. Sales dip in January, February, and October.
4. Electronics excel in Airport and Commercial locations, while Toys dominate Downtown
and Residential areas.

## Recommendations:
1. Expand investment in Downtown stores to capitalize on high profitability.
2. Investigate low sales in January and February to identify and mitigate potential market
challenges.
3. Enhance inventory management to avoid stock shortages or excesses, ensuring optimal
stock levels.
