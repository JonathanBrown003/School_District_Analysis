# School District Analysis
Pandas to analyze school district data:

![Challenge Code Here](https://github.com/JonathanBrown003/School_District_Analysis/blob/8d011869d4759d1e3d0747eebfc413e483313976/PyCitySchools_Challenge.ipynb)

## Overview of the School District Analysis
We set out to replace inaccurate data for 9th graders at Thomas High School while also performing the same analysis we did during the module in looking at testing and grade data at various schools using Pandas. Factors that were taken into consideration while looking at the data include average math and reading scores, school budget, per capita spending per school, etc. We also looked at the total passing percentage of students along with their aggregate math and reading scores by school. 

## Results
Many of the metrics remained the same due to removing a portion of data for 9th graders at Thomas High School. Removing this data did not drastically skew the district data in the aggregate but it did very slightly affect the aggregate scores for students at Thomas High School. The math and reading scores still averaged approximately 83% before and after scrubbing the data. 

A surprising finding with spending per capita found that the highest average student scores were attained by those schools in the lowest per capita spending schools (<$584 per student). Please see below:

![](https://github.com/JonathanBrown003/School_District_Analysis/blob/aae9c42cd83848726c6a54154b36558cf291fbff/Resources/Spending_BySchool.PNG)

We also found that charter schools had considerably better student scores across the board in every category measured:

![](https://github.com/JonathanBrown003/School_District_Analysis/blob/803ea7ebaccfeeb229bec6d3ee73f2f49af23b5a/Resources/Charter_Schools.PNG)

## Summary
Changes that occurred as a result of 9th grade student scores at Thomas High School having their scores replaced with NaN include an entire grade of students not counted. This didn't affect the data much however as the average scores were still around 83% according to our analysis. The overall percentages for math and reading scores were marginally affected at Thomas High School. 
