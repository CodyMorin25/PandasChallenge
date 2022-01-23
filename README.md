# PandasChallenge

## School District Analysis
Used Anaconda, Jupyter Notebook, Pandas, and Python in this analysis.

### Overview of Project
It was found that there was evidence of academic dishonesty (i.e. the reading and math grades for Thomas High School ninth graders seems to have been altered). The school board was unsure to the extent of the dishonesty and want to uphold the state-testing standards and turned to Maria. She tasked me with replacing the reading and math scores for Thomas High School ninth graders with NaNs but keeping the data intact. Also once that was done to repeat the analysis done to it before the dishonesty was found.

### Results

#### School Summary Affected
- The school summary only changes in regards the Thomas High School since the percentages for their students passing math, reading, or both will drop since a quarter of the students won't have scores. But will still be included in the total number of students.
![District_Summary_old.png](

#### District Summary affected 
- In changing the math and reading scores for Thomas High School ninth graders to NaNs, the total schools and total students are not affected. The average math scores change from 79.0 to 78.9 but the average for reading stayes the same at 81.9.
##### Old Data
![District_Summary_old.png](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/District_Summary_Original.PNG)
##### New Data
![District_Summary_new.png](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/District_Summary_New.PNG)

#### Thomas High School Performance
- When using the decitful data Thomas High School places in the top five of the schools at second but with the new data it places eighth. The drop was expected since all of Thomas High School's ninth grades recieved no score but was still counted towards the schools total.
##### Old Top
![top_5_schools.old](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/Top_5_Schools_Original.PNG)
##### New Top
![top_10_schools_new](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/Top_10_Schools_New.PNG)

#### Math and Reading scores affected
- The math and reading scores per grade changed for Thomas High School but not for the rest mainly due to them being grouped by grade. Where for Thomas High School where there should be a number for ninth graders there is instead NaN.
##### Math Scores Old
![math_scores_old](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/Math_by_grade_Original.PNG)
##### Math Scores New
![math_scores_new](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/Math_by_grade_New.PNG)
##### Reading Scores Old
![reading_scores_old](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/Reading_by_grade_Original.PNG)
##### Reading Scores New
![reading_scores_new](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/Reading_by_grade_New.PNG)

#### Scores by School spending/size/type affected
-For the scores by school spending, size, and type. The only changes came to where Thomas High School was grouped and the others stayed the same.

##### Spending Old
![Spending_old](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/School_Spending_Summary_Original.PNG)
##### Spending New
![Spending_new](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/School_Spending_Summary_New.PNG)
##### Size Old
![size_old](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/School_Size_Summary_Original.PNG)
##### Size New
![size_new](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/School_Size_Summary_New.PNG)
##### Type Old
![type_old](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/School_Type_Summary_New.PNG)
##### Type New
![type_new](https://github.com/CodyMorin25/PandasChallenge/blob/main/Images/School_Type_Summary_Original.PNG)
