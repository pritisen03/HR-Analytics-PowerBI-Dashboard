# HR Analytics & Workforce Insights Dashboard

An interactive Power BI dashboard analysing employee attrition using the IBM HR Analytics dataset (1,470 employees).

## Objective
Identify which departments, roles and working conditions are linked to higher employee attrition.

## Dashboard Preview
![Dashboard](images/page1.png)
![Key Insights](images/insights.png)

## Key Insights
- Overall attrition rate is 16.12% (237 of 1,470 employees left)
- Sales has the highest attrition rate (20.63%). R&D has the most leavers by count, but the lowest rate (13.84%)
- Employees working overtime leave at 30.53% vs 10.44% for those who don't, roughly 3x higher
- Laboratory Technician, Sales Executive and Research Scientist roles account for the most leavers

## Recommendations
- Review overtime policies and workload balance
- Run retention programs for the Sales department
- Focus on Lab Technician and Sales Executive roles with exit interviews and growth plans

## Tools Used
Power BI, DAX, Data Modelling

## DAX Measures
Attrition Rate = DIVIDE([Employees Left], [Total Employees])
