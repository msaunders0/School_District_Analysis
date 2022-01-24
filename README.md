# School_District_Analysis

## Overview of School District Analysis

The purpose of this analysis was to gain insight on the possibility of academic dishonesty indicated in the supplied data and measure its impact.

## Results of School District Analysis

### How is the district summary affected?
Averages and percentage values for the district were skewed because of academic dishonesty from Thomas High School's 9th grade class. However, the effect seems to be rather negligble. After removing the 9th grade class scores from Thomas High School, the average math score was 78.9% (before, 79%), average reading score was the same (81.9%), percentage passing math was 74.8% (before, 75%), percentage passing reading was 85.7% (before, 86%), and the percentage overall passing was 64.9% (before, 65%).

Before
![image](https://github.com/msaunders0/School_District_Analysis/blob/main/Resources/district_summary_before.png)

After
![image](https://github.com/msaunders0/School_District_Analysis/blob/main/Resources/district_summary_after.png)

### How is the school summary affected?
The results for Thomas High School were drastically different in the school summary after the data was cleaned. After cleaning the data, THS' % Passing Math was 66.9% (before, 93.3%), % Passing Reading was 69.7% (before, 97.3%), and % Overall Passing was 65.1% (before, 90.9%).

Before
![image](https://github.com/msaunders0/School_District_Analysis/blob/main/Resources/school_summary_before.png)

After
![image](https://github.com/msaunders0/School_District_Analysis/blob/main/Resources/school_summary_after.png)

### How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
Replacing the ninth graders' math and reading scores had a dramatic effect on Thomas High School's overall performance. Before the cleanup, Thomas High School was ranked #2 out of all schools. After the cleanup, Thomas High School fell to #8.

### How does replacing the ninth-grade scores affect the following:
  -  Math and reading scores by grade
       -  Other than the fact that the 9th grade scores for THS were entirely removed (changed to NaN), the math and reading scores by grade were barely different. 
  -  Scores by school spending
       -  THS resides in the $630-644 spending range. Very slight reductions were observed in average math score, average reading score, % passing math, % passing reading, % overall passing.
       -  Before
       -  ![image](https://github.com/msaunders0/School_District_Analysis/blob/main/Resources/spending_summary_before.png)
       -  After
       -  ![image](https://github.com/msaunders0/School_District_Analysis/blob/main/Resources/spending_summary_after1.png)
  -  Scores by school size
       -  Because the 9th grade scores were removed, THS's overall student count dropped from 1635 to 1174. Thus, THS remains in the Medium size bin. Reductions were observed in average math score, % passing math, % passing reading, and % overall passing. Average reading score slightly increased.
       -  Before
       -  ![image](https://github.com/msaunders0/School_District_Analysis/blob/main/Resources/size_summary_before.png)
       -  After
       -  ![image](https://github.com/msaunders0/School_District_Analysis/blob/main/Resources/size_summary_after1.png)
  -  Scores by school type
       -  THS is part of the Charter school type. Reductions were observed for average math score, % passing math, % passing reading, and % passing overall. A slight increase in average reading score was also observed.
       -  Before
       -  ![image](https://github.com/msaunders0/School_District_Analysis/blob/main/Resources/type_summary_before.png)
       -  After
       -  ![image](https://github.com/msaunders0/School_District_Analysis/blob/main/Resources/type_summary_after1.png)
  
## Summary
In summary, many changes were observed after the reading and math scores for the ninth grade at THS were replaced. THS' % passing math, % passing reading, and % passing overall were drastically reduced. THS' overall ranking dropped from #2 to #8. Additionally, THS' student count was reduced by 461, although this did not cause them to cross into the small school size bin. Lastly, a slight increase in average reading score was observed in THS' relative bin for scores by school spending, scores by school size, and scores by school type.  
