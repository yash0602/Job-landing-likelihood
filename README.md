# Job-Landing-Likelihood 
It is hard for international students to land a job mainly due to 2 reasons - 1) High competition 2) Low job openings(Jon Density). This data analysis shows that there is a higher chance of landing a job in cities where graduation rate is low and demand of job is more. 


![](https://github.com/yash0602/Job-landing-likelihood/blob/master/g.png)

# Analysis 
 Major cities like New York, San Franciso, and Boston have higher graduation rate implying high competition. Since the Job Density is almost constatnt throught the cities, it gets harder for students to land a job in such high competetive pool. Small US cities like Austin, Dallas, and Tallahassee (with less schools) have low graduation rate but almost similar job density as other major cities suggesting that there is a higher chance for students to land a job beacuse of low competetion.     

# Note
For this analysis, I am not considering cross-state mobility as a factor. 

# Steps 
1. Retrieved data of univerisites/schools in all the US cities from opportunity atlas 
2. Retrieved data of Job density and Graduation rate from opportunity atlas
3. Used VLOOKUP function to extract all the data sets into a single Excel sheet 
4. Used COUNT.IF statement to get the total count of univerisites/school per city 
5. Used pivot table and pivot graph to analyze the data

# Source 

The data was retrieved on 8th February 2020 from https://www.opportunityatlas.org/
