# HR-Analytics-Dashboard
## Excel Dashboard from start to end Project | HR Analytics Dashboard 

### Project Overview
#### We will see the design and development of a beautiful dashboard in Microsoft Excel as we can see from the topic: HR analytics dashboard. I have used some of the slicers on this dashboard which when operated with respect to this particular slicers like for gender you can see this is completely Dynamic and I have used some extra filters as well and if I'm operating this you can see the data is changing with respect to that education field and you can take a Insight from this particular dashboard or HR department can take Insight from this dashboard like with respect to education Fields how the company is performing and this dashboard is focused on attrition right so iteration is nothing but the employees who are leaving the company so how many employees are living by age, by gender, by marital status by job role Etc so we have one more sliser like Department if you can see whenever I'm operating this the values are changing with respect to that aspect all right so let's discuss on different components which are there on this particular dashboard.

### About the Data
#### The data which I have already converted into a Table by pressing Ctrl T. The total amount of data which we are having it is almost almost 1500 data is there and  we have almost 44 columns. The columns includes:Attrition,	Business Travel,	CF_age band,	CF_attrition label,	Department,	Education Field,	emp no,	Gender,	Job Role,	Marital Status,	Over Time,	Training Times Last Year,	CF_attrition count,	CF_current, Employee	Daily Rate,	Distance From Home,	Education,	Environment Satisfaction,	Hourly Rate,	Job Involvement,	Job Level,	Job Satisfaction,	Monthly Income,	Monthly Rate,	Num Companies Worked,	Percent Salary Hike,	Performance Rating,	Relationship Satisfaction,	Stock Option Level,	Total Working Years,	Work Life Balance,	Years At Company,	Years In Current Role,	Years Since Last Promotion,	Years With Curr Manager,	Age,
<img width="32766" height="22" alt="image" src="https://github.com/user-attachments/assets/a57f73b2-1565-4b43-b94b-1d1de394e7f8" />


### Analysis Plan and Insights
1) Create KPI
2) Add Employee Number
3) Convert to Percentage
4) Create Dashboard Background
5) Copy Background from PowerPoint
6) Creating Pivot Table
7) Creating Star Rating Chart
8) Creating Chart(Pie Chart, Education Chart, Departmentwise Attrition, Bar Chart, Funnel Chart,Slicers)

### Formulae Used
=GETPIVOTDATA("emp no",$A$3)
=IFERROR(GETPIVOTDATA("Attrition",$A$3,"Gender","Female"),0)
=4-B25
Build a dashboard to showcase key metrics:

Dashboard Visualization
Insights from the Analysis

