# Pewlett-Hackard-Analysis

#Overview
The purpose of this analysis is to import and analyze data on Pewlett Hackard's employees to anticipate and prepare for retiring managers. In this challenge postgresql was used to conduct the analysis. 

#Results
In deliverable 1, queries are designed to return employees of the retirement age and to count the number of upcoming retirees. From ther unique_titles.csv file, we can see all of the individuals who are coming uop on the retirement age. The image below shows the number of retirees for each title. This shows that Senior Engineer and Senior Staff are the two positions with the most future retirees. It could be dificult to backfill all of these positions becasue over 50,000 Senior Engineers and Senior Staff will be retiring combined. 

![Screen Shot 2022-02-09 at 11 19 59 PM](https://user-images.githubusercontent.com/95301484/153342588-ef9307d3-ea34-49b4-9546-4eb6bfc0d610.png)

In deliverable 2, a query was designed to find all of the employees that could replace the future retirees. The list was printed in the mentorship_eligibility.csv file. If the same count in run on the mentorship eligibility list, we can see that we do not have enough employees to replace the large number of retiring employees. This is shown in the table below. 

![Screen Shot 2022-02-09 at 11 31 42 PM](https://user-images.githubusercontent.com/95301484/153343802-cf9946ae-060a-454b-8168-6b95c90863fa.png)

#Summary
Based on the data presented above, it is clear that there are not enough employees to replace the large wave of retiring employees. The company must look to hire from outside the company, or reach down into a younger demographic at the company. With over 70,000 employees coming up on retirement and only roughly 1,500 employees in the proper age range to replace these employees, the company will need to ramp up hiring.


