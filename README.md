Superstore Sales & Profitability Analytics
Power BI | DAX | Power Query | Data Modeling | What-If Analysis

An interactive business intelligence portfolio project for exploring sales performance, profitability, customer segments, and pricing scenarios. The Power BI .pbix source file is not publicly shared.
Business Objective
Help business stakeholders answer four questions:
- How are sales, profit, orders, and margins performing?
- Which regions and segments contribute most to revenue and profitability?
- Where should management investigate underperformance?
- How might changes in price, quantity, and discounts affect financial outcomes under stated assumptions?
Dashboard Preview
Sales Overview

Customer Analytics

What-If Scenario

[Watch the dashboard demonstration](Superstore.mp4)
Key Performance Indicators
KPI	Displayed value
Total Sales	$2.3M
Total Profit	$286.4K
Profit Margin	12.5%
Total Orders	5,009
Average Order Value	$458.6
Average Discount	15.6%


Values above are reproduced as displayed on the dashboard with filters set to All.
Key Business Findings
- West leads the regions, with $725K in sales and $108K in profit.
- Central has the weakest regional profit margin among the four displayed regions: $501K in sales and $40K in profit, equivalent to approximately 8% when calculated from the displayed rounded values. This suggests a need to investigate its product mix, discounts, and costs.
- Sales increased 46.9% year over year, and profit increased 48.4%.
- Orders increased 50.8% year over year, while average order value decreased 2.6%. This suggests that volume contributed more to growth than basket value.
What-If Scenario Analysis
The report uses DAX measures and interactive parameters to test hypothetical changes to pricing, sales quantity, and discount levels.
Scenario input	Selected change
Price	+25%
Quantity	-5%
Discount	+2 percentage points


Simulated outcome	Dashboard impact
Sales	+$362.7K (+15.8%)
Profit	+$463.2K (+161.7%)
Profit margin	+15.7 percentage points (+126.1% relative change)
Quantity	-1,894 (-5.0%)


Interpretation: Under these assumptions, the model indicates a potential increase in sales and profit, even with lower quantity. These are hypothetical model outputs, not realized business results or a validated forecast.
Modeling Assumptions and Limitations
- Simulated sales apply price and quantity multipliers and adjust discounts relative to each row's original discount.
- Simulated profit subtracts historical implied costs scaled by the quantity change. This treats costs as proportional to quantity and does not separately model fixed costs.
- Customer price sensitivity, demand elasticity, competitor responses, and other real-world effects are not independently estimated.
- Reported figures are the dashboard's displayed values; some values are rounded.
Tools and Techniques
- Power BI: interactive dashboard and KPI reporting
- Power Query: data preparation
- DAX: measures, year-over-year analysis, and What-If calculations
- Data modeling: analytical relationships supporting reporting
- Business analytics: regional performance, customer analysis, and scenario evaluation
Business Value
This project demonstrates how a decision-maker can monitor business performance, locate profitability gaps, and explore pricing scenarios before taking action. It is a portfolio demonstration, not a claim of measured savings or profit achieved for a client.
Author
Zahra Oumous — Data Analytics | Power BI | SQL Server | Python
