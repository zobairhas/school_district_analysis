# School District Analysis

## Project Overview
The client has asked to analyze various school districts. The original request was to present which schools had the highest (and lowest) overall scores in math and reading. Then we compared those scores against the school's budget, size, and type. 
 
## School District Analysis Results
- How is the district summary affected?
  - Overall, the district summary wasn't impacted by much even by omitting the 9th grader scores from Thomas High School.
  - The most notcieable difference was in the reading passing rate where it dropped by 1.3%
```
Original PyCitySchools District Summary:
![Original_PyCitySchools_Summary](https://user-images.githubusercontent.com/44425379/150736760-0f15e234-5f1e-472c-9cba-977766e14f6b.png)
```

```
PyCitySchools District Summary without THS 9th Grader Math/Reading Scores:
![Updated_PyCitySchools_Summary](https://user-images.githubusercontent.com/44425379/150736804-5a115c80-8aa0-4b96-9587-ada9c70b1918.png)
```


- How is the school summary affected?
  - There was little impact on the school summary. All of the high schools except for Thomas High School still had about the same performance rates. 
- How does replacing the ninth-grader math and reading scores affect Thomas High School’s performance relative to the other schools?
  - It did not impact the performance relative to the other schools. Thomas High School still mainted the same position as the number two school even though all ninth-grader scores were removed. Thomas High School's math, reading, and overall performance rates were lower by a small margin.  
- How does replace the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - Thomas High School was impacted due to the ninth-grade scores being removed.  
  - Scores by school spending
    - Little to no change.
  - Scores by school size
    - Little to no change.
  - Scores by school type
    - Little to no change.
  
## School Districts Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
-  % Passing Math rates were slightly lower
-  % Passing Reading rates were slightly lower
-  % Overall Passing rates were slightly lower
-  Average Reading and Math scores were slightly lower
