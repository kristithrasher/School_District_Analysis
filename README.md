# School_District_Analysis

## Overview of Project
This project contains analysis of school district Data provided to us by Maria. Maria chief data scientist for school district. Her task is analyzing school data in a variety of formats. In this role her task is it provides insights of performance trends and insights. We are asked to help Maria with student funding and student standardized test data. School and district level. We were asked to work with Python and Anaconda and Jupyter notebook. The data is to be treated with confidentiality according to the FERBA (family educational rights and privacy act). After performing our analysis and creating the school district summary reports the school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. 

Due to the evidence of academic dishonesty the school board asked for additional help to wants to uphold state-testing standards. We were asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the grades have been replaced for math and reading for Thomas high school ninth graders, we ran analysis on the updated school district analysis and compared the results. 

### Purpose
The purpose of this project is to aggregate data and show trends in school performance responsible for analyzing school data. To analyze the difference when the Thomas High ninth grade scores were changed to NaNs. This will only help get the most relevant information for the school board. This project is designed to help school board and superintendent in making decisions with school budgets and priorities. 

## Results  Use images and examples of your code if necessary to support your evidence.
How is the district summary affected?
- After extracting the Thomas High School ninth grade math and reading scores, there was not a real significant difference in the district summary data other than very small     percentage in data.
![district summary](https://user-images.githubusercontent.com/94208810/144725302-69f99866-48a1-4b03-81a2-12cd0dd95292.png)

How is the school summary affected?
-The overall percentage for Thomas High School went up when we removed the 9th grade scores and just used 10th-12th grade Thomas High School math and reading. i have enclosed a picture to show difference in summary. When the 9th grade scores were changed to nan values it showed performance for Thomas High School at 60% performance. 

-Summary with null value 9th grade scores
![school summary with 9th grade nan scored in](https://user-images.githubusercontent.com/94208810/144725113-6e95a03b-084e-42ec-8e4b-ae0c2f56dfd7.png)

- Summary without 9th grade scores went up to 90% 
- ![School summary Thomas 10-12 grades were factored in without 9th Grade](https://user-images.githubusercontent.com/94208810/144725054-0aab658d-d93c-40f8-971a-9600a7c96175.png)

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?

- After replacing the ninth graders' math and reading scores it showed no real change in Thomas High School's Performance. They are still ranked in Top Five for Performance. 

![Top5SchoolsRevised Analysis](https://user-images.githubusercontent.com/94208810/144724084-07564d32-e6c4-4912-84ad-1684733d6557.png)

How does replacing the ninth-grade scores affect the following:

- Math and Reading Scores by Grade
  -The scores of all grades showed no difference and remained at the same level.

- Scores by School Spending: 
    - The lower amount per student the higher the performance was which showed when students who had less than $584 per student performed at a 90%. 
  
  ![Spending Ranges](https://user-images.githubusercontent.com/94208810/144724588-54a332d1-d410-4077-9329-45de56806ed6.png)

  
- Scores by School Size: 
  - Medium size schools performed at a higher level than small and large sized schools. 
  
  ![school size](https://user-images.githubusercontent.com/94208810/144724562-0a8053ef-2253-4eed-b386-bbecabeb26f4.png)
    
- Scores by School Type: 
  - Charter Schools performed at 90% and District schools at 90% at 54%. Replacing the ninth-grade scores for Thomas High School did not affect this performance as a whole. 
  
  ![Screenshot (91)](https://user-images.githubusercontent.com/94208810/144724375-7b363520-02c2-4124-94a0-cdb2bfdf9dd5.png)

## Summary: 

This new assignment consisted of two technical analysis deliverables and a written report to present my results. After replacing the ninth grade reading and math scores for Thomas High School there was no real difference in the school district analysis. The school summary showed the performance of Thomas High School was lower when the 9th grade scored were replaced with NANs. However, when we calculated just the Thomas High 10th thru 12th grade, we saw a significant difference in the performance and Thomas high school performed as a top 5 high school. The scores by school size show that the medium size schools ranging from 1000-2000 students had higher scores than smaller or larger size schools. The school type Charter outperformed the district schools.
