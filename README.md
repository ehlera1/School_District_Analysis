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

![1_Overall_District_Before](https://user-images.githubusercontent.com/90698381/137794192-e90f31f0-d1ec-4be5-9131-75fde24857b9.png)

District summary after removal of Thomas High School ninth graders.

![1_Overall_District_After](https://user-images.githubusercontent.com/90698381/137794211-0655c955-c38f-41aa-b9b9-093a6fca1c7f.png)

When looking at these images you can see the following:  
-	The average math score was slightly reduced.
-	The average reading score was unchanged.
-	The percentage of students passing math and reading dropped slightly. 


### How the school summary was affected.
The overall school summary with exception to the metrics for Thomas High School remained constant. T  
-	The images below show metrics for all the schools both before and after the adjustment for Thomas High Schools’ ninth graders. Thomas Highs School had a their average math score decrease, average reading score increase, and all their passing percentages decrease. 

School summary before adjustment:

![2_School_Before_Adjustment](https://user-images.githubusercontent.com/90698381/137794339-79ccaa72-f40b-4f16-9fa5-1b12161457fc.png)

School summary after adjustment:

![2_School_After_Adjustment](https://user-images.githubusercontent.com/90698381/137794364-c591e8b1-dc6e-4325-ae07-109a70a6e03e.png)

### How replacing the ninth graders’ math and reading scores affected Thomas High School’s performance relative to the other schools in the district.
- When we initially compared the top and bottom performing schools in the district, Thomas High School was the second highest school in ranking in terms of the overall passing percentage of students. When comparing the results after the 9th grade students from Thomas High School were removed the overall passing percentage decreased yet they were still the second highest in terms of overall passing percentage. Please see the results below of top performing schools before and after adjustment. 

Top performing schools before adjustment:

![3_Top_Schools_Before](https://user-images.githubusercontent.com/90698381/137794552-7a186509-3462-4959-8de1-c98de8e0bf81.png)

Top performing schools after adjustment:

![3_Top_Schools_After](https://user-images.githubusercontent.com/90698381/137794521-3f0a4c61-793f-42ae-8b65-74f70effa5b8.png)

### How replacing the ninth-grade scores affected the following.
-	In the secondary analysis of this district, when we replaced the ninth grade scores for Thomas High School we simply chose to omit any data for their reading and math scores. When reviewing the overall scores before and after you can clearly see that there is not a numeric value in the averages shown by school/grade in the after image. While omitting the data does reduce the data sample size for the 9th grade there should be no impact to the individual schools average scores by grade while it may slightly change the overall ninth grade average for the district. Please see the tables below showing the averages for math and reading scores: 
Average math scores by grade before adjustment:

![4_Math_Scores_Before](https://user-images.githubusercontent.com/90698381/137794630-57ccb7b5-3ed7-44c2-acfc-76e791107e97.png)

Average math scores by grade after adjustment:

![4_Math_Scores_After](https://user-images.githubusercontent.com/90698381/137794647-bd0d9d23-3c8c-470c-a6b6-36fe8bba386f.png)

Average reading scores by grade before adjustment:

![4_Reading_Scores_Before](https://user-images.githubusercontent.com/90698381/137794697-c0d5b28d-1b8c-406d-86e6-4ef838175d59.png)

Average reading scores by grade after adjustment:

![4_Reading_Scores_After](https://user-images.githubusercontent.com/90698381/137794686-0fab3696-e43b-4adf-bb9b-5da3b60dcf23.png)

-	After adjustment of the Thomas High School 9th grade scores there appears to be no significant change in the average math or reading scores, average math or reading percentages, or average overall passing percentages based on the spending range per student. The below images are of before and after adjustment and are identical. 

Per student spending summary before adjustment: 

![5_Spend_Summary_Before](https://user-images.githubusercontent.com/90698381/137794756-67da697c-72e6-4268-af31-e4b57439cbea.png)

Per student spending summary after adjustment: 

![5_Spend_Summary_Final](https://user-images.githubusercontent.com/90698381/137794747-e592fec5-689c-435b-adc7-debe64d1bc41.png)

-	Similar to the results of the per student spending summary, after adjustment of the Thomas High School 9th grade scores there appears to be no significant change in results to the average scores or percentage based on school size. The below images are of before and after adjustment and are identical. 

School size summary before adjustment:

![6_Size_Summary_Before](https://user-images.githubusercontent.com/90698381/137794796-1797cb0e-ac99-4870-aa33-a10c85693e5a.png)

School size summary after adjustment:

![6_Size_Summary_Final](https://user-images.githubusercontent.com/90698381/137794816-5f7c806a-06b5-47ee-bb71-c33f4dae515e.png)

-	The finial metric in our analysis was the scores based on school type. This metric did not see any significant changes and the two results shown below are identical.

School type summary before adjustment:
 
![7_Type_Summary_Before](https://user-images.githubusercontent.com/90698381/137794834-0e57c044-d7ae-4b2f-a560-a4b320a071d0.png)

School type summary after adjustment: 

![7_Type_Summary_Final](https://user-images.githubusercontent.com/90698381/137794857-3bd163b4-21f3-4b0d-b52d-185f8deabad0.png)

## Summary: 

To summarize our analysis after replacing the 9th grade scores for Thomas Highschool.  It was clear to see that there were changes in the overall results. The district’s average math score dropped by 0.1%, the passing math percentage dropped by 0.2% and the overall passing percentage dropped 0.1%. The most noticeable changes were specifically related to Thomas High School. Thomas High School had reductions in their average math score, passing math percentage, passing reading percentage, and overall passing percentage. When averaging the scores and percentages it appeared that there were no significant changes to report on. We are glad to have completed this secondary analysis for Maria and hope she continues to engage us for further analysis. 

