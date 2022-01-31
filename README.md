# School District Analysis

## Overview of the school district analysis

For this analysis, I was asked by Maria to help her in analysing school district data. Basically, I had to extract meaningful information from the data that would help the school board in making informed decisions regarding funds allotment. The data contained information about 39,170 students and 15 schools. I used Pandas Library in Pyhton to perform my analysis and calculations. I generated school district summary, high and low performing schools, average math and reading scores by grade, grouped scores by school spending per student and by school size. Later, Maria was informed by the school board that for 9th grade students of THS (Tomsas High School) there is evidence which suggests academic dishonesty. Thus, I was asked to replace all math and reading score values for those particular students with NaNs. After doing that, I performed all the previously mentioned calculations again. And finally, I was aked to write a report on how these changes affected the overall analysis. 

## School District Analysis Results

- By looking at the disctict summary tables below, we can clearly see that Average Math Score and percentages decreased after removing Thomas High School ninth graders. The decrease was very little but still it was there. 

![image](https://user-images.githubusercontent.com/95254809/151729007-0236b9c9-8b6e-4bb9-b0b7-d15c5ad8a490.png)

![image](https://user-images.githubusercontent.com/95254809/151729101-230fda46-960d-4925-a5e3-556692109772.png)

- For the school summary tables, it can be seen that except for Average reading scores, all values decreased. Please see the images below. 

![image](https://user-images.githubusercontent.com/95254809/151730246-15d95bbb-cbd1-419f-a81c-a66d4d3a8007.png)

![image](https://user-images.githubusercontent.com/95254809/151730319-ec18015e-dc3d-47b9-8267-aa376694241b.png)

- From the images below, we can see that the postion of THS is number 2 in both cases. So relative to other schools, their performance did not change after removing ninth graders. 

![image](https://user-images.githubusercontent.com/95254809/151730474-f401a63a-1866-40b7-90f7-48b1f79b6088.png)

![image](https://user-images.githubusercontent.com/95254809/151730498-ed7f67ae-93e8-4888-b85a-479d47288bad.png)

- The only thing which changed for Math and reading scores by grade is that now there are NaN values for ninth graders of THS. 

![image](https://user-images.githubusercontent.com/95254809/151731025-0e204603-93e8-4676-a352-fc57dfe1090a.png)

![image](https://user-images.githubusercontent.com/95254809/151732036-52821ca5-5f3f-43d3-8263-a8d074830e32.png)

![image](https://user-images.githubusercontent.com/95254809/151732060-914b9809-4f93-4705-95be-120b580b569f.png)

![image](https://user-images.githubusercontent.com/95254809/151732072-88c0d139-75c9-4f31-b694-c330528f0a1f.png)

- For the spending ranges, only a very minute difference is seen and that too only when the columns are not formatted. After formatting the columns, I get the same values for both tables. This can be seen in the two images below:

![image](https://user-images.githubusercontent.com/95254809/151732640-f690a1bb-e814-4c87-a926-7b00ce961563.png)

![image](https://user-images.githubusercontent.com/95254809/151732666-1f8f799d-21b5-4dce-9175-247d8295896c.png)

- We see a similar result for scores by school size and school type as seen below:

![image](https://user-images.githubusercontent.com/95254809/151732735-66feab4a-549d-426e-9d6a-b1cb514b73b6.png)

![image](https://user-images.githubusercontent.com/95254809/151732747-19827c4e-a066-4223-9a9b-28b1ac63f387.png)

![image](https://user-images.githubusercontent.com/95254809/151732977-774b3959-0db1-4961-9f15-7428b6a9b5d5.png)

![image](https://user-images.githubusercontent.com/95254809/151733015-96c20714-6659-4e12-bc4b-ba32d9243c9b.png)

In order to differentiate between the two results, I added a 'new' to the names of tables which had ninth grade students from THS removed from them. 

## Summary

Following are the four changes which can be clearly seen from the analysis:

- For district_summary_df, Average Math Score, % Passing Math, % Passing Reading and % Overall Passing decreased a bit while Average Reading Score remained same
- For the school summary tables, Average Math Score, % Passing Math, % Passing Reading and % Overall Passing decreased while Average Reading Score increased a bit
- One  change which can be seen in math and reading scores by grade is that ninth grade values for THS have been replaces by NaNs.
- For the spending ranges, only a very minute difference is seen and that too only when the columns are not formatted. After formatting the columns, I get the same values for   both tables. 









