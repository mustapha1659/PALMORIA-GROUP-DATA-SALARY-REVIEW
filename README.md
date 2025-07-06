# PALMORIA-GROUP-DATA-SALARY-REVIEW

Project Overview:
This overview presents an analysis of HR data from Palmoria Group, with the aim of identifying gender inequality issues and evaluating the company's salary structure across its three regions. The analysis uses employee demographic and compensation data to uncover disparities and proposes actionable insights supported by interactive Power BI visualizations. It also calculates employee bonuses based on provided bonus rates and determines the total bonus payout per region and company-wide.

### Data sources:
- Employee Data: Palmoria_Group_Employees.csv
- Bonus Rates: Palmoria_Bonus_Rates.xlsx

### Tools used:
- Power BI: For data transformation, visual exploration, and interactive dashboard creation.
- Microsoft Excel: For initial data cleaning and bonus rate mapping.

### Data cleaning and Preparation:
The following steps were taken during data cleaning:
- Generic Gender Assignment: Assigned a generic gender status to employees
- Removal of Invalid Entries:
- Excluded employees without salary allocation.
- Removed entries with NULL values in the department field.
- Merged data queries
- Cleaned and imported datasets into Power BI for modeling and visual analysis.

### Exploratory Data Analysis:
- Gender Distribution by Region and Department
Power BI bar and pie charts revealed imbalances in gender distribution across regions and departments. Region 1 and IT departments showed strong gender disproportions.
- Gender Pay Gap Analysis
Power BI box plots and DAX calculations were used to compare average salaries by gender. A noticeable gender pay gap was found in Region 1 and Region 2, especially in Finance and Engineering roles.
- Bonus Calculation
Bonus amounts were calculated using DAX measures in Power BI:
Bonus = Base Salary × Bonus Rate
- Bonus rates were joined with the employee dataset using role/grade as the key.

### Recommendation:
- Regular audits to ensure gender pay equity across roles and levels.
- Continue using Power BI dashboards for live tracking of gender and salary metrics.




