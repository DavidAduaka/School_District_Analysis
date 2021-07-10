# School_District_Analysis

## Project Overview
Maria is the chief data scientist for a city school district and is responsible for analyzing information from a variey of sources in a variety of formats. In this role she is tasked with preparing all standardized test data for analysis, reporting, and pesentation to provide insights about performance trends and patterns. To assist her with her analysis she needs:  

- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting each of the following metrics:
    - Top 5 and bottom 5 performing schools, based on the overall passing rate
    - The average math score received by students in each grade level at each school
    - The average reading score received by students in each grade level at each school
    - School performance based on the budget per student
    - School performance based on the school size 
    - School performance based on the type of school

## Resources 
- Data Source: schools_complete.csv, students_complete.csv
- Software: Anaconda 4.10.1, Jupyter Notebook 6.4.0

## Challenge Overview 
The school board notified Maria that the students_complete.csv file shows evidence of academic dishonesty specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. To up-hold the state-testing standards Maria wants the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.

## Challenge Summary
After completing the analysis with the updated data set only a few of the key metrics changed. Thomas High school's performance relative to the other schools, scores by school spending, scores by school size, and scores by school type all did not change. The reason for this is because the data that was ommitted due to academic dishonesty was just for one grade. Relative to the overall dataset this does not show up much in these metrics because they are for each school and for all grades. The metrics that changed were the distrcit summary (passing math %, passing reading %, and overall passing %) and the school summary (Math and Reading scores by grade) because Thomas High School had no data for 9th grade. 
