# HR Analytics: Employee Attrition Dashboard

### Project Overview
This project involves the creation of an interactive HR Analytics Dashboard designed to track
and analyze employee attrition. By examining various data points such as department, job
satisfaction, age, and salary, the dashboard provides the HR department with actionable
insights to identify high-risk groups and improve employee retention strategies.

### Data Transformation & DAX Measures
Before visualization, the raw data was transformed to create high-value KPIs:
Attrition Count: Created a conditional column to binarize attrition ( 1 if Yes, 0 if No).
Attrition Rate: Developed a DAX measure to calculate the percentage of attrition relative
to the total employee count:
Formula: AttritionRate = SUM(AttritionCount) / SUM(EmployeeCount)
Averaging Logic: Calculated average age, average salary, and average years at the
company to establish organizational benchmarks.

### Key Performance Indicators (KPIs)
The dashboard visualizes the following critical metrics:
1. Workforce Overview: Total Employees and Total Attrition.
2. Attrition Rate: A real-time percentage of staff turnover.
3. Employee Profile: Average Age, Average Salary, and Average Tenure.
4. Attrition Drivers: Analysis of attrition categorized by:
Education Field & Age Group.
Salary Slabs (Income brackets).
Years at Company & Gender.
Job Role & Department.
5. Employee Sentiment: Job Satisfaction scores segmented by specific Job Roles.

### Dashboard Features
Interactive Slicers: A department-level slicer allows HR managers to drill down into
specific teams (e.g., Sales, R&D, HR).
Comparative Analysis: Visuals comparing turnover rates across different salary levels and
age demographics.
Role-Based Insights: Identifying which specific job roles suffer from the lowest
satisfaction and highest turnover.

### Tech Stack
Tool: Power BI Desktop
Data Cleaning: Power Query Editor (Conditional Columns, Data Type formatting).
Analytics: DAX (Data Analysis Expressions).
Visuals: KPI Cards, Donut Charts, Bar Charts, and Tree Maps.

### Project Structure
HR_Analytics_Dashboard.pbix : The primary Power BI file.
dataset/ : The raw HR data (CSV/Excel).
screenshots/ : Visual overview of the completed dashboard.

### How to View
1. Clone the repository.
2. Open the .pbix file using Power BI Desktop.
3. Use the Department Slicer to filter the entire report for a specific business unit.

### About the Author
Dhiraj Bhise 
LinkedIn:  www.linkedin.com/in/dhiraj-bhise-335532306


