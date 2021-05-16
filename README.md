# School District Analysis

## Overview

### Background and Deliverables
This analyst has been contacted by the representative of a local school district to review and analyze their data. During the initial meeting with the district representative the following list of deliverables were identified as requirements for the analysis: 

* A high-level snapshot of the district's key metrics, presented in a table format
* An overview of the key metrics for each school, presented in a table format
* Tables presenting each of the following metrics:
* Top 5 and bottom 5 performing schools, based on the overall passing rate
* The average math score received by students in each grade level at each school
* The average reading score received by students in each grade level at each school
* School performance based on the budget per student
* School performance based on the school size 
* School performance based on the type of school

During the course of the initial analysis, the school district identified evidence of "academic dishonesty" in the math and reading scores of 9th graders at Thomas High School. In response, the school district has requested the replacement of math and reading grades for 9th graders at Thomas High School with "NaN" values followed by a regeneration of the aforementioned deliverables to identify any impact on results at the district level.

### Methodology and Technologies

The school district provided the following comma separated values (CSV) files as source data for the analysis:
* schools_complete.csv
* students_complete.csv

The analysis was conducted using:
* Jupyter Notebook 6.1.4
* Python 7.19.0
* GitBash 2.31.1
* GitHub

Both CSV files were downloaded, inspected and imported into Jupyter Notebook using Python. Python coding was used to clean and process the data. Project files were stored in the GitHub respository for the purposes of warehousing, delivery and review.


## Results

### Math and Reading Scores By School and Grade

The comparative analysis of the data began by producing outputs for each school both before and after the removal of math and reading scores for 9th graders at Thomas High School. The following screenshots depict where data had been replaced with "NaN".

#### Math Scores by School and Grade (Before & After)

![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/ByGrade_Summary_Math_Before.PNG?raw=true)
![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/ByGrade_Summary_Math_After.PNG?raw=true)

#### Reading Scores by School and Grade (Before & After)

![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/ByGrade_Summary_Reading_Before.PNG?raw=true)
![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/ByGrade_Summary_Reading_After.PNG?raw=true)

### School Summaries
The impact of the removing math and reading scores for 9th graders at Thomas High School can be seen in the following tables. Note results are unchanged for all schools except for Thomas High School. A focused comparison of Thomas High School can be found below the school summaries.

#### School Summary Before

![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/School_Summary_Before.PNG?raw=true)

#### School Summary After

![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/School_Summary_After.PNG?raw=true)


#### Thomas High School Comparison (Before & After)

Note there are minor drops in average math and reading scores as well as a drop in the percent of students passing math, reading and overall.

![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/THS_Summary_Before.PNG?raw=true)
![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/THS_Summary_After.PNG?raw=true)

#### Top Performing Schools (Before & After)

As seen in the tables below, the impact of the removal of math and reading data for 9th graders at Thomas High School can be seen in the average scores and percentage of students passing. However, these changes were not significant enough to change Thomas High School's ranking as the #2 school in the district. See the top school rankings below.

![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/Top_Schools_Before.PNG?raw=true)
![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/Top_Schools_After.PNG?raw=true)

The removal of math and reading data for 9th graders at Thomas High School did impact percentages. However, due to rounding requirements of the analysis the impact of their removal were not seen in the district summary, scores by school type, scores by school size, or schools by school spending results.

#### District Summary (Before & After)

![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/District_Summary_Before.PNG?raw=true)
![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/District_Summary_After.PNG?raw=true)

#### Scores by School Type (Before & After)

![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/SchoolType_Before.PNG?raw=true)
![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/SchoolType_After.PNG?raw=true)

#### Scores by School Size (Before & After)

![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/Size_Before.PNG?raw=true)
![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/Size_After.PNG?raw=true)

#### Scores by School Spending (Before & After)

![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/Spending_Before.PNG?raw=true)
![alt text](https://github.com/geboweniii/School_District_Analysis/blob/main/Images/Spending_After.PNG?raw=true)
