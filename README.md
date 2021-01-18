# School District Analysis

## Overview of School District Analysis

### Purpose of Analysis
The schoolboard has discovered evidence of academic dishonesty in the students_complete.csv, specifically, regarding reading and math scores for ninth graders at Thomas High School. The reading and math scores for ninth graders at Thomas High School need to be changed to NaNs, while keeping the remaining data the same. The purpose of this analysis was to redo the original School District Analysis and see how removing the reading and math scores for the ninth graders at Thomas High School affected or altered the overall analysis.


### Results
- How is the district summary affected?
![district summary](https://user-images.githubusercontent.com/75760493/104870399-0bf5bb80-590e-11eb-8bfd-2ee5651a3573.PNG)
Based on the results that were gathered from the district summary above, it shows the disctirct summary is hardly affected by the removal of the ninth graders scores from Thomas High. Finding the new average scores and passing percentages among all the high schools in the district, the average math score dropped 0.1%, the average reading score stayed the same, the percentage passing math dropped 0.2%, the percentage passing reading dropped 1%, and the overall passing percent dropped roughly 1%. The difference in values ranged from 0-1%; it affected the data slightly, but not enough to cause a drastic change in results.

- How is the school summary affected?
![school summary](https://user-images.githubusercontent.com/75760493/104870514-54ad7480-590e-11eb-973f-e1bf30086a8c.PNG)
Out of the 1635 students from Thomas High, 461 of them were ninth graders, meaning the size of our sample for Thomas High drastically decreased. However, even though the size of our data decreased, this wouldn't have a drastic impact on the final results. From the school summary above, the overall percentage was calculated to be 90.63%, which is 0.31% less than the overall percentage that included the ninth graders scores. Since the only data that was altered was the scores from Thomas High, only the Thomas High averages and percentages will be affected, none of the averages or percentages of the other schools will change.

- How does replacing the ninth grader's reading and math scores affect Thomas' performance relative to other schools?
It won't have much of an affect on Thomas' performance because the performance is measured based on all the scores that are given. If we decided to remove a selection of scores, the overall performance would then be calculated using the remaining scores. 



- How does replacing ninth graders affect the following:
    
    - Math and reading scores by grade:
    
        Math score averages: 
        
        ![math score averages](https://user-images.githubusercontent.com/75760493/104870535-642cbd80-590e-11eb-9387-40cfba916e3c.PNG)
        
        Doesn't affect any of the math score averages for any class in any of the other schools. Only difference is Thomas High has NaN for the math score for 9th grade.
    
    
        Reading score averages:
        
        ![reading score averages](https://user-images.githubusercontent.com/75760493/104870566-7575ca00-590e-11eb-9ccd-168d04a5d427.PNG)
        
        Doesn't affect any of the reading score averages for any class in any of the other schools. Only difference is Thomas High has NaN for the reading score for 9th grade.
    
    - Scores by school spending:
    ![school spending](https://user-images.githubusercontent.com/75760493/104870614-91796b80-590e-11eb-8b76-bde885e60b5d.PNG)
    Scores based on school spending are not altered, since the only information that is being altered are grade values.
    
    - Scores by school size:
    ![school size](https://user-images.githubusercontent.com/75760493/104870653-a7872c00-590e-11eb-8359-c5352959d0ac.PNG)
    Scores based on school size are not altered, since the only information that is being altered are grade values.
    
    - Scores by school type:
    ![school type](https://user-images.githubusercontent.com/75760493/104870674-b372ee00-590e-11eb-9cdc-1a02041f573a.PNG)
    Scores based on school type are not altered, since the only information that is being altered are grade values.
    



### Summary
