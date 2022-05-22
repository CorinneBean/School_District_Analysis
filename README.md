# PyCitySchools_Challenge

## Overview of PyCitySchools_Challenge
The initial school district analysis was performed to evaluate the standardized testing scores of the PyCity school district. After the initial analysis the school board found evidence of academic dishonesty in the reading and math grades for 9th grade students at Thomas High School. To uphold state-testing standards, I have been tasked with removing the testing scores for the 9th grade students at Thomas High School while keeping the remainder of the data intact. 

## Results
### 1. How is the district summary affected?

The district summary was affected because the 9th grade students at Thomas High School reading and math scores turned to null. This would affect the overall average scores for the district since these scores are now no longer included. The student count was not affected since that number is found by counting each unique Student ID.

**Original Analysis**
![Original Analysis](https://github.com/CorinneBean/School_District_Analysis/blob/3a1cc2617144300b1d0e0265433be7f5d7afd0e7/Resources/Original%20District%20Summary.png)

**Adjusted Analysis**
![Adjusted Analysis](https://github.com/CorinneBean/School_District_Analysis/blob/3a1cc2617144300b1d0e0265433be7f5d7afd0e7/Resources/Adjusted%20District%20Summary.png)

When the two charts are compared, you can see that removing the scores of the 9th graders at Thomas High School had a minimal effect on the district summary data set. The change appears to be less than 1%.

### 2. How is the school summary affected?
In the original analysis, Thomas High School had a 91% passing rate. After removing these scores, the testing data was adjusted accordingly. 

**Original Analysis**
![Original Analysis]( https://github.com/CorinneBean/School_District_Analysis/blob/589a8eb3f4c9d9b3bb1fcac8789caf16513ecdc7/Resources/Original%20Per%20School%20Summary.png)

**Adjusted Analysis**
![Adjusted Analysis]( https://github.com/CorinneBean/School_District_Analysis/blob/589a8eb3f4c9d9b3bb1fcac8789caf16513ecdc7/Resources/Adjusted%20Per%20School%20Summary.png)

Before removing the grades for 9th grade students at Thomas High School, the school appeared to be doing tremendously well on state-standardized testing. However, once the scores were removed because of academic dishonesty the score for Thomas High School dropped to 65% from the original 91% passing rate.

### 3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
When reviewing how the schools within the district compare initially Thomas High School was in 2nd place within the PyCity district. Their overall passing percentage scored at 90.948012. Once the 9th grade scores were removed from the percentage their overall passing percentage dropped to 90.630324. The change did not affect their status as a whole and still appear to be the 2nd top school within the PyCity district.
**Original Analysis**
![Original Analysis]( https://github.com/CorinneBean/School_District_Analysis/blob/08c964f9e7e53c377f29cbecd696603c2f1525e3/Resources/original_top_school.png)

**Adjusted Analysis**
![Adjusted Analysis]( https://github.com/CorinneBean/School_District_Analysis/blob/08c964f9e7e53c377f29cbecd696603c2f1525e3/Resources/adjusted_top_school.png)
### 4. How does replacing the ninth-grade scores affect the following:
Prior to the adjustment, Thomas High School had an average math score of 83.6 and an average reading score of 83.7 for 9th grade students. Since the discovery of academic dishonesty these scores have been removed to preserve the accuracy of the other school’s data. Since these grades are no longer counted for the school their performance to other schools can no longer be evaluated for the 9th grade class.

**Original Analysis**
>Original Math 

![Original Math]( https://github.com/CorinneBean/School_District_Analysis/blob/93b0ae021b3c3d0050cb5552d080613af8c2aa35/Resources/original_math_by_school.png)

>Original Reading

![Original Reading]( https://github.com/CorinneBean/School_District_Analysis/blob/93b0ae021b3c3d0050cb5552d080613af8c2aa35/Resources/original_reading_by_school.png)

**Adjusted Analysis**
>Adjusted Math

![Adjusted Math]( https://github.com/CorinneBean/School_District_Analysis/blob/93b0ae021b3c3d0050cb5552d080613af8c2aa35/Resources/adjusted_math_by_school.png)

>Adjusted Reading

![Adjusted Reading]( https://github.com/CorinneBean/School_District_Analysis/blob/93b0ae021b3c3d0050cb5552d080613af8c2aa35/Resources/adjusted_reading_by_school.png)

Thomas High School falls within the spending range (per student) of $630-644. When we evaluate how the academic dishonesty affected the school based on their spending, we find that the incident had minimal impact on the overall scores for the school.
**Original Analysis**
![Original Analysis]( https://github.com/CorinneBean/School_District_Analysis/blob/03bcdcaf308c837aaeccd6afadb0b148c6570a17/Resources/original_scores_by_spending.png)

**Adjusted Analysis**
![Adjusted Analysis]( https://github.com/CorinneBean/School_District_Analysis/blob/03bcdcaf308c837aaeccd6afadb0b148c6570a17/Resources/adjustedl_scores_by_spending.png)

Thomas High School falls within the school size of Medium (1000-1999). When we evaluate how the academic dishonesty affected the school based on their size, we find that the incident had minimal impact on the overall scores for the school.

**Original Analysis**
![Original Analysis]( https://github.com/CorinneBean/School_District_Analysis/blob/f223123881050e4b491f2200769b131bf3b7c161/Resources/original_score_by_size.png)

**Adjusted Analysis**
![Adjusted Analysis]( https://github.com/CorinneBean/School_District_Analysis/blob/f223123881050e4b491f2200769b131bf3b7c161/Resources/adjusted_score_by_size.png)

Thomas High School is a charter school. When we evaluate how the academic dishonesty affected the school based on type, we find that the incident had minimal impact on the overall scores for the school.

**Original Analysis**
![Original Analysis]( https://github.com/CorinneBean/School_District_Analysis/blob/f223123881050e4b491f2200769b131bf3b7c161/Resources/original_scores_by_type.png)

**Adjusted Analysis**
![Adjusted Analysis]( https://github.com/CorinneBean/School_District_Analysis/blob/f223123881050e4b491f2200769b131bf3b7c161/Resources/adjusted_scores_by_type.png)

## Summary

Based on the analysis it is easy to conclude that an impact would be noticeable when you look at each school’s performance individually. This is where we saw the greatest change from a passing rate dropping from 91% to 65%. However, when you compare the numbers for the district you can see that the impact of the academic dishonesty is very minimal. The 9th grade scores which were involved in this incident have been changed to NaN which will no longer calculate to the final totaling of the school district’s performance. 
