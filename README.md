# School_District_Analysis
Using Jupyter Notebook &amp; Pandas
## Overview of the school district analysis

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help.


### Purpose
To investigate and analysis the school district analysis that has replaced the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and how these changes affected the overall analysis.


## Results

The District summary slightly changed 0.1 on the average math score  and the rest stayed the same value.

### The District summary
![District_Summary_df](https://github.com/Poonsri14/School_District_Analysis/blob/main/Resources/District_Summary_df.png)


The school summary per each school compared with original analysis has statyed the same, excecpt for Thomas High School that is slight increased 0.0674 on Average Math Score, 0.086 % on Percentage Passing Math, 0.290% on Percentage Passing Reading and 0.318 on Overall Passing. However, there is decreaing (-0.0468) on Averge Reading Score.

### The School Summary
![Per_school_summary_df](https://github.com/Poonsri14/School_District_Analysis/blob/main/Resources/Per_school_summary_df.png)

After replacing the ninth graders’ math and reading scores Thomas High School’s performance doens't relative to the other schools, but really affect their school perfermances. Thomas High School has a lot better performances on Percentage Passing Math from 66.911% to 93.186%, Percentage Passing Reading from 69.663% to 97.019%, and Percentage Overall Passing from 65.076% to 90.63%

### Thomas School Summary
![THS_school](https://github.com/Poonsri14/School_District_Analysis/blob/main/Resources/THS_school_replacingNaN.png)

Replacing the ninth-grade scores doesn't affect the following:

### Math Score by grade
![Math Score by grade](https://github.com/Poonsri14/School_District_Analysis/blob/main/Resources/Math_scores_by_grade.png)
    
### Reading Score by grade

![Reading Score by grade](https://github.com/Poonsri14/School_District_Analysis/blob/main/Resources/Reading_scores_by_grade.png)
 
### Scores by school spending
![scores by school spendind](https://github.com/Poonsri14/School_District_Analysis/blob/main/Resources/score_by_school_spending.png)  
    
### Scores by school size
![scores by school size](https://github.com/Poonsri14/School_District_Analysis/blob/main/Resources/score_by_school_size.png)

### Scores by school type
![scores by school type](https://github.com/Poonsri14/School_District_Analysis/blob/main/Resources/score_by_school_type.png)

## Summary: 

According to the figures above, ther are couples changed in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs: The average math score on the District summary, the school Summary, and Thomas High School performances. 
However, Math and reading scores by grade, Scores by school spending, Scores by school size, and Scores by school type are stayed the same.
