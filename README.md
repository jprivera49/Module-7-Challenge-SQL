# Module-7-Challenge-SQL
Determine the total number of employees per titles who will be retiring and identify employees who are eligible to participate in a mentorship program.

### Steps taken to solve the problem and the challenges encountered
First I needed to filter the data csv's and find employees whose dates fell into a specific birthdate.  I then moved this into retirement_info folder.  Then I had to join the retirement and deptartment employee tables and then filter this table based on them currently working for the company.  This information was added to a new table.  I then was able to find employees who are able to reitre and filter by their titles.

To be eligible to participate in the mentorship program, employees will need to have a date of birth that falls between January 1, 1965 and December 31, 1965.  I joined the dept_emp table and the title table and then filtered by the birthdate listed above.  A new table, mentorship, was created.  

### Results of analysis
Based on my analysis, 54,722  employees are set to reitre, with 7 different titles being affected.  2,382 employees are eligible for the mentorship program, based on the dates set.

### ERD Mapping Out Database
![ERD].https://raw.githubusercontent.com/jprivera49/Module-7-Challenge-SQL/master/QuickDBD-export%20(1).png
