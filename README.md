# School_District_Analysis

## Project Overview
Maria a data scientist for City School District has requested us to analyze reading and math scores for the high schools in the district. Following deliverables were requested as part of the project.
  - A high-level snapshot of the district's key metrics, presented in a table format
  - An overview of the key metrics for each school, presented in a table format
  - Tables presenting each of the following metrics:
    - Top 5 and bottom 5 performing schools, based on the overall passing rate
    - The average math score received by students in each grade level at each school
    - The average reading score received by students in each grade level at each school
    - School performance based on the budget per student
    - School performance based on the school size 
    - School performance based on the type of school

## resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: anaconda3, python 3.7.7, jupyter notebook

## Summary
  - District's key metrics
   !["district summary"](./Resources/district_summary.png "District's key metrics")
  
  - Key metrics for each school
   !["schools' summary"](./Resources/schools_summary.png "Schools' key metrics")
  
  
  - Additional Metrics:
    - Top 5 performing schools, based on the overall passing rate
     !["Top 5 schools"](./Resources/top5_schools.png "District's Top 5 schools")
    
    - Bottom 5 performing schools, based on the overall passing rate
     !["Bottom 5 schools"](./Resources/bottom5_schools.png "District's Bottom 5 schools")
    
    
    - The average math score received by students in each grade level at each school
     !["Average Math all grades"](./Resources/avg_math_scores_by_grade.png "Average math score in each grade of schools")
    
    - The average reading score received by students in each grade level at each school
     !["Average Reading all grades"](./Resources/avg_reading_scores_by_grade.png "Average reading score in each grade of schools")
    
    
    - School performance based on the budget per student
     !["Performance based on the budget per student"](./Resources/budget_per_student.png "School performance based on the budget per student")
    
    - School performance based on the school size 
     !["Performance based on the school size"](./Resources/school_size.png "School performance based on the school size")
    
    - School performance based on the type of school
     !["Performance based on the type of school"](./Resources/type_of_school.png "School performance based on the type of school")
  
  

Once all the deliverables were presented, we were informed that there was a mistake.

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.

So she has requested us to replace the math and reading scores, and once that is done, she asked us to repeat the school district analysis with the updated data, and write up a report to describe how these changes affected the overall analysis.

## Challenge Overview
Replace math and reading scores for Thomas High School 9th grade with 'NaN' and repeat the analysis and provide the same deliverables as above and answer the following questions.

## Challenge Summary
  - District's key metrics
   !["district summary"](./Resources/challenge_district_summary.png "District's key metrics")
  
  - Key metrics for each school
   !["schools' summary"](./Resources/challenge_schools_summary.png "Schools' key metrics")
  
  
  - Additional Metrics:
    - Top 5 performing schools, based on the overall passing rate
     !["Top 5 schools"](./Resources/challenge_top5_schools.png "District's Top 5 schools")
    
    - Bottom 5 performing schools, based on the overall passing rate
     !["Bottom 5 schools"](./Resources/challenge_bottom5_schools.png "District's Bottom 5 schools")
    
    
    - The average math score received by students in each grade level at each school
     !["Average Math all grades"](./Resources/challenge_avg_math_scores_by_grade.png "Average math score in each grade of schools")
    
    - The average reading score received by students in each grade level at each school
     !["Average Reading all grades"](./Resources/challenge_avg_reading_scores_by_grade.png "Average reading score in each grade of schools")
    
    
    - School performance based on the budget per student
     !["Performance based on the budget per student"](./Resources/challenge_budget_per_student.png "School performance based on the budget per student")
    
    - School performance based on the school size 
     !["Performance based on the school size"](./Resources/challenge_school_size.png "School performance based on the school size")
    
    - School performance based on the type of school
     !["Performance based on the type of school"](./Resources/challenge_type_of_school.png "School performance based on the type of school")

## Comparison
  - How is the district summary affected?
   !["district summary"](./Resources/district_summary.png "District's key metrics")
   !["district summary"](./Resources/challenge_district_summary.png "District's key metrics after changes")
   
   After removing 9th grade math and reading grades for Thomas High School, there was almost no effect on the average math and reading scores, however % passing in math, reading, and overall went down by 1.
   
   
  - How is the school summary affected?
   !["schools' summary"](./Resources/schools_summary.png "Schools' key metrics")
   !["schools' summary"](./Resources/challenge_schools_summary.png "Schools' key metrics after changes")
   
   There is not much change in average math and reading scores, however the % math passing fell by 26%, % reading passing fell by 27%, and % overall passing fell by 26%.
   
   
  - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   !["Top 5 schools"](./Resources/top5_schools.png "District's Top 5 schools")
   !["Top 5 schools"](./Resources/challenge_top5_schools.png "District's Top 5 schools after changes")
   
   Thomas High School was Top 2nd school in the district before the grades were removed once they were removed it is no longer in the TOP 5 list.
   
   !["Bottom 5 schools"](./Resources/bottom5_schools.png "District's Bottom 5 schools")
   !["Bottom 5 schools"](./Resources/challenge_bottom5_schools.png "District's Bottom 5 schools after changes")
   
   This listing was not affected.
   
   
  - How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
      1) Math:
        
        !["Average Math all grades"](./Resources/avg_math_scores_by_grade.png "Average math score in each grade of schools")
        !["Average Math all grades"](./Resources/challenge_avg_math_scores_by_grade.png "Average math score in each grade of schools after changes")
        
        Other grades' scores were not affected.
        
      2) Reading:
        
        !["Average Reading all grades"](./Resources/avg_reading_scores_by_grade.png "Average reading score in each grade of schools")
        !["Average Reading all grades"](./Resources/challenge_avg_reading_scores_by_grade.png "Average reading score in each grade of schools after changes")
        
        Other grades' scores were not affected.
        
    - Scores by school spending
      !["Performance based on the budget per student"](./Resources/budget_per_student.png "School performance based on the budget per student")
      !["Performance based on the budget per student"](./Resources/challenge_budget_per_student.png "School performance based on the budget per student after changes")
      
      Scores by school spending fell by 6 to 7 % in % passing math, reading, and overall in $630-644 bin.
      
    - Scores by school size
      !["Performance based on the school size"](./Resources/school_size.png "School performance based on the school size")
      !["Performance based on the school size"](./Resources/challenge_school_size.png "School performance based on the school size after changes")
      
      Scores by school size fell by 6% in % passing math, reading, and overall in medium school size (1000 - 2000) category.
      
    - Scores by school type
      !["Performance based on the type of school"](./Resources/type_of_school.png "School performance based on the type of school")
      !["Performance based on the type of school"](./Resources/challenge_type_of_school.png "School performance based on the type of school after changes")
      
      Scores by school type fell by 3 to 4 % in passing math, reading, and overall in charter schools.
      
