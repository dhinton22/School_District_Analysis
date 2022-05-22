# School_District_Analysis

The goal of this project is to organize and calculate scores based on grade, school type, school size, and budget for the school board. While reviewing the data, the school board recognized some discrepancies with the 9th grade scores for Thomas High School, therefore, the reading and math scores were converted to NaN to ensure the end point data is not skewed by false scores. 

# Results

The first step was to remove the 9th grade reading and math scores. This was completed by using the .loc method  to select all the reading and math scores from the 9th grade at Thomas High School and replace the values with NaN (Not a Number). 

 1. How is the district summary affected?
 
    - The District summary was marginally affected by removing the 9th grade reading and math scores. The summary shows that the Average Math Score decreased by .1% and the Average Reading Score remained the same. 
    ![image](https://user-images.githubusercontent.com/103547108/169710705-fc7515e4-01de-404b-87e5-32b44bf98bae.png)
    ![image](https://user-images.githubusercontent.com/103547108/169710711-ef38b0fe-f35f-44ce-96c6-24a1a32aeae3.png)

 2. How is the school summary affected?
    - The summary shows that Thomas High School :
        - Average Math Score decreased by .06
        - Average Reading Score increased by .05
 3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - Replacing the ninth graders' math and reading scores does not greatly affect Thomas High Schools performance relative to other schools. Thomas High School is in the top 5 schools in the district. 
   ![image](https://user-images.githubusercontent.com/103547108/169710929-6644a66d-f069-4728-870e-49bfd778ff5c.png)
 
 4. How does replacing the ninth-grade scores affect the following:
      -Math and reading scores by grade
        - The ninth-grade math and reading scores for Thomas High School 9th graders were changed to Nan. This reduced the amount of Thomas High School students from 39,170 to 38,709. The reduction impacted all categories of scores and percentages. Removing the ninth grade scores dropped the schools passing percentage.        
        math:
 ![image](https://user-images.githubusercontent.com/103547108/169711164-993639c8-9de7-4a2a-a6ab-bc15f99247be.png)
        
        reading:
![image](https://user-images.githubusercontent.com/103547108/169711179-c74f318f-b6e4-4a14-bc0b-690b6bbeec81.png)

      -Scores by school spending
        - Replacing the 9th grade reading and math scores does not seem to affect the school spending for Thomas High School. Also it appears that Charters schools appear to have better scores however less school spending. 


 ![image](https://user-images.githubusercontent.com/103547108/169711472-a75ab4c6-d170-49e9-bdfb-2970350b3051.png)

      -Scores by school size
        - Omitting the 9th graders reading and math scores affected the school size because the student count dropped by 471 students. Also I noticed that the larger the school size the poorer the scores. 
![image](https://user-images.githubusercontent.com/103547108/169711577-42f2d7f0-1939-42c3-9956-88ace975b208.png)

      -Scores by school type
         - School type shows that charter schools earn higher grade score averages.
         - Charter schools pass at an overall percentage of 90% while district school type pass ag 53.7%
 ![image](https://user-images.githubusercontent.com/103547108/169711714-f83b4257-2ff8-4e3e-ac5a-5233a5a3a6e1.png)


#Summary

In summary, I determined that removing the 9th graders scores for Thomas High School affected the district as a whole but on a very small scale. Changing 471 records to 'NaN' did not greatly skew the overall passing percentage of 39100 students in the district. However, academic dishonestly is frowned upon.
