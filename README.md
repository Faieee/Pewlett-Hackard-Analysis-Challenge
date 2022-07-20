# Pewlett-Hackard-Analysis-Challenge
## Overview of the analysis
The .csv files present in the [Data](/Data) folder outline employees readying for retirement in the next few years. [unique_titles.csv](/Data/unique_titles.csv) contains a list of employees that is ready for retirement, [retiring_titles](/Data/retiring_titles.csv) contains a count of retiring employees by job title, and [mentorship_eligibility.csv](/Data/mentorship_eligibility.csv) contains a possible list of employees to be considered for the upcoming Mentorship Program.
## Results
- A total of 72,458 employees of age 70-73 are going to begin the process of retirement.
- As seen in the Retiring Titles table, the majority of employees will be leaving with the Senior Engineering and Senior Staff titles.
![](/Data/retiring_titles.png)
- Nearly no registered managers will be retiring, although the previously discussed issues with manager classification may lend this to further analysis.
- A total of 1,549 employees can be considered for the mentorship program.
## Summary
### Adressing the "Silver Tsunami"
As the "silver tsunami" takes effect, the majority of roles that need to be filled are going to be in the Senior Engineering and Senior Staff positions. When looking at the current distributions of employees, 

![](/Data/current_titles.png)

it is clear that there are pleny of employees to fill the ~25,000 Senior Engineer and Senior Staff positions from their corresponding non-senior positions.
### Viability of Mentorship Program
![](/Data/mentorship_departments.png)
Querrying the members of the mentorship program by department shows a relatively healthy spread of qualified employees by department, with plenty of employees in the Development department to take care of all the future Engineering vacancies. By having these employees train replacement employees for Senior positions over the course of the next few years, these positions can be easily replenished.
