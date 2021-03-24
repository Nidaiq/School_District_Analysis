# School_District_Analysis

# Background

Maria is a chief data scientist for a school district.  She is responsible for analyzing the standardized test data for performance analysis, reporting and presentations about insights about performance trends and patterns.  Her analysis helps the School Board and the School Superintendents in making decisions regarding school budgets and priorities.  The family Educational Rights and Privacy Act (FERPA) is important to protect the student's identity.  After completing the initial analysis, Maria was notified of academic dishonesty for Thomas High School ninth grader's data where the math and reading scores had been altered. 

## Purpose

The purpose of this analysis was to replace the math and reading scores for Thomas High School while keeping the rest of the data intact and also to repeat the school district analysis with the changes.

# Analysis

The analysis revealed the following:

1) Observation of Image 1_Original_Data_Set and Image 2_New_Data_Set  and in the resources, folder reveals that overall the changes in the district summary were very minor.  

2) Looking at Image 3 _Change_in_School_Ranking in the resources folder it can be observed that the biggest change found in the school analysis was that after deleting the results for Thomas High School, the ranking of the school changed, and it became one of the top 5 schools when sorted by the of over-all rating.

3) The reading score and the math scores for Thomas High School were drastically changed due to deletion of the grade 9 data.  From Image 3 the new data shows the average reading score and average math score as 83.9 and 83.4 respectively. 

4) The greatest change was observed within the data for the high school % Passing Reading, % Passing Math and % Overall Passing were all over 90% after deleting the data for the grade 9:

- The % Passing Math score went from 67% to 93%.  
- The % Passing Reading score changed from 70% to 97%.  
- The % Passing Overall changed from 65% to 91%.  

5) The grade 9th data for Thomas High School was replaced with NaN and that showed up in the Data Frame.  That is a change from what was original.

6) In the spending range of $630-644 went up in the scores for reading and math which was then reflected in the percentage too. 

# Summary of results:

The change in reading and math score that was also reflected in the % Passing Math, % Passing Reading and % Passing Overall specially for Thomas High School as the grade 9 data for the school was deleted.  This was also reflected in the spending range Data Frame.  Deleting the data set for grand 9th in Thomas High School changed the overall rating of the school and bumped it up to # 2 on the list of the schools with highest % overall passing.  This manipulation of data shows how important it is to evaluate if a data set should be deleted or not.  A change like such can have a minor impact on the overall data as the number of students in Thomas High School in grade 9th were only 461 out of 39170 in the school district (which represents only 1.2% of the population).  Deleting the dataset for Grade 9th had a larger impact on the overall rating and scores of Thomas High School but had a negligible impact on the overall school district analysis.  
