# Nexoria Group: Executive Performance & Strategic Outlook Suite
## Project Overview
In a global corporate environment, the transition from "Historical Data" to "Future Strategy" is the biggest challenge for leadership. This Power BI suite provides a 360-degree view of the Nexoria Group,
moving beyond simple reporting into Strategic Storytelling By integrating financial KPIs with operational health metrics, this dashboard enables the Board of Directors to identify margin leakage, 
track executive accountability, and forecast future resource requirements during high-pressure "Board Seasons."
## Datasets Description
![](https://github.com/Ebenezer080925/Nexoria-Group-Executive-KPI-Report/blob/main/Data%20Description%201.png)
![](https://github.com/Ebenezer080925/Nexoria-Group-Executive-KPI-Report/blob/main/Data%20Description%202.png)
## RELATIONSHIP OF TABLES
This image displays a Star Schema data model in Power BI, where a central FactKPI_Monthly table is connected to four supporting dimension tables. These relationships use a one-to-many (1:*) cardinality, 
meaning each unique descriptive attribute filters multiple rows of monthly performance data. The DimDate, DimOrg, DimRegion, and DimKPI tables serve as "lookup" tables to provide context like time, department, 
location, and specific metric definitions. By connecting these tables via Keys (such as MonthKey or OrgKey), the model allows for efficient filtering and complex data analysis across different business views.
![](https://github.com/Ebenezer080925/Nexoria-Group-Executive-KPI-Report/blob/main/ERD.png)
# Overview Dashboard
1.Executive Overview (The "North Star")
Objective: Provide an immediate pulse-check on global growth and profitability.

Key Metrics & Insights:
Total Actual Revenue: $19.81BN (Beating the $19.57BN budget by +1.2%).

Operational Profit (EBITDA): $5.04BN, successfully exceeding the $4.91BN target.

Efficiency (Gross Margin %): 54.63%, maintaining a healthy margin above the 53.66% budget.

Workforce Scale: Total Headcount of 84.29 vs. a budget of 83.57.

Organizational Breakdown:
Using ZoomCharts Drill-Down technology, the board can pivot across 18 Business Units.

Top Performer: The Commercial division is the primary engine, contributing over $4.74BN in revenue.

Product Insights: SMB Sales ($1.91BN) and Charts ($1.77BN) lead the product portfolio, while the Core Platform ($1.49BN) remains a stable foundation.
![](https://github.com/Ebenezer080925/Nexoria-Group-Executive-KPI-Report/blob/main/Executive%20Overview%20Page%20.png)

#Performance Deep-Dive
Objective: Identify and isolate the root causes of budget variance.

Variance Analysis:
Net Revenue Variance: $237.44M (Positive variance of 1.21%).

YOY Growth: A massive 104.64M increase in variance compared to the previous year, showing accelerating momentum.

Geographic Performance: The APAC region shows the strongest budget alignment, while AMER remains a key area for margin recovery.

Root Cause Detection: The Waterfall Analysis highlights that while Technology and Operations are driving gains, the Commercial division is facing specific "ProductLine" pressures that require executive intervention.
![](https://github.com/Ebenezer080925/Nexoria-Group-Executive-KPI-Report/blob/main/Performance%20Deep-Dive.png)

# Strategic planning and  OPeration
Objective: Align operational health with future revenue forecasts for Board Season.

Forecasting & Resource Planning:
Forecast vs. Budget Gap: A narrow gap of $241.45M exists between current projections and original plans, signaling high confidence in meeting year-end targets.

Productivity Risk: The Headcount vs. Revenue area chart reveals a critical trend: Headcount peaked at 88 in March while Revenue hit $1.87BN. Subsequent dips in revenue without proportional headcount reductions suggest a need for a hiring freeze in underperforming units.

Operational Stability:
Customer Health: EMEA leads in Active Customers, but AMER shows the highest potential for Net Customer Adds.

Forward Strategy: By filtering for "Board Season" (IsBoardSeason = 1), the visual isolates the critical Feb/Mar window where 2026 strategic pivots must be finalized.
![](https://github.com/Ebenezer080925/Nexoria-Group-Executive-KPI-Report/blob/main/Strategic%20PLanning%20and%20Operation.png)

# Final Recommendations for Nexoria Board
Capitalize on APAC Momentum: Shift additional marketing resources to APAC where the "Actual vs. Budget" variance is most favorable.

Operational Efficiency: Realign the Operations division headcount, as the current revenue-per-employee ratio has dipped since the Q1 peak.

Margin Protection: Focus the Commercial team on the "Core Platform" and "Security" product lines, which show the highest stability in Gross Margin %.


https://drive.google.com/file/d/14hJIi9692gVUW-nZGbXalB_ZnlPGtnHY/view?usp=sharing
