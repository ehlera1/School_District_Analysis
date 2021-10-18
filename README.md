# School District Analysis – Adjusted for Academic Dishonesty
## Project Overview
We have been working with Maria the Chief Data Scientist for a city school district on analyzing key metrics for the district that the school board can use to have informed discussions and make strategic decisions. After completing an initial analysis for Maria, she was notified by her supervisor that one of the files she provided to us titled “students_complete.csv” shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders. Unfortunately, the extent of the dishonesty in is not know by student for Thomas High School ninth graders and the school board would still like to uphold state-testing standards. Maria has asked that we duplicate our initial analysis without the scores for Thomas High School ninth graders. The analysis that follows will include all the metrics as outlined in Maria’s original request without the test scores for Thomas High School ninth graders. 

PLEASE NOTE: Due to the Family Education Rights and Privacy Act (FERPA) the data shown in the following analysis is confidential and should not be shared under any circumstance. 
## Resources
-	Data Sources: schools_complete.csv, students_complete.csv
-	Software: Python 3.7.6, Anaconda Version 4.10.3, Jupyter Notebook

## Results

### How the district summary was affected
When we look at the overall district performance the metrics are slightly different with the Thomas High School ninth grade scores removed. Please see the images below for reference: 

District summary before removal of Thomas High School ninth graders.

1 INSERT IMAGE 

District summary after removal of Thomas High School ninth graders.

1 INSERT IMAGE 

When looking at these images you can see the following:  
-	The average math score was slightly reduced.
-	The average reading score was unchanged.
-	The percentage of students passing math and reading dropped slightly. 


### How the school summary was affected.
The overall school summary with exception to the metrics for Thomas High School remained constant. T  
-	The images below show metrics for all the schools both before and after the adjustment for Thomas High Schools’ ninth graders. Thomas Highs School had a their average math score decrease, average reading score increase, and all their passing percentages decrease. 

School summary before adjustment:

2 INSERT IMAGE

School summary after adjustment:

2 INSERT IMAGE

### How replacing the ninth graders’ math and reading scores affected Thomas High School’s performance relative to the other schools in the district.
- When we initially compared the top and bottom performing schools in the district, Thomas High School was the second highest school in ranking in terms of the overall passing percentage of students. When comparing the results after the 9th grade students from Thomas High School were removed the overall passing percentage decreased yet they were still the second highest in terms of overall passing percentage. Please see the results below of top performing schools before and after adjustment. 

Top performing schools before adjustment:

3 IMAGE
Top performing schools after adjustment:

3 IMAGE

### How replacing the ninth-grade scores affected the following.
-	In the secondary analysis of this district, when we replaced the ninth grade scores for Thomas High School we simply chose to omit any data for their reading and math scores. When reviewing the overall scores before and after you can clearly see that there is not a numeric value in the averages shown by school/grade. While omitting the data does reduce the data sample size for the 9th grade there should be no impact to the individual schools average scores by grade while it may slightly change the overall ninth grade average for the district. Please see the tables below showing the averages for math and reading scores: 
Average math scores by grade before adjustment:

4 MATH AND READING SCORES IMAGES

Average math scores by grade after adjustment:

4 MATH AND READING SCORES IMAGES

Average reading scores by grade before adjustment:

4 MATH AND READING SCORES IMAGES

Average reading scores by grade after adjustment:

4 MATH AND READING SCORES IMAGES

-	After adjustment of the Thomas High School 9th grade scores there appears to be no significant change in the average math or reading scores, average math or reading percentages, or average overall passing percentages based on the spending range per student. The below images are of before and after adjustment and are identical. 

Per student spending summary before adjustment: 

5 SPENDING IMAGES 

Per student spending summary after adjustment: 

5 SPENDING IMAGES 

-	Similar to the results of the per student spending summary, after adjustment of the Thomas High School 9th grade scores there appears to be no significant change in results to the average scores or percentage based on school size. The below images are of before and after adjustment and are identical. 

School size summary before adjustment:

6 SIZE IMAGES

School size summary after adjustment:

6 SIZE IMAGES

-	The finial metric in our analysis was the scores based on school type. This metric did not see any significant changes and the two results shown below are identical.

School type summary before adjustment:
 
7 TYPE IMAGES

School type summary after adjustment: 

7 TYPE IMAGES

## Summary: 


