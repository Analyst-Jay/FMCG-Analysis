FMCG SALES INTELLIGENCE PORTFOLIO DATASET
=============================================

Purpose
-------
Synthetic, portfolio-ready FMCG field-sales data built to support an end-to-end
Power BI project: Excel import, Power Query cleaning, star-schema modelling,
DAX, KPI design, distributor analysis, sales-team analysis, page navigation,
custom tooltips, and Power BI Service publishing.

Reference video
---------------
https://www.youtube.com/watch?v=nEXcXGcB220

Video workflow verified from the published chapter list:
dataset understanding -> Excel PivotTables -> import -> Power Query -> cleaning/
transformation -> first visual -> Star Schema -> fact/dimension organization ->
DAX -> KPI measures -> Executive Dashboard -> Distributor Dashboard -> Sales
Team Dashboard -> navigation -> custom tooltips -> Power BI Service.

Core business tables
--------------------
Primary_Sales
Secondary_Sales
Target
Coverage_Productivity
Product_Master

Supporting dimension tables
---------------------------
Distributor_Master
Sales_Rep_Master
Outlet_Master

Important note about header matching
------------------------------------
The public indexed page for the video exposes the project workflow and business
areas but does not expose the raw Excel header list. Therefore this pack includes
a broad, portfolio-ready superset of FMCG field-sales columns covering all of the
business concepts explicitly identified for the tutorial. I cannot honestly claim
byte-for-byte header matching to the creator's private source file.

Data quality practice
---------------------
Some raw fields intentionally contain:
- leading spaces
- mixed letter casing
- blanks
- text/format inconsistencies
These are deliberate so you can practise Power Query cleaning and type conversion.

Recommended Power BI model
---------------------------
Dimensions: Product, Distributor, Sales Rep, Outlet, Date
Facts: Primary Sales, Secondary Sales, Target, Coverage/Productivity

Row counts
----------
Primary_Sales: 3000
Secondary_Sales: 3000
Target: 1800
Coverage_Productivity: 3000
Product_Master: 1500
Distributor_Master: 1500
Sales_Rep_Master: 1500
Outlet_Master: 2000

Suggested report pages
----------------------
1. Executive Overview
2. Distributor Analytics
3. Sales Team Analytics
4. Product & Secondary Sales (recommended extension)
5. Coverage & Productivity (recommended extension)
6. Insights / Management Summary (recommended extension)

Sources checked
---------------
Video:
https://www.youtube.com/watch?v=nEXcXGcB220

Creator resource page:
https://analyticalguy.tech/powerbi

FMCG field-sales warehouse reference:
https://github.com/sadaatalsyed/FMCG_FieldSales_DWH
