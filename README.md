# Pewlett-Hackard-Analysis

#### Overview
The purpose of this analysis was to provide insight for Pewlett-Hackard's upcoming wave of employees who are expected to retire in the near future. Initial findings indicated that over 70,000 employees were approaching retirement age, many of whom filled critical roles in the company. Such a loss of experience and manpower could be expected to have drastic affects on the company's ability to fulfill its production obligations. Thus, the leadership team needed to take action, but they required an analysis of the available data in order to make informed decisions. This data consisted of relavent stored tables of department, employee, manager, salary, and title information. 

![Graph to show number of retiring employees by title](https://github.com/veachk90/Pewlett-Hackard-Analysis/blob/main/retirement_titles_graph.png)

#### Decisions
With this information, company leadership found it prudent to implement a mentorship program in order to train the next employees to fill the roles that would be left vacant. This would entail offering those employees preparing to retire the opportunity to continue working part-time in a mentoring capacity. It would also include finding internal candidates to mentor with the goal of filling these positions. 

#### Findings
Deliverable 1:
- Of the total number of employees expected to retire soon, about 72,000, only 2 of them were department managers. Thus, the overwhelming majority of these retiring employees were involved in the company's production. Indeed, the mode of job titles among them was Senior Engineer. This indicates that the affects of the 'silver tsunami' could not be mitigated by merely restructuring the management.
- Of the employees expected to retire soon, about 20,000 are in standard roles, not senior roles. It may be the case that not all of them are suited to becoming mentors. However, they still provide significant manpower, and could be worth retaining through other methods, such as creating remote positions (if this has not been done already), moving to part-time status, or possibly promoting those qualified to do so. Because the primary concern is whether Pewlett-Hackard will be able to meet its production, offering early retirement to these employees would be counter-productive.

Deliverable 2:
- The initial proxy for determining whether a candidate is eligible for consideration for the mentorship program is their age. Since most of the retirees fill senior positions, it makes sense that the future candidates would need to have a good amount of experience in their fields and in the company. 
- Some of the candidates in the mentorship_eligibility table are not in senior roles at the time of this analysis. Thus, it is possible that, despite their experience, some of them may not be suited for the program. The tables shows the current positions for these employees, but it is also possible that some of them had previously stepped down from senior positions, and could be worth offering enrollment into the mentorship program.

The summary addresses the two questions and contains two additional queries or tables that may provide more insight. (5 pt)
There are 72,458 roles that will need to be filled in the near future as the older employees begin to retire. After producing the table for those employees eligible for the mentorhsip program, a total of 1,549 employees were found. While this poses a significant discrepancy between role vacancies and employees to fill them, the table of eligible employees was based solely on those who were born in 1965. The age range could, of course, be expanded to include a wider group. If the data is available, other criteria, such as performance-based awards count, could be considered as well to expand the pool of candidates. Currently, there are 300,024 employees in the company. It is likely that Pewlett-Hackard will need to hire a significant number of external employees to fill the production demand. 
