# Overview
In this assignment, we practiced proficiency in using postgreSQL 11 by creating tables, importing data with csv files, joining tables with primary and foreign keys, and leveraging 
filters to generate more specific queries. The assignment called for determining the number of retiring employees per title, and identify employees who are eligible to participate
in a mentorship program set by leadership at the company. This analysis will also serve to assist in business strategy by identifying how many employees will be leaving and if 
the current staffing supports this 'silver tsunami'. 

# Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.
- There are a total of 72,458 employees reaching retirement.

![Total Count of Retiring Titles](https://i2.paste.pics/d40afc7fe8108a7afc4715bf55316387.png)

- There are not very many candidates available for the proposed mentorship program compared to the number of retiring employees (1549).
 
![Count of Mentorship Eligibility](https://i2.paste.pics/974482aa14e9a6e61ed011287e33a4f8.png)

- There are no managers eligible for the mentorship program. 

![List of Titles in Mentorship Eligibility](https://i2.paste.pics/3c6932728b26f94bebf268fc78dc1b00.png)

- There are 36291 engineers retiring. 

 ![Count of Retiring Engineers](https://i2.paste.pics/54451ca2f6a8d2cf3b28ca3d3e163a1f.png)
 
 
# Summary

- How many roles will need to be filled as the "silver tsunami" begins to make an impact?
  - A total of 72,458 roles will need to be filled as the "silver tsunami" starts to take affect on Pewlett Hackard. This information is based on active, current employees who have birth years between 1952 and 1955. The total amount of active employees are 240,124. 30% of the current employees are reaching retirement soon. 

 ![Count of Total Active Employees](https://i2.paste.pics/d13fcd83cd409ce1cb6112fcf42689a9.png?trs=ff39213388cbc5f55e1200b85364ec13d96bd07a4cd8d4ffce416a4f0ec05501)
 
- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
  - The amount of eligible candidates for the mentorship program is only 1549, 2% of the retiring employees. Also, from the previous point, there are no retiring managers available for the mentorship program. From a query to establish a count of eligible mentorship candidates by title, the engineer title has the highest percentage (9%) available to serve as mentors for employees.
 
 ![Count of Titles in Mentorship_Eligibility](https://i2.paste.pics/b1883a3ccef03900e7f18334c601bb9f.png) 
