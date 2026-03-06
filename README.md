# Pewlett-Hackard-Analysis
## Software
SQL, PostgreSQL, pgAdmin 4

## Overview of the Analysis
The purpose of this analysis is to determine two ways to deal with the rapid retirement of the baby boomers. The first way is to offer a retirement package to the people who are eligible to retire. The second way is to have the people who are thinking about retirement teach the new hires how to do the job. This way the company will not have thousands of job openings and the transition from retirement employees to new employees can be smooth.

## Results
- retirement_titles table had 133776 names. Quantity not directly representative of people retiring due to people changing positions in the company over the years. 

- unique_titles table reduced names to 72458 by having employees number show only once. This is the actual number of people retiring.

- retiring_titles table represents the number of people who are retiring in each position

- mentorship_eligibility table demonstrates the people who are nearing retirement and are able to teach the new employees their job.

![retirement_titles](https://user-images.githubusercontent.com/110945895/194912293-d514e8a8-1000-4a3c-9f12-06076462901f.png)

Figure 1. There are 133776 rows in the table. Within the first 10 rows, there are repeating names like Chirstian Koblick, Kyoichi Maliniak, and Sumant Peac with different titles. This shows these people moved positions while they are in the company.

![unique_titles](https://user-images.githubusercontent.com/110945895/194912344-972181f5-4066-4f4b-a9e3-d737b0afc41e.png)

Figure 2. There are 72458 rows with unique employees number showing that there no more repeating names. These are the people that are going to retire soon.

![retiring_titles](https://user-images.githubusercontent.com/110945895/194912378-d8d0d5f2-7fa6-4a77-a595-331225b4001d.png)

Figure 3. There are number of titles being counted with each title name. This shows the number of people that are going to retire in each department. 

![mentorship_eligibitility](https://user-images.githubusercontent.com/110945895/194912464-01558f5c-359e-4f57-8f13-e24403b6985e.png)

Figure 4. There are 1,549 people who are going to be getting ready to retire. These are the people who can mentor the incoming people. 

## Summary
There would need 72458 roles to be filled as the "silver tsunami" begins to make an impact. This can be seen in the unique titles table from the number of rows. There are not enough qualified retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees. There is only 1,549 retirement-ready employees. The number of retirement-ready employees is on mentorship_eligibility table. That means that there is a gap of 70909 employees that are ready to have the retirement package that won't be training the new employees.

