# Pewlett-Hackard-Analysis
## Project Overview
To determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program as an alternative to immediate retirement.

## Resources
- Data Files: https://github.com/mcarson16/Pewlett-Hackard-Analysis/blob/main/Data.zip
  - Original Files: departments.csv, dept_manager.csv, dept_emp.csv, titles.csv, salaries.csv, and employees.csv
- pgAdmin 4
- Visual Studio Code

## Results
![image](https://user-images.githubusercontent.com/83254435/122701000-f31d6900-d211-11eb-8ec0-dd6b7b01825b.png)
- A total of 90,398 employees will be eligible for retirement.
- The majority of potential retirees come from the Engineer title, followed by Senior Staff.

![image](https://user-images.githubusercontent.com/83254435/122701473-f1a07080-d212-11eb-9e75-7bef99e6d2e7.png)
- Of the potential retirees, 1,549 are eligible for the mentorship program.
  - If all eligible Senior Staff participate in the mentorship program, it will recuperate 2% of potential staffing losses.
  - If all eligible Engineers participate in the mentorship program, it will recuperate 2% of potential staffing losses.
  - If all eligible Staff participate in the mentorship program, it will recuperate 3% of potential staffing losses.
  - If all eligible Senior Engineers participate in the mentorship program, it will recuperate 3% of potential staffing losses.
  - If all eligible Technique Leaders participate in the mentorship program, it will recuperate 2% of potential staffing losses.
  - If all eligible Assistant Engineers agree to participate in the mentorship program, it will recuperate 2% of potential staffing losses.
  - No Managers are currently eligible for the mentorship program.
- For full list of employees eligible for the mentorship program, see mentorship_eligibility.csv in https://github.com/mcarson16/Pewlett-Hackard-Analysis/blob/main/Data.zip

## Summary
- Hiring efforts will be most critical for the Engineer and Senior Staff titles.
- Of the 90,398 potential retirees, only about 1% would be eligible for the mentorship program. 
  - Eligible mentors could take on multiple mentees for a broader impact.
