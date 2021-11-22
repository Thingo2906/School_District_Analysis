# School_District_Analysis

## Overview of the school district analysis:
- The school board has informed Maria and her supervisor that the students complete.csv file contains evidence of academic dishonesty, with reading and math grades for Thomas High School ninth graders seeming to have been tampered with. Despite the fact that the school board is unaware of the entire scope of the academic dishonesty, they are committed to upholding state testing standards and have sought Maria's assistance.
## Results: 
### How is the district summary affected?
- Average Math Scores: moved from 79 to 78.9 as a result of taking out Thomas High School Ninth Grade scores.
- Average Reading Scores did not change.
- Percent Passing Math moved from 75% to 74%.
- Percent Passing Reading moved from 86% to 85%.
- Percent Overall Passing moved from 65% to 64%.
<img width="1139" alt="333333" src="https://user-images.githubusercontent.com/93515126/142798311-db100507-028a-4a83-945b-6fb2d5a97508.png">
### How is the school summary affected?
- Average Math at Thomas decreased from 83.42 to 83.35.
- Average Reading at Thomas slightly increased from 83.84 to 83.89.
- Average Percent Passing Math at Thomas greatly decreased from 93.3% to 66.9%.
- Percent Passing Reading at Thomas decreases from 97.3% to 69.7%.
- Average Percent Overall passing both Math and Reading decreased from 90.9% to 65.1%.
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Thomas High School Scores
Nineth students at Thomas High School had their math and reading scores substituted with 'NaN' (Not a Number) so that their grades would not impact future computations. If all of the students' grades were substituted with a 'O,' this would have a detrimental influence on the school's and district's averages.
#### Thomas High School math scores:
Ninth grade math scores were replaced with NaN. Thomas High School 10th, 11th, and 12th grade math scores are as follows: 83.1, 83.5, and 83.5.
<img width="365" alt="WDWARFSE" src="https://user-images.githubusercontent.com/93515126/142800290-7e96ca03-772e-4c0b-936c-27fb3e71fd3e.png">
#### Thomas High School reading scores:
Ninth grade math scores were replaced with NaN. Thomas High School 10th, 11th, and 12th grade reading scores are as follows: 84.3, 83.6, and 83.8.
<img width="409" alt="DGFDFGHFHG" src="https://user-images.githubusercontent.com/93515126/142800454-62b32b76-a5da-44bf-9cd4-a32822448a1f.png">
#### Scores by School Spending
Schools that spent between $551-600 appear to have the best-performing students in math and reading:
<img width="659" alt="QASDSDFDG" src="https://user-images.githubusercontent.com/93515126/142801145-ebb357bf-9d89-4cff-aa24-409407add67f.png">
#### Scores by School Size
Scores by school size were calculated by determining size ranges for all 15 schools in the district: Small (<1000) Medium (1000-2000) Large (2000-5000)
<img width="850" alt="ASDaDSF" src="https://user-images.githubusercontent.com/93515126/142801297-b5435103-251f-4cc6-808a-8b6a698ca88a.png">
#### Scores by School Type
It was either a charter or a district school. Charter schools, unsurprisingly, outperformed district schools.
<img width="656" alt="GFXCXFGFGHGJ" src="https://user-images.githubusercontent.com/93515126/142801620-7d9a5a8d-a1f1-4093-a320-e674dc40b8da.png">
## Summary
### The removal of 9th grade student scores from Thomas High School has the following effects on the school district:
-Average math scores have decreased a smidgeon (1%).
-The average reading score was unaffected.
-The percentage of students who passed arithmetic has decreased somewhat (-1 percent )
-The percentage of students who passed reading has decreased somewhat (-1 percent )
-The overall pass rate has decreased (-1 percent )
### Only Thomas High School's grades were affected:
-The percentage of students passing math classes has decreased from 93.2 percent to 66.9%.
-The percentage of students who passed reading decreased from 97.3 percent to 69.7%.
-The overall pass rate dropped from 90.9 percent to 65.1 percent.)
### Other reports were impacted by the removal of 9th grade student scores from Thomas High School:
-For all other schools, math and reading results by grade stayed unchanged.
-Scores by school spending changed from $601-650:
  .The percentage of students passing math has decreased from 73 percent to 67 percent.
  .The percentage of those who passed their readings declined from 84 percent to 77 percent.
  .The overall passing rate fell from 63 percent to 56 percent.
-For medium-sized schools (1000-2000 students), the following scores have changed:
+The percentage of students passing math has decreased from 94 percent to 85 percent.
+The percentage of those who passed their readings declined from 97 percent to 91 percent.
+The overall passing rate fell from 91 percent to 85 percent.
-The following factors impacted the scores of different types of schools:
+The percentage of students passing math has declined from 94% to 90%.
+The percentage of those who passed their readings declined from 97 percent to 93 percent.
+The overall passing rate declined from 90% to 87 percent.
h

