# school-district-analysis

# Overview:
In this project I used data from schools across a school district to perform an analysis that will inform future decision making within the district.  My analysis focused on test scores, school budgets, school type, and school size.  I used Python in Jupyter Notebooks to gain insights like the budget spent on each student, how school size affects test scores and budgets, and average test scores across all schools.  These insights will help future school administrators to most effectively allocate resources between schools within the district. Mid-way through the project, I was informed that the grade statistics for 9th grade students at Thomas High School showed evidence of academic dishonesty.  I then needed to remove the data from 9th graders at Thomas High School in order to ensure that my insights were accurate.  Once the data for 9th grade students at Thomas High School was removed, I was able to redo the analysis for the school district with more accurate results. 

# Results:
Once the data for 9th graders from Thomas High School were removed, the following metrics yielded the following results. 

- How is the district summary affected?
  - The passing percentages for math scores, reading scores, and overall passing were slightly increased after the fraudulent data was removed.


-  How is the school summary affected?
  - The percentage of students who passed math, reading, and who passed overall significantly increased for Thomas High School.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - The fraudulent scores initially recorded placed Thomas High School's performance in the bottom 5 schools.  The updated scores that accurately reflected the school's performance showed that Thomas High School was actually the second highest performing school.  

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - Replacing the ninth-grade scores at Thomas High School did not affect the math and reading scores for other schools, and ninth-grade scores for Thomas High School were not counted in the analysis. 
  
  - Scores by school spending
    - Updating the ninth-grade scores increased the passing percentages for the $645-$675 category, and decreased the passing percentages for the $630-$644 category.
    
  - Scores by school size
    - Updating the ninth-grade scores decreased the passing percentage for medium sized schools. 
    
  - Scores by school type
    - Updating the ninth-grade scores decreased the overall passing percentage for Charter schools. 
    
# Summary: 
- The most significant change is that before the 9th grade test scores were updated, Thomas High School was in the bottom 5 performing schools in the district.  After I updated my analysis to remove any fraudulent data, I learned that Thomas High School was the second highest performing school in the district.

- Another change is that the percentages for passing math, passing reading, and overall passing statistics were all increased when the incorrect 9th-grade data was removed from the data set

- Schools that spent an average of $630 - $644 per student saw a decreased passing rate for math, reading, and overall passing when the 9th grade data was corrected.

- Medium sized schools also saw a decreased passing rate for math, reading, and overall passing when the 9th grade data was corrected.
