# Datamatrix-ml-Pharmaceuticals-Report
This report delivers a detailed examination of datamatrix-ml-pharmaceuticals sales performance, monthly sales trend, product class performance, and  management performance across Poland and Germany. uncovering trend in regional sales, channel efficiency, staff contributions, and product profitability using power Bi.

#  Table of content
 1. Introduction
   2. Data Preparation
   3. Tools used
   4. Understanding the datset
   5. Visualisation
   6. Key Findings
   7. Conclusion and Recommendations
# Introduction
The report provides a technical report of pharmaceutical sales and product performance across many dimensions sub channel countries, sale team, sale manager, product categories and trends, the dashboards provided serve as the basic for descriptive analytic with further interpretive insights include to support decision making.

# Data Preparation
This project analyzes pharmaceutical sales performance across multiple dimensions — location, sales channel, and product characteristics — to generate business insights such as channel effectiveness, location performance,management performance, and product profitability. All datasets were cleaned using power bi, and transformed for proper analysis.

Tools Used
power bi -For initaial data prtocessing, formula and structuring
Power bi - for merging and transfoirming data effenciency
power bi - for visualsation, trend snalysids and generate insights

Understanding the dataset
This dataset represents chocolate product sales across different locations, sales channels, and salespersons. It helps analyze performance, profitability, and demand patterns. Main Tables and Roles: • Sales Fact Table: Records each transaction — date, salesperson, location, product, boxes shipped, sales channel, and delivery status. • Location Table: Adds country, city, and region details. • SalesPerson Table: Contains salesperson names, emails, and hire dates. • Product Table: Provides product names, categories, cocoa content, cost, price, and organic labels.

Key steps: • Removed duplicates and filled missing values. • Standardized text fields (e.g., delivery status, sales channels). • Converted dates to YYYY-MM-DD format. • Created calculated columns such as: o Total Sales = Boxes Shipped × Price per box o Profit = Total Sales – Total Cost o Profit Margin (%) = (Profit / Total Sales) × 100 o Delivery Success Flag = IF(Delivery Status="Completed",1,0)

The final dataset, Chocolate_Sales, combines sales, location, product, and salesperson information for analysis.

Insights Derived: • Location and channel performance • Salesperson productivity vs. €100,000 target • Product and category profitability • Organic vs. non-organic product demand

# OVERALL BUSINESS PERFORMNACE:
•	The business had a total sales amounting to $11.8 billion
•	A total of 29 million units of the products were sold
•	The business record about 254 thousand customers
SALES CHANNEL & SUB CHANNEL PERFORMANCE:
Channel has two categories:
•	Pharmacy dominates the total of $6.2bn
•	Followed by hospital with $6.5bn
Sub channel:
•	Retail tops with $ 3.34bn
•	Institution $2.87bn
Sales team & rep performance:
•	Jimmy grey tops the list with $ 0.9bn follow by Abigal Thomas .and stella with $ 0.9bn
•	Alan ray and Thompson performed low
SALES MANAGER:
•	Brittany Bold $4bn
•	Tracy bank $3bn
•	James Goodwill$3bn
•	Anthony Grbriel $2bn
TREND ANALYSIS:
As at 2017:
•	Total sales $ 2.7bn
•	Quantity $7m
•	Customers 56k
As at 2018:
•	Total sales 3.51bn
•	Quantity 8m
•	Customers 94k
As at 2019:
•	Total sales 2.93bn
•	Quantity 7m
•	Customers 52k
As at2020:
•	Total sales 2.66bn
•	Quantity 7m
•	Customers 51k
Note: about 4k customer from Germany were lost as at 2020 compared to the number of customers in 2017.

# MONTHLY SALES ANALYSIS:
•	Lowest sales occurred in January $0.67bn followed by a sharp recovery in February $0.97bn
•	Peak sales were achieved in march $1.11bn and September $ 1.19bn
•	A notable dip occurred in April $ 080bn
Note sales performance fluctuates showing inconsistency in demand or execution which required smoothing through better demand forecasting and sales campaigns.

# CONCLUSION:
The business shows strong potential to thrive in other countries but suffers from inconsistency and lack of stability in a new environment.

# RECOMMENDATIONS:
•	Stability monthly sales address sharp fluctuations by aligning marketing effort and promotional campaigns with seasonal demand trends.
•	Rebuild customer confidences in Germany , while seeking for a better trade deals in Poland and other countries.
