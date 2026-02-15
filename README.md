# hr-analytics-powerbi-dashboard 🚀

**HR Analytics Dashboard built using Power BI.**  
Includes data cleaning, modeling, KPIs, and interactive visualizations for workforce, finance, and attendance analysis. 📊

## Project Overview 👩‍💻
This is my first Power BI project: an HR Analytics Dashboard designed to analyze workforce, finance, and attendance data. The project uses three main datasets: Employees, Salaries, and Timesheets, and demonstrates data cleaning, modeling, and visualization skills.

## Project Details 📝

### Datasets 📂
- Employees – Cleaned and standardized data, including employee IDs, names, age, gender, contract status, country, and join date.  
- Salaries – Monthly salary data for employees across different months, linked to Employees by ID.  
- Timesheets – Attendance data including employee ID, workdays, and attendance percentage, also linked to Employees.

### Data Cleaning & Transformation 🧹
- Removed duplicate records  
- Standardized text and data types  
- Prepared tables for accurate modeling and analysis

### Data Modeling 🔗
- Established one-to-many relationships between Employees and Salaries, and Employees and Timesheets  
- Enabled accurate aggregation and KPI calculations

### Key Performance Indicators (KPIs) & Dashboards 📈

**Overview Dashboard**  
- Total Employees   
- Average Age 
- Average Salary   
- Gender Ratio 
- Contract Status 
- Headcount by Country

**Finance Dashboard**  
- Total Monthly Payroll   
- New Hires (2025)  
- Hiring Velocity 
- Total Paid Salaries 
- Last Month Paid Salaries   
- Salary Paid by Country  
- Salary per Employee 

**Attendance Dashboard**  
- Average Attendance 
- Attendance by Gender 
- Monthly Attendance Trends  
- Attendance by Country 
- Individual Attendance Records 

## Key Measures ⚡

1. Average Salary (in Employees table)  
Average Salary = DIVIDE(SUM(Employee[Salary_USD]), COUNT(Employee[ID]))  
Calculates the average salary of all employees.

2. Total Working Days (in TimeSheet table)  
Total Working Days = SUM(TimeSheet[workingdays])  
Calculates the total working days of all employees.

3. Attendance % (in TimeSheet table)  
Attendance2 % = DIVIDE(AVERAGE(TimeSheet[workingdays]), 22)  
Calculates average attendance percentage assuming 22 working days per month.

## Skills Demonstrated 💡
- Data cleaning and preparation  
- Data modeling with Power BI  
- Creating KPIs and interactive dashboards  
- Analytical thinking and insight generation  

---

**Author:** 
Eng.Lamees Khalid 
