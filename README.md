# Pewlett-Hackard-Analysis
## Analysis
  The project they are wanting us to do is to indentify the employees that would be eligible for a mentorship program. They want us to do this becuase of the number of employees that are about to retire. They do not want to be caught flat footed.
## Results
  - the amount retiring to their job title you will see that the Engineering department will be affected by it.
  - When looking at the total eligible mentors (1,940) it will barely cover the the gap of people that can retire.
## Summary
  In the end you will will have to find away to file approximatley 90,000 jobs because of the up and coming retirements. One one you can make it not so difficult is by seeing what areas that are needing the help the most by using :
Use Count() to sum the titles of retiring employees
-- and create retiring_titles table.
SELECT count(title), title
into retiring_titles
from unique_titles
Group By title
order by count desc;
This way you know what departments will neet it the most and where to focus the the mentorship towards, At the same time trying to hire new people to fill in for the peoplt that are in the mentor program. This will be a difficult time for Pewlett Harckard but with the focus in the right areas that effect the company the most it will help make the transtion easier.
 
