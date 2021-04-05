# Pewlett-Hackard-Analysis

## Overview of the Analysis

Now that Bobby has proven his SQL chops, his manager has given both of you two more assignments: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, you’ll write a report that summarizes your analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

## Results

Based on the results of the SQL analysis: 
- There are 133,776 different retirement titles for all the titles of current employees who were born between January 1, 1952 and December 31, 1955 including previous titles from before promotions

![retirement_titles](https://user-images.githubusercontent.com/76754655/113525961-e5970200-9585-11eb-8b79-8aad7f5d94f4.PNG)

- There are 90,398 unique retirement titles for the all the unique most recent titles of current employees who were born between January 1, 1952 and December 31, 1955

![unique_titles](https://user-images.githubusercontent.com/76754655/113525964-eaf44c80-9585-11eb-9724-930d6af524d7.PNG)

- There are 7 different titles with Senior Engineer and Senior Staff being the most number of unique most recent titles of current employees who were born between January 1, 1952 and December 31, 1955 and only 2 Managers

![retiring_titles](https://user-images.githubusercontent.com/76754655/113525968-ef206a00-9585-11eb-993f-7e5be6097c50.PNG)

- There are 1,940 employees who are eligible to participate in a mentorship program based on current employees whose birth dates are between January 1, 1965 and December 31, 1965

![mentorship_eligibility](https://user-images.githubusercontent.com/76754655/113525972-f2b3f100-9585-11eb-9b9e-a3550e18c076.PNG)

## Summary
Based on the following questions:
- How many roles will need to be filled as the "silver tsunami" begins to make an impact?
  -  There will need to be 90,398 roles filled as the "silver tsunami" begins to make an impact based on the number of employees retiring soon 
- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
  - There are only 1,940 qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees, and considering 90,398 unique retirement titles for all the unique most recent titles of current employees who were born between January 1, 1952 and December 31, 1955 who are ready to retire, it seems like there may need to be at least 10 times as many qualified, retirement-ready employees in the departments to mento the next generation of Pelett Hackard employees if there are more than 1 mentees per mentor for the mentorship program

Additional queries/tables that may provide more insight into the upcoming "silver tsunami":
- Is there a table for the number/date of individuals currently being hired to replace retiring employees?
- Is there a table to determine the budget for each department to hire additional individuals?
