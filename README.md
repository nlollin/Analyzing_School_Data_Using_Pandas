# pandas-challenge
This repository contains code and a written data analysis.

# Code
After reading two separate csv files containing data on schools and students in a district, the two files were merged into one DataFrame so that a deeper analysis could be performed.  This analysis was broken into sections that created dataframes for each of the descriptions provided.

## District Summary

This section calculates the total number of schools, students, and budget for the entire district.  It also finds the average math and reading scores, as well as the overall passing rate (along with the passing rates of the two subjects separately).

## School Summary

This section calculates the same metrics that were found in the district summary, but separates the information by school rather than providing it for the district as a whole.

## Highest-Performing Schools

This section identifies the 5 schools with the highest overall passing rate.

## Bottom Performing Schools

This section identifies the 5 schools with the lowest overall passing rate.

## Math Scores by Grade

This section calculates the average math scores for each grade and separates the information by school.

## Reading Score by Grade

This section calculates the average reading scores for each grade and separates the information by school.

## Scores by School Spending

This section places each school into a category based on its "per student budget".  
The four categories are: "< $585", "$585 - $630", "$630 - $645", and "$645 - $680"  (per student)
The average scores and passing rates for each subject, along with the overall passing rate, for those categories are calculated.

## Scores by School Size

This section places each school into a category based on its size.  
The three categories are: "Small (<1000)", "Medium (1000-2000)", and "Large (2000-5000)"
The average scores and passing rates for each subject, along with the overall passing rate, for those categories are calculated.

## Scores by School Type

This section places each school into a category based on the type of school.  
The two categories are: "District" and "Charter"
The average scores and passing rates for each subject, along with the overall passing rate, for those categories are calculated.

# Analysis

The Word document in this repository contains a written analysis discussing the average scores and passing rates within the district.  The association between these scores/passing rates and the school budget, school size, and school type are analyzed.
