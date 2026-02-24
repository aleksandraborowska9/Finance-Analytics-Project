# Executive Financial Control Tower – Power BI

##  Project Overview
This project delivers an executive-level **Financial Control Tower dashboard** built in Power BI. 

The solution enables leadership to monitor financial performance, compare Actual vs Budget, track forecast accuracy, analyze regional and product performance, and simulate revenue growth scenarios, all within a secure and enterprise-grade BI framework.

The dashboard demonstrates advanced DAX, proper star schema modeling, time intelligence implementation, scenario planning, and Row-Level Security (RLS).

---

##  Project Objectives
The dashboard enables executives (CFO-level audience) to:

- Monitor Revenue, Cost, Profit, and Gross Margin
- Compare Actual vs Budget
- Track Forecast Accuracy
- Analyze Regional and Product Performance
- Perform Time-Based Analysis (YTD, YoY, Rolling 12 Months)
- Simulate Revenue Growth Scenarios (What-if Analysis)
- Secure data access using Row-Level Security (RLS)

---

##  DAX Implementation (25+ Measures)

### Core Financial Measures
- Total Revenue  
- Total Cost  
- Total Profit  
- Gross Margin %  
- Total Budget  
- Total Forecast  
- Budget Variance  
- Budget Variance %  
- Forecast Accuracy %  

### Time Intelligence
Implemented using:
`TOTALYTD`, `SAMEPERIODLASTYEAR`, `DATEADD`, `DATESINPERIOD`

Measures include:
- Revenue YTD  
- Revenue Previous Year  
- Revenue YoY %  
- Rolling 12 Months Revenue  
- 3-Month Moving Average  
- YTD Profit  

### Contribution & Ranking
- Revenue Contribution % by Region  
- Revenue Contribution % by Product  
- Top N Product Logic  

### Dynamic KPI Selector
- Disconnected KPI Table  
- Toggle between Revenue / Profit / Margin %  
- Implemented using `SWITCH()` and `SELECTEDVALUE()`  

### What-If Scenario Planning
- Revenue Growth % parameter  
- Adjusted Revenue  
- Adjusted Profit  
- Profit Impact analysis  
- Scenario comparison visual  

---

##  Row-Level Security (RLS)

Implemented role-based access control:

**Role: Region Manager**
- Users can only view data for their assigned region
- Tested using “View as Role” functionality


---

##  Key Skills Demonstrated

- Advanced DAX and Time Intelligence
- Star Schema Data Modeling
- Performance-focused BI design
- Financial KPI engineering
- Scenario simulation modeling
- Enterprise Row-Level Security

---

##  Business Value

This solution provides leadership with:

- Real-time financial performance visibility
- Improved budget control
- Better forecasting insight
- Scenario-based strategic planning
- Secure, role-based data access
- Data-driven executive decision support
