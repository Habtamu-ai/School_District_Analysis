

# School_District_Analysis
This project analyzes student funds and student standardized test scores. The project uses the anaconda software packages and python programing language as a tool for the analysis.
# Overview of the school district analysis
The main purpose of this project is to look into if the student score alterd by the school. And if it is to know the full extent of it. Thomas High School is the one we going to look into, based on the recommendation by the school board. This analysis is going to replace the Thomas High School ninth-grade reading and math score and run the analysis and see if there is any change.

# Result
First, we removed grade 9th math and reading scores from Thomas High School. The two images below show the school data before and after replacing ninth-grade math and reading scores of Thomas High School.

###  Overview of the School data
![School_data](https://user-images.githubusercontent.com/78656720/111785675-48548200-8893-11eb-92a6-8aebb2339f4d.png)
###  School data after Thomas High School grade 9th score is Replaced
![Thomas_Grade_9th_removed](https://user-images.githubusercontent.com/78656720/111785702-50acbd00-8893-11eb-9155-3f570d1d5234.png)

## Second, we create the following metrics;
   #### The district summary
   #### The school summary
   #### The top 5 and bottom 5 performing schools, based on the overall passing rate
   #### The average math score for each grade level from each school
   #### The average reading score for each grade level from each school
   #### The scores by school spending per student, by school size, and by school type 
   
   
   #### The district summary
Looking at the two tables below the district summary before and the district summary after we replaced the grade 9th Thomas High school, there is a change in the math, reading, and overall percentage passing rate though it is minimal.
   ##### New District Summary
![New_District_Summary](https://user-images.githubusercontent.com/78656720/111794066-3d521f80-889c-11eb-923d-fe72270d94bc.png)


   ##### District Summary
![District Summary](https://user-images.githubusercontent.com/78656720/111794795-f87ab880-889c-11eb-9874-73e36c11d8ab.png)

 #### The school summary
Based on the recommendation of the school board we have looked closely at each school's summary and we find the following in Thomas High School. Looking at figures five and six, the *overall passing percentage* dropped from 90.4 to 65 percent, *reading* from 97 to 69, and *math* from 93 to 67. But this might be misleading because we only remove the score but we kept the student number in the data which might affect the overall passing and the school budget.
 
   ##### District Summary after removing math and reading score of Thomas High School
 ![New_per school summary](https://user-images.githubusercontent.com/78656720/111797352-78a21d80-889f-11eb-8ec3-f903c554707f.png)
  
  ##### District Summary 
 ![perschool_summary_latest](https://user-images.githubusercontent.com/78656720/111802940-ef8de500-88a4-11eb-83a7-ac6639b88003.png)
  
  #####  District Summary after without grade 9th students 
 ![PER_School Summary_Thomas](https://user-images.githubusercontent.com/78656720/111797278-632cf380-889f-11eb-8180-924a2817feae.png)

We also analyze the top  and bottom five schools based on their school performance.
and presented the tabel below.
#### The top 5 and bottom 5 performing schools, based on the overall passing rate
![Top Terforming School](https://user-images.githubusercontent.com/78656720/111829318-e9a6fc80-88c2-11eb-8e19-7e7b0d92e0b0.jpeg)

![Low Performing Schools](https://user-images.githubusercontent.com/78656720/111829708-6df97f80-88c3-11eb-8154-a0da6a09c627.png)

To figure out what contributes to the school's high or low performance we also run the analysis based on the school budget and school size.
Looking at the table below, we cannot conclude the higher-performing school has more budget than the low-performing school. Diving deep, we also run the analysis by school size based on the number of students. We find the small size schools (student numbers less than 1000) score the overall passing 90 percent. While the overall passing percentage of large schools (students number, between 2000 and 5000) is 58.  By diving deeper we have also looked at the school performance based on the type of school. The image below shows Charter schools' overall passing percentage is 87. While district schools' overall passing percentage is 54.

![Score by Spending](https://user-images.githubusercontent.com/78656720/111833761-01817f00-88c9-11eb-8c35-0227b4401d5e.png)
![Scores by Size](https://user-images.githubusercontent.com/78656720/111833777-06dec980-88c9-11eb-895f-553dbbad8bca.png)
![Scores By School Type](https://user-images.githubusercontent.com/78656720/111833785-09d9ba00-88c9-11eb-840a-6a2e58181031.png)

# Summary

Summarizing our analysis we have noticed four main developments from the previous analysis. By looking at the images below we can say score by grade and by budget hasn't been affected by the new analysis. while Score by school type and school size change.

## Math and reading scores by grade
  ######  Schhol grade new                                                                                                           
![Math Average score by school](https://user-images.githubusercontent.com/78656720/111838397-adc66400-88cf-11eb-9908-2e85561b4022.png)  
 ###### School grade old
![Old_Math](https://user-images.githubusercontent.com/78656720/111838492-c8004200-88cf-11eb-82c8-04f34a98bcc4.png)

![Reading average score by grade and school](https://user-images.githubusercontent.com/78656720/111838432-b9198f80-88cf-11eb-8989-d50b0930cb40.png)


![Old_Reading](https://user-images.githubusercontent.com/78656720/111838507-ccc4f600-88cf-11eb-9441-fb7ef8916916.png)



   # Scores by school spending
   # New
   ![Score by Spending](https://user-images.githubusercontent.com/78656720/111838556-e23a2000-88cf-11eb-9da8-c65677b3f77c.png)
   
   # Old
   ![Old_by spending](https://user-images.githubusercontent.com/78656720/111838568-e5cda700-88cf-11eb-8849-1fc3f0b7ca4a.png)

  
    
  ## Scores by school size
   ![Scores by Size](https://user-images.githubusercontent.com/78656720/111838618-f67e1d00-88cf-11eb-8b28-b02829db8105.png) 
   ![old_by size](https://user-images.githubusercontent.com/78656720/111838635-faaa3a80-88cf-11eb-9b60-529a55414dc0.png)
       

   ## Scores by school type
   
   ![Scores By School Type](https://user-images.githubusercontent.com/78656720/111838731-1f061700-88d0-11eb-93b6-4fa35ce1fde4.png)
      
   ![old_by type of school](https://user-images.githubusercontent.com/78656720/111838770-2fb68d00-88d0-11eb-8172-20078087c52c.png)










