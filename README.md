# Power-bi-employee-report
1. Project Title:
   Workforce Analytics Dashboard – Interactive Power BI dashboard analyzing employee count, salary trends, work modes, and performance ratings across departments and locations.

2. Purpose: This Power BI dashboard provides a comprehensive view of workforce distribution, salary trends, and employee performance across departments, locations, and work modes. It highlights key metrics such as average compensation, employee count, and performance ratings. The dashboard enables HR and leadership teams to monitor workforce health, identify performance gaps, and make data-driven decisions to optimize employee engagement and organizational growth.
   
3. Tech Stack :
Power BI Desktop – Used to design and build the interactive dashboard with visuals and KPIs.
Power Query (M Language) – Performed data cleaning, transformation, and shaping before loading into the model.
DAX (Data Analysis Expressions) – Created calculated columns,measures.
Power BI Visuals – Designed charts and KPIs for trend analysis.

4. Data Source :
   https://www.kaggle.com/datasets/rohitgrewal/hr-data-mnc

5. Business Problem:
Organizations often struggle to gain a clear, consolidated view of their workforce data. Information about employee distribution, salary structures, and performance ratings is usually scattered across systems, making it difficult for HR and management to identify trends, ensure pay equity, monitor performance, and optimize resource allocation. This lack of visibility can lead to inefficiencies, disengagement, and missed opportunities for improving workforce productivity.

Goal of the Dashboard:
i. The goal of this dashboard is to provide a centralized, interactive view of employee data, enabling leadership and HR teams to:
ii. Track workforce distribution by department, location, and work mode.
iii. Monitor salary trends and performance ratings at both overall and departmental levels.
iv. Identify workforce imbalances, pay disparities, and performance gaps.
v. Support data-driven decisions that enhance employee engagement, efficiency, and organizational growth.

Walkthrough of the key visuals:
Header KPIs (Top Row)
 Total Employees: 2.0M
 Average Rating: 3.0
 Average Salary: 0.9M
These KPIs give a quick snapshot of workforce size, performance, and compensation.

1. Left Section (with Bookmark Buttons)
This section is interactive, allowing you to toggle between three views using bookmarks:
i.By Department (Horizontal Bar Chart)
Shows the employee distribution by department.
IT has the highest count (0.6M), followed by Sales (0.4M) and Operations (0.3M).
R&D has the least (~0.1M).
ii.By WorkMode (Donut Chart)
Displays employees by their working mode (e.g., On-site, Remote, Hybrid).
Provides a quick proportional view of workforce distribution across work arrangements.
Useful to understand workplace flexibility trends.
iii.By Status (Column Chart)
Shows employee counts by status (Active, Resigned, Retired, Terminated).
Helps track attrition and workforce stability.
Likely shows that the majority are Active, while the other categories (Resigned, Retired, Terminated) are much smaller.

2. Salary by Department (Bar Chart)
Displays average/total salaries by department.
IT leads with the highest salary (1.13M), followed by Finance (0.94M).
HR has the lowest salary (0.74M).

3. Right Section
Count of Employees by Department and Status (Stacked Bar Chart)
Shows the breakdown of employees in each department by status: Active, Resigned, Retired, Terminated.
IT and Sales have the highest number of active employees.
Departments like Finance, Marketing, and Operations also show notable activity but smaller in size compared to IT & Sales.
4. Bottom Section
Performance Rate by Department (Ribbon Chart)
Visualizes how performance ratings (1–5) are distributed across departments.
IT and Sales have a higher count of employees across all ratings.
Ratings gradually reduce in smaller departments like HR and R&D.
The flow highlights how performance varies department-wise, with IT and Sales dominating.

Business Impact: This dashboard provides leaders with a clear view of workforce distribution, salaries, and performance, enabling data-driven decisions around talent management. For example, IT and Sales hold the largest share of employees and highest salaries, highlighting where the majority of investment lies. By monitoring status trends (active vs. resigned/terminated) and work modes, businesses can identify retention risks, optimize workforce allocation, and design policies that improve employee satisfaction. Overall, the insights help in balancing costs, improving performance, and strengthening workforce planning.

6. Screenshots/Demos
   Dashboard preview: https://github.com/anushagc04-pbi/Power-bi-employee-report/blob/main/Snapshot%20Of%20The%20Employee%20Report.png

