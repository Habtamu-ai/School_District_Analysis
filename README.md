

# School_District_Analysis
This project analyzes student funds and student standardized test scores. The project uses the anaconda software packages and python programing language as a tools for the analysis.
# Overview of the school district analysis
The main purpose of this project is to investigate if students reading and math score is altered by the school districts and to know the full extent of it. 
Thomas High School is one of the  main suspect by the school board. This analysis is going to replace the Thomas High School ninth grade reading and math score and run the analysis and see if there is any change.

# Result
First, we removed grade 9th math and reading score from Thomas High School.The two consquestive figures below show the school data before and after replacing grade ninth math and reading socores of Thomas High School.
### Fig.1. Overview of the School data
![School_data](https://user-images.githubusercontent.com/78656720/111785675-48548200-8893-11eb-92a6-8aebb2339f4d.png)
### Fig.2. School data after Thomas High School grade 9th score is Replaced
![Thomas_Grade_9th_removed](https://user-images.githubusercontent.com/78656720/111785702-50acbd00-8893-11eb-9155-3f570d1d5234.png)

## Second, we create the following metrics;
   #### The district summary
   #### The school summary
   #### The top 5 and bottom 5 performing schools, based on the overall passing rate
   #### The average math score for each grade level from each school
   #### The average reading score for each grade level from each school
   #### The scores by school spending per student, by school size, and by school type 
   
   
   #### The district summary
   Looking at the two figures below the first district summary and the district summary after we replaced the grade 9th Thomas High school, there is a change in the math, reading and overall percentage passing rate though it is minimal.
   ##### Fig. 3 New District Summary
![New_District_Summary](https://user-images.githubusercontent.com/78656720/111794066-3d521f80-889c-11eb-923d-fe72270d94bc.png)


   ##### Fig. 4 District Summary
![District Summary](https://user-images.githubusercontent.com/78656720/111794795-f87ab880-889c-11eb-9874-73e36c11d8ab.png)

 #### The school summary
 Based on the recommendation of the school board we have looked closely each schools summary and we find the following in Thomas High School. Looking at figure five and six , the *overall passing percentage* droped from 90.4 to 65 percent, *reading* from 97 to 69, and *math* from 93 to 67.But this might be misleading, because we only remove the score but we kept the student number in the data which might affect the overall passing and the school budget.
 
   ##### Fig. 5 District Summary after removing math and reading score of Thomas High School
 ![New_per school summary](https://user-images.githubusercontent.com/78656720/111797352-78a21d80-889f-11eb-8ec3-f903c554707f.png)
  
  ##### Fig. 6 District Summary 
 ![perschool_summary_latest](https://user-images.githubusercontent.com/78656720/111802940-ef8de500-88a4-11eb-83a7-ac6639b88003.png)
  
  ##### Fig. 7 District Summary after without grade 9th students 
 ![PER_School Summary_Thomas](https://user-images.githubusercontent.com/78656720/111797278-632cf380-889f-11eb-8180-924a2817feae.png)

We also analyze the top  and bottom five schools based on their school performance.
and presented the tabel below.
#### The top 5 and bottom 5 performing schools, based on the overall passing rate
![Top Terforming School](https://user-images.githubusercontent.com/78656720/111829318-e9a6fc80-88c2-11eb-8e19-7e7b0d92e0b0.jpeg)

![Low Performing Schools](https://user-images.githubusercontent.com/78656720/111829708-6df97f80-88c3-11eb-8154-a0da6a09c627.png)

To figure out what contributes for the schools high loa performance we also run the analysis by school budget and by school size.
looking at the tabel below we cannot say the higher performing school has biger budget than the low performing school. Diving deep we also run the analysis by school size based on number of students. As we can see from the tabel below schools that are small(student number less than 1000) scores overlall passing 90 percent. While the overall passing parcentage of schools that are large (students number,between 2000 and 5000) is 58.  By diving deep more we have also looked at school performance based on the type of school. Fig 10. shows Charter schools overall passing percentage is 87.While district schools overall passing percentage is 54.
![Score by Spending](https://user-images.githubusercontent.com/78656720/111833761-01817f00-88c9-11eb-8c35-0227b4401d5e.png)
![Scores by Size](https://user-images.githubusercontent.com/78656720/111833777-06dec980-88c9-11eb-895f-553dbbad8bca.png)
![Scores By School Type](https://user-images.githubusercontent.com/78656720/111833785-09d9ba00-88c9-11eb-840a-6a2e58181031.png)

# Summary
Summerizing our analysis we have noticed four main develppment from the previous analysis
By just looking at the overall passing percentage we can summerize the following
## Math and reading scores by grade
   - 9th:
   - 10th:
   - 11th:
   - 12th: 
 ## Scores by school spending
    - <$584:
    - $585-629:
    - $630-644:
    - $645-675:
   
  ## Scores by school size
     - Small(<1000)
     - medium (1000-2000)
     - Large(2000-5000)
  

   ## Scores by school type
      - Charter
      - District









