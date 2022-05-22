# PyCitySchools_Challenge

## Overview of PyCitySchools_Challenge
The initial school district analysis was performed to evaluate the standardized testing scores of the PyCity school district. After the initial analysis the school board found evidence of academic dishonesty in the reading and math grades for 9th grade students at Thomas High School. To uphold state-testing standards, I have been tasked with removing the testing scores for the 9th grade students at Thomas High School while keeping the remainder of the data intact. 

## Results
1. How is the district summary affected?

The district summary was affected because the 9th grade students at Thomas High School reading and math scores turned to null. This would affect the overall average scores for the district since these scores are now no longer included. The student count was not affected since that number is found by counting each unique Student ID.

### Original Analysis
![Original Analysis](https://github.com/CorinneBean/School_District_Analysis/blob/3a1cc2617144300b1d0e0265433be7f5d7afd0e7/Resources/Original%20District%20Summary.png)

### Adjusted Analysis
![Adjusted Analysis](https://github.com/CorinneBean/School_District_Analysis/blob/3a1cc2617144300b1d0e0265433be7f5d7afd0e7/Resources/Adjusted%20District%20Summary.png)

When the two charts are compared, you can see that removing the scores of the 9th graders at Thomas High School had a minimal effect on the district summary data set. The change appears to be less than 1%.


2. How is the school summary affected?
```
In the original analysis, Thomas High School had a 91% passing rate. After removing these scores, the testing data was adjusted accordingly. 
```
### Original Analysis

#### Adjusted Analysis
```
Before removing the grades for 9th grade students at Thomas High School, the school appeared to be doing tremendously well on state-standardized testing. However, once the scores were removed because of academic dishonesty the score for Thomas High School dropped to 65% from the original 91% passing rate.
```
3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
4. How does replacing the ninth-grade scores affect the following:
	- Math and reading scores by grade
	- Scores by school spending
	- scores by school size
	- scores by school type

## Summary
