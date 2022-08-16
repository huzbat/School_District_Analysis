# School_District_Analysis

The purpose of deliverable 3 is to write a report that summarizes my updated analysis and compares it with the results from the module.
My analysis will contain the following:

### 1. Overview of the school district analysis: Explain the purpose of this analysis.
Our objective was to analyze the data of an entire School District (both as a whole and individual schools), such as spending, funding, size, and student grades in order to gain novel insights and provide visual simplicity on these metrics. Accounting for potential academic dishonesty variables was also considered and made easier with visual simplicity.
### 2. Results: Using bulleted lists and images of DataFrames as support, address the following questions.
Considering potential academic dishonesty by the ninth grade students of Thomas High School analysis was completed twice.
Initially all student data was accounted for.
However, in the second trial the scores of ninth graders of Thomas High School were omitted from the calculations by replacing the scores with NaN.
View Dataframe below for visual.
![image](https://user-images.githubusercontent.com/87838015/185002111-bae80470-f10a-42ee-a418-80a3f17bd2c8.png)


#### How is the district summary affected omitted?
The overall passing percentages of Thomas High School decreased by 0.11%
#### How is the school summary affected omitted?
The average scores of Thomas High School for math and reading *increased* by 0.06
#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools omitted?
**School rankings are unchanged.**

#### How does replacing the ninth-grade scores affect the following:
##### Math and reading scores by grade
### Average Scores by Grade Level
After an in-depth analysis it was found that school was a bigge factor in scores than the grade of the individual. With a score variation of 1-2% based on grade. As seen below.


##### Scores by school spending
School budget did not have a significant affect on the grades of students. As seen below.
![image](https://user-images.githubusercontent.com/87838015/185002146-224d7bbd-f468-4d9f-851a-38771786c515.png)
##### Scores by school size
School type resulted in a significant difference in grade level.  It was found that school sizes classified as Large has the lowest average scores, whereas, the differenc ein scores between medium and small schools was negligible.
As seen below.
![image](https://user-images.githubusercontent.com/87838015/185002162-59cc1f77-b6ef-4779-ab3a-3fc5becff054.png)
##### Scores by school type
Charter schools generally performed better than District schools. Evident by the fact that the top 5 schools with highest overall grades were all Charter schools.
As seen below.
![image](https://user-images.githubusercontent.com/87838015/185002017-d9663409-fab7-4281-a81c-f5ae96c8d67c.png)

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
#### How is the district summary affected replaced with NaN?
The overall passing percentage for the entire district fell to 64.9%
#### How is the school summary affected replaced with NaN?
The overall passing percentage for Thomas High School fell to 65%
#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools replaced with NaN?
Replacing the scores with NaN resulted in Thomas High School no longer being included on the list of top five schools


Author: Huzaifa Hussain
For all questions and inquiries, please contact me on [LinkedIn](https://www.linkedin.com/in/huzaifa-s-hussain/).



