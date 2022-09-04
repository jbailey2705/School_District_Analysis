# School_District_Analysis

## Project Overview

Maria, the Chief Data Scientist of the city School District has been tasked with preparing students test scores for Math and Reading at the High School level. The information will be used to make decisions on the proficiency of city school testing.
Maria has asked for help in cleaning the data and providing further data analytics to help analyze student funding & standardized test scores. The analysis provided will help Maria and her supervisior in making decisions regarding school budgets & alocations. 

Using two rescources to compile data, we have presented Maria the followin information:
  1. Distict Summary - snapshot of the district's key metric
  2. Per School Summary - provides key metrics for each school
  3. A table presenting top and bottom 5 performing schools
  4. Average of math & reading scroes for grades 9-12
  5. School performance based on the following:
      - Budget
      - School Type
      - School Size

## Resources:

For this project will will be using the following programs:
      - Anaconda
      - Python
      - Jupitor Program (Pandas)

[schools_complete.csv](https://github.com/jbailey2705/School_District_Analysis/files/9485340/schools_complete.csv)

[students_complete.csv](https://github.com/jbailey2705/School_District_Analysis/files/9485341/students_complete.csv)

[clean_students_complete.csv](https://github.com/jbailey2705/School_District_Analysis/files/9485342/clean_students_complete.csv)

## School Analysis Results

After rereviewing the data with Maria, we removed the 9th grade students for Thomas HS, 461 students in total

1. Below snapshots are of the District Summary - showing the total population,budget, average scores and passing rates for the entire district and and revised removing the 9th grade scores for Thoma HS. 

## Original District Summary:

![Screen Shot 2022-09-04 at 2 14 55 PM](https://user-images.githubusercontent.com/109354592/188329900-489fca1a-3801-43f6-8526-f324bb8ed0fd.png)

## District Summary Revised:

![Screen Shot 2022-09-04 at 2 18 08 PM](https://user-images.githubusercontent.com/109354592/188329978-d2e5c375-32d6-4eb0-9995-d0391c0f1c50.png)

2. Over all there are a total of 1635 students at Thomas HS, raising some concerns with the school board.

## Original Analysis

![Screen Shot 2022-09-04 at 2 38 43 PM](https://user-images.githubusercontent.com/109354592/188330975-5df44676-65c9-4369-9a18-03e884155dc3.png)

## Revised Analysis

After adjusting the summary with only the number of students with scores at Thomas HS, passing % was impacted slightly.

![Screen Shot 2022-09-04 at 2 51 10 PM](https://user-images.githubusercontent.com/109354592/188331143-a2c9592e-295b-4ac4-9505-9388165b92dc.png)

Revised without THS grade 9 students

![Screen Shot 2022-09-04 at 2 55 31 PM](https://user-images.githubusercontent.com/109354592/188331230-28e45055-c9de-46ce-8728-5a7655a93b13.png)

3. By replacing the ninth graders math and reading scores,THS performance ranking dropped to the bottom 5.

## Initial Analysis

![Screen Shot 2022-09-04 at 3 04 31 PM](https://user-images.githubusercontent.com/109354592/188331512-4fdd864c-d691-405d-b621-7ac25a1c0bdb.png)

## Revised Analysis

![Screen Shot 2022-09-04 at 3 06 01 PM](https://user-images.githubusercontent.com/109354592/188331550-a66224eb-d9d3-413b-ab35-4f51d1d9829f.png)

## Adjusted School type Summary

![Screen Shot 2022-09-04 at 3 08 31 PM](https://user-images.githubusercontent.com/109354592/188331637-c7b5d067-b876-490c-89d0-a45e26f0b80f.png)


# Summary

By conducting further analysis and removing THS 9th graders from the sample size Maria & the School Board were able to reajust budget allocaitons amounst the eniter Shool District accordingly by concluding the 4 data poiints provided: 

1. THS performance situtates the school at the 8th place in the district with the updated calculations.
2. THS passing rate changed dropped from 91% to 65%.
3. NaN at the grade level will now be on the analysis for THS 9th graders.
4. Overall data analysis saw shifts in the Math and Reading averages.





