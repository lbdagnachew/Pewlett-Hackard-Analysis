# Pewlett-Hackard-Analysis

# Overview of the analysis:

The purpose of this analysis is to conduct a Database analysis for Pewlett Hackard, a large company, for the upcoming “Silver Tsunami”. A large number of employees are expected to begin retiring. By completing this analysis, the company will identify the number of retiring employees by titles(positions) and determine which employees are eligible to participate in the mentorship program. This will help Pewlett Hackard to prepare a plan to hire new staff and prepare for a mentorship initiative.  
-A query is written and executed to create a Retirement Titles table for employees who are born between January 1, 1952, and December 31, 1955.

# Resorces:

- Softwate: SQL, PostgreSQL and pgAdmin
- Data Source: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv

# Results:

•  By using an online tool called Quick Database Diagrams, we created a conceptual Entity Relationship Diagram (ERD) to design and visualize the database table relationships. 

![EmployeeDB](https://user-images.githubusercontent.com/101952961/169726017-fc1919e6-d7c7-42a9-9f0f-440268bb659c.png)

•	Retiring Positions: Based on our analysis, there is currently a total of 72,458 employees that will retire soon and 70% of this group hold senior positions (50,842/72,458 * 100) = 70.16%. The retiring_titles shows the breakdown below:

![Retiring_Titles](https://user-images.githubusercontent.com/101952961/169729644-1354f102-7d97-4c23-b3fb-e45513baaae6.png)

•	Mentorship Eligibility: Below is the list of employees that can qualify to become members of the mentorship program. Most of these employees have senior titles.

![Mentorship_Eligibility](https://user-images.githubusercontent.com/101952961/169731049-8fb013c7-f445-49f7-be23-0b873e4fbf4a.png)


# Summary:

There are 72,458 roles that are in urgent need to be filled out as soon as the workforce starts retiring at any given time. Since a large number of future retirees hold Senior positions, there should be enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees
