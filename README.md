# School_District_Analysis
The school board had reason to suspect that there may be academic dishonesty taking place in the 9th grade class of Thomas High School. Specifically in the areas of reading and math. Due to these concerns the unit was tasked with providing an comparative anaysis between the scores with and without the Thomas High School 9th graders. After the analysis, a written report is to be provded to demonstrate how these changes affect the overall analysis.  
### The following key metrics were analyzed:
- Number of students
- Number of schools
- Total budgets
- Average math and reading scores
- Percentage of students who passed math and reading
- Overall passing percentage combining math and reading


# Results of Analysis
## District Summary Analysis
After analysing the District summaries with and without the Thomas High Schools 9th grade scores, the differences are less then half a percent in all categories. Removing the scores did not reveal any significant change to indicate dishonesty. However, when reviewing Thomas High scores without the 9th graders the school still performs above the average for all schools. 

All Scores

![DistictSummaryALL](https://user-images.githubusercontent.com/88912539/134841166-ce7fb6ef-0d35-46b3-a910-33730e903c23.png)

Scores with Thomas High School 9th graders removed

![DistrictSummaryNO_THS](https://user-images.githubusercontent.com/88912539/134841210-93715c19-6c92-41f0-8239-b95eb0ff6594.png)

Thomas High Schol 9th graders removed

![DistrictSummaryTHSOnly](https://user-images.githubusercontent.com/88912539/134841756-0141bb30-9690-4544-b3b7-5b69b9d8ea21.png)


## School Summary Analysis 
Evaluating the ranking of the top five schools in the district, Thomas High School remained in second place with and without the 9th grade scores. It is noteworthy that when comparing the metrics, the precision had to be expanded to display tenths to make any change visible. Based on whole numbers there was no change at all.  


Top 5 All Scores

![SchoolSummaryAll](https://user-images.githubusercontent.com/88912539/134842147-149347f3-3c78-40b1-980f-0f749b710eb4.png)


Top 5 without Thomas High School 9th Graders 

![SchoolSummaryNoTHS](https://user-images.githubusercontent.com/88912539/134842160-e3145ac6-9ff5-43b2-a3d0-6d03d8260ada.png)

## Relative Math and Reading Analysis
Additional analysis was conducted to compare all 9th grade scores for the district with and without Thomas High School. The results indicated that with all 9th graders in the district the average math score was 78.93%. Removing the Thomas High School 9th grader return a result of 78.73% resulting in a .2% change. Conducting the same analysis on Reading score revealed all score resulted in 81.91% and after removing Thomas High School the score was 81.83%

All 9th grade average Math
```
all_ninth_grade_wTHS = ninth_graders.mean()["math_score"]
print(all_ninth_grade_wTHS)
```
78.93565918653576

9th grade average Math without Thomas High School
```
all_ninth_grade_woTHS_math = ninth_graders.mean()["math_score"]
print(all_ninth_grade_woTHS_math)
```
78.73965469991778

All 9th grade average Reading
```
all_ninth_grade_wTHS_reading = ninth_graders.mean()["reading_score"]
print(all_ninth_grade_wTHS_reading)
```
81.91435834502104

9th grade average Reading without Thomas High School
```
all_ninth_grade_woTHS_reading = ninth_graders.mean()["reading_score"]
print(all_ninth_grade_woTHS_reading)
```
81.83794646935233

## School Spending Analysis 
School spending all scores
![SpendingAll](https://user-images.githubusercontent.com/88912539/134843937-79e0982d-dcf0-4d41-83f6-63a742f3a8a9.png)

School spending without Thomas High School 9th Graders 
![SpendingNO_THS](https://user-images.githubusercontent.com/88912539/134843956-d4649d07-412b-4d01-badc-665b7c1c805d.png)

## School Size Analysis 
School size all scores
![SpendingAll](https://user-images.githubusercontent.com/88912539/134844069-5fe7a5a5-cdd3-40f4-a5ac-9bf94e54cc14.png)

School size without Thomas High School 9th Graders 
![SizeNO_THS](https://user-images.githubusercontent.com/88912539/134844103-93441ad3-a982-4ebb-9cbb-13ec36a775b3.png)

## School Type Analysis 

School Type all scores
![TypeALL](https://user-images.githubusercontent.com/88912539/134844228-2f20bba3-244a-4c05-9259-10ad5d29b11b.png)

School Type without Thomas High School 9th Graders 
![TypeNO_THS](https://user-images.githubusercontent.com/88912539/134844244-37ef9d5d-3828-4e78-8d82-8b60401fb935.png)

#Summary 
In summary there were no significant differences in the number of students passing and the average scores for reading and math based on the 9th grade class at Thomas High School. Although the school board had reason to believe there was academic dishonesty, a through evaluation of the requested metrics did not support a conclusion of academic dishonesty. 
