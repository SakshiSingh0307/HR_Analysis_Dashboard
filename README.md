# HR Analysis Dashboard:

1. **Data Loading:**
   - Imported the dataset from Kaggle using the "Get Data" option in Power BI.
   - Verified and ensured correct data types were assigned to each column, such as dates, numeric values, and text fields.

2. **Data Preparation:**
   - Cleaned the data in the "Power Query Editor" by removing unnecessary columns.
   - Handled missing values by replacing nulls and filtering incomplete rows.
   - Created calculated columns for:
     - Attrition rate: `(Total Attrition / Total Employees) * 100`.
     - Income categories based on Monthly Income.
   - Established relationships between tables using "Model View."

3. **Measures Creation:**
   - Defined key DAX measures to calculate important metrics:
     - Total Employees: `COUNT(EmployeeID)`
     - Total Attrition: `SUM(AttritionFlag)`
     - Average Monthly Income: `AVERAGE(MonthlyIncome)`
     - Attrition Rate: `DIVIDE(Total Attrition, Total Employees, 0)`

4. **Building Visualizations:**
   - **Page 1 - Overview Dashboard:**
     - **Attrition by Department:** Bar chart showing attrition counts for HR, R&D, and Sales.
     - **Employees' Age Distribution:** Clustered column chart displaying age bands.
     - **Gender Distribution:** Donut chart showing male vs. female employees.
     - **Key Metrics:** Cards displaying Total Employees, Total Attrition, Average Age, and Attrition Rate.
     - **Attrition by Education Field:** Pie chart showing attrition across fields like Life Sciences, Marketing, etc.

   - **Page 2 - Detailed Analysis:**
     - **Attrition Rate by Age and Gender:** Stacked bar charts segmented by age bands and gender.
     - **Job Satisfaction:** Matrix showing satisfaction ratings by job roles.
     - **Job Involvement:** Bar chart illustrating involvement levels across job roles.
     - **Years in Current Role:** Scatter plot showing age groups vs. years in role.

5. **Slicer Panel:**
   - Added slicers for interactivity:
     - Department, Age, Gender, Date (with default range or date selection).
   - Grouped all slicers into a collapsible panel on the right side for ease of use.

6. **Publishing the Report:**
   - Saved the Power BI file and uploaded it to the Power BI Service workspace.
   - Shared the report with stakeholders and embedded it into a dashboard for easier access.

link of report: https://app.powerbi.com/view?r=eyJrIjoiNTkzMjk5NjEtMGMzYy00MzRlLWJkODctM2U0NWJhNTA5NWYwIiwidCI6ImQ0NzUyNWJmLTYwMmQtNGVkNy04YzYwLTNkYjBlYzM3ZTI2NiIsImMiOjEwfQ%3D%3D

This process helped create an insightful and interactive HR Analysis Dashboard.
