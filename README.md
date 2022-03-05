# School District Analysis Challenge

## Overview of the School District Analysis:
The purpose of this analysis is to analyze the student testing data for ninth grade students at Thomas High School. The reason for a segmented analysis on Thomas High School's ninth grade student's grade data is that the students_complete.csv file that was supplied by the school board for previous analysis has been marked as suspect of academic dishonesty in regards to the ninth grade reading and math grades for Thomas High School. Therefore, to uphold state-testing standards this analysis will replace Thomas High School's math and reading scores with NaN values while keeping the rest of the data intact. After replacing Thomas High School's math and reading scores with NaN values the initial analysis on was repeated to obtain a district summary that shows math and reading scores, passing averages and passing percentages for charter and district high schools in the school board's district. 

## Results 
* How the District Summary is affected
In this revised analysis, the loc method, logical, and comparison operators were used to replace the ninth grade math and reading scores for Thomas High School to NaN values:

![Ninth_Grade_RM_NaN](https://github.com/adecoste2/School_District_Analysis/blob/main/Challenge%20Images/Challenge%20Images/Ninth_Grade_RM_NaN.png?raw=true)


District Summary Initial Analysis
![District_Summary_Before](https://github.com/adecoste2/School_District_Analysis/blob/main/Challenge%20Images/Challenge%20Images/District_Summary_Before.png?raw=true)

District Summary Subsequent Analysis
![District_Summary_After](https://github.com/adecoste2/School_District_Analysis/blob/main/Challenge%20Images/Challenge%20Images/District_Summary_After.png?raw=true)


* How the School Summary is affected
The School Summary was unaffected in regards to all school's *School Type*, *Total Students*, *Total School Budget* and *Per Student Budget* values however, the *Average Math Score*, *Average Reading Score*, *% Passing Math*, *% Passing Reading* and *% Overall Passing* values decreased for Thomas High School because the data for nineth grade math and reading scores were changed to NaN values.

School Summary Initial Analysis
![School_Summary_Before](https://github.com/adecoste2/School_District_Analysis/blob/main/Challenge%20Images/Challenge%20Images/School_Summary_Before.png?raw=true)

School Summary Subsequent Analysis
![School_Summary_After](https://github.com/adecoste2/School_District_Analysis/blob/main/Challenge%20Images/Challenge%20Images/School_Summary_After.png?raw=true)

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the ninth grader's math and reading scores does not affect Thomas High School's performance relative to other schools. As you can see from the images below, there is a minute dip in the *Average Math Score*, *Average Reading Score*, *% Passing Math*, *% Passing Reading* and *% Overall Passing* values but not enough to shift ranking or funding.

School Performance Initial Analysis
![School_Performance_Before](https://github.com/adecoste2/School_District_Analysis/blob/main/Challenge%20Images/Challenge%20Images/School_Performance_Before.png?raw=true)

School Performance Subsequent Analysis
![School_Performance_After](https://github.com/adecoste2/School_District_Analysis/blob/main/Challenge%20Images/Challenge%20Images/School_Performance_After.png?raw=true)

* How does replacing the ninth-grade scores affect the following:

  * Math and reading scores by grade
  
    Math Scores by Grade Initial Analysis
    ![]()
  * Scores by school spending
  * Scores by school size
  * Scores by school type


## Summary
