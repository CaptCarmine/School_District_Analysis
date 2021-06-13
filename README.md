# School District Analysis

## Overview

 Maria, the chief data scientist for her school district was tasked with analyzing the standardized school test scores for math and reading, which recently happened. I was brought on to help her organize the data using Pandas and Numpy. I already helped her find the average scores for each test, per grade. As well as find the percetange of students who passed overall, based on the size and funding the school recieved.

 We recently found out that a number of student in the 9th grade class of Thomas High School cheated on the standardized exams. With that found I have been task to look back on the data, and make a number of modifications.

- She has asked me To replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Creating tables presenting each of the following metrics:
  1. Top 5 and bottom 5 performing schools, based on the overall passing rate
  2. The average math score received by students in each grade level at each school
  3. The average reading score received by students in each grade level at each school
  4. School performance based on the budget per student
  5. School performance based on the school size
  6. School performance based on the type of school

## Results

See the Results below for changes in Thomas high school standings with the 9th graders scores dropped and not removed from population.
![Pre dropping 9th graders scores](https://github.com/CaptCarmine/School_District_Analysis/blob/main/Resources/Per_school_not_dropping_9th_graders.png?raw=true)

Using bulleted lists and images of DataFrames as support, address the following questions.

- How is the district summary affected?
  1.Well, based on if you remove the 9th graders or not it takes Thomas high school from the number 2 school in the discrict to a middle of the pack school.
- How is the school summary affected?
  1.The school summary is only effected, for Thomas High school, bringing all there standardized scores around 25% points.

See the Results below for changes in Thomas high school standings with the 9th graders scores dropped and removed from population.
![Post dropping 9th graders scores](https://github.com/CaptCarmine/School_District_Analysis/blob/main/Resources/Per_school_After_dropping_9th_graders.png?raw=true)
  
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  1. It brings Thomas High school, back to one of the Top schools. As as school, once the 9th grade population is dropped there is a less than a 0.5 % in there grades across Math, reading and overall passing%  .
- How does replacing the ninth-grade scores affect the following:
  1. Math and reading scores by grade
     -By grade there is a large change as the data, shows both thomas high school 9th grade sections, with an X.
  2. Scores by school spending
     - There is no change in significance, by school spending.
  3. Scores by school size
     -There is no change in significance, by school size.
  4. Scores by school type
     -There is no change in significance, by school type.

## Summary
<!-- Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. -->

The exercise, about replacing the school data with NaN, showed interesting information about how data sets can work. By replacing the data, and not showing the difference, it had large scale affects on the schools placement,  and average scores. Once we went back and cleaned the data to not include those students in the denominator of total students for Thomas high, there were only very slight variations to the values for Average scores in math, and reading. and % scores for math, reading and overall percent. I believe this shows the importance of both, how vital cleaning the data is, and how much NaN fields. can modify integer value reporting.  
