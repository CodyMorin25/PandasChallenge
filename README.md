# PandasChallenge

## School District Analysis
Used Anaconda, Jupyter Notebook, Pandas, and Python in this analysis.

### Overview of Project
It was found that there was evidence of academic dishonesty (i.e. the reading and math grades for Thomas High School ninth graders seems to have been altered). The school board was unsure to the extent of the dishonesty and want to uphold the state-testing standards and turned to Maria. She tasked me with replacing the reading and math scores for Thomas High School ninth graders with NaNs but keeping the data intact. Also once that was done to repeat the analysis done to it before the dishonesty was found.

### Results

- The school summary only changes in regards the Thomas High School since the percentages for their students passing math, reading, or both will drop since a quarter of the students won't have scores. But will still be included in the total number of students.
- In changing the math and reading scores for Thomas High School ninth graders to NaNs, the total schools and total students are not affected. The average math scores change from 79.0 to 78.9 but the average for reading stayes the same at 81.9.
- When using the decitful data Thomas High School places in the top five of the schools at second but with the new data it places eighth. The drop was expected since all of Thomas High School's ninth grades recieved no score but was still counted towards the schools total.
- The math and reading scores per grade changed for Thomas High School but not for the rest mainly due to them being grouped by grade. Where for Thomas High School where there should be a number for ninth graders there is instead NaN.
-For the scores by school spending, size, and type. The only changes came to where Thomas High School was grouped and the others stayed the same.

