# School District Test Analysis
## A comparison with and without Thomas High School 9th Grade Results

### Questions

How is the district summary affected?
- The Average Math Score decreases from 79.0 to 78.9

How is the school summary affected?
- The Average Math Score decreases for Thomas High School: 83.42 -> 83.35
- The % Passing Math decreases for Thomas High School: 93.27 -> 93.19

- The Average Reading Score increases for Thomas High School: 83.85 -> 83.90
- The % Passing Reading decreases for Thomas High School: 97.31 -> 97.02

- The % Overall Passing for Thomas High School drecreases: 95.29 -> 95.10
  - Note: I did not count the 9th graders in the formula (I did not count NaNs as fails)
  - Note: I kept the (inaccurate) formula from the lesson


How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
- Thomas High School drops in % Overall disctrict ranking: 2nd Best -> 5th Best. This is the most noticeable affect. 

How does removing the ninth grade scores affect the following:
- Math and Reading Scores by Grade
  - Thomas High School now has NaN for 9th grade Math and Reading results. Every other result is unchanged.

- Scores by School Spending
  - Scores by School Spending is minimaly affected by removing 9th Grade Results from Thomas High School
    - No noticeable change to the 10th of a percent for average scores
  - Note: I chose not to decremented the Thomas High School population, I only removed student grades 
  - Note: Thomas High School was, and remains, in the 3rd bin, $630-$644

- Scores by School Size
  - Scores by School Size is minimaly affected by removing 9th Grade Results from Thomas High School
    - No noticeable change to the 10th of a percent for average scores
  - Note: Thomas High School is a medium sized school

- Scores by School Type
  - Scores by School Type is minimaly affected removing 9th Grade Results from Thomas High School
    - No noticeable change to the 10th of a percent for average scores
  - Note: Thomas High School is a Charter School


### Results Summary
District Summary
![District Summary with THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Disctrict%20Summary%20w%209.PNG)
![District Summary without THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Disctrict%20Summary%20wo%209.PNG)

School Summary
![School Summary with THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/School%20Summary%20w%209.PNG)
![School Summary without THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/School%20Summary%20wo%209.PNG)

High Performing Schools
![High Performing Schools with THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/High%20Performing%20Schools%20w%209.PNG)
![High Performing Schools without THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/High%20Performing%20Schools%20wo%209.PNG)

Low Performing Schools
![Low Performing Schools with THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Low%20Performing%20Schools%20w%209.PNG)
![Low Performing Schools without THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Low%20Performing%20Schools%20wo%209.PNG)

Math Scores by Grade

![Math Scores by Grade with THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Math%20Scores%20by%20Grade%20w%209.PNG)
![Math Scores by Grade without THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Math%20Scores%20by%20Grade%20wo%209.PNG)

Reading Scores by Grade

![Reading Scores by Grade with THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Reading%20Scores%20by%20Grade%20w%209.PNG)
![Reading Scores by Grade without THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Reading%20Scores%20by%20Grade%20wo%209.PNG)

Scores by School Spending
![Scores by School Spending with THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Scores%20by%20School%20Spending%20w%209.PNG)
![Scores by School Spending without THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Scores%20by%20School%20Spending%20wo%209.PNG)

Scores by School Size
![Scores by School Size with THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Scores%20by%20School%20Size%20w%209.PNG)
![Scores by School Size without THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Scores%20by%20School%20Size%20wo%209.PNG)

Scores by School Type
![Scores by School Type with THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Scores%20by%20School%20Type%20w%209.PNG)
![Scores by School Type without THS 9th Grade](https://github.com/Calistic/School_Disctrict_Analysis/blob/master/Pictures/Scores%20by%20School%20Type%20wo%209.PNG)


#Challange
