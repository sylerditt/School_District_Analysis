# School_District_Analysis

## Overview of the School District Analysis
The purpose of this analysis was to prepare standardized test data and find patterns in the data. We wanted to be able to disperse funding based on test scores. There was evidence of academic dishonesty so we had to redo the analysis after replacing math and reading scores affected by the dishonesty. We grouped scores by subject, school spending, size, and type in order to perform the analysis. 

## Results
*The district summary changed based on passing scores when we adjusted for academic dishonesty. Math scores, reading scores, and therefore overall passing scores went down. The budget was not affected. 
**Original district summary
![image](https://user-images.githubusercontent.com/85717241/147838118-6575f078-0f7c-4ca6-b50b-b8771883cc46.png)
**New district summary
![image](https://user-images.githubusercontent.com/85717241/147838004-4cb2d4a6-5494-44fa-ac8a-7abb3d752cdc.png)

*The school summary changed because Thomas High School was removed from the top 5 after we adjusted scores. All other factors remained the same. 
**Original top 5 schools
![image](https://user-images.githubusercontent.com/85717241/147838361-a8761a2c-890d-4320-adf4-429f7dfd7b68.png)
**New top 5 schools
![image](https://user-images.githubusercontent.com/85717241/147838346-ffbfa102-ce46-4b05-abd7-de396846baa6.png)

*No changes seen in scores by spending.
**Original and new scores by spending
![image](https://user-images.githubusercontent.com/85717241/147838606-b27997ae-3c00-48d8-924c-6b8a970658ba.png)

*No changes seen in scores by size. 
**Original and new scores by school size
![image](https://user-images.githubusercontent.com/85717241/147838745-f888a2b9-cef4-4477-80b1-1257f52ee253.png)

*Differences seen in overall passing score when analyzing schools based on type. Overall passing score has lowered by 3% for charter schools. 
**Original scores by school type
![image](https://user-images.githubusercontent.com/85717241/147838936-b0eb596b-3c74-4ca3-83b6-2754a8fff5bb.png)
**New scores by school type
![image](https://user-images.githubusercontent.com/85717241/147838889-8fc95791-490f-41f8-897d-58d458971a2c.png)

## Summary
After adjusting for academic dishonesty and replacing scores with NaNs, Thomas High School was removed from the top 5 performing schools based on scores. Since Thomas High School is a charter school, this affected the scores by school type, lowering the percent overall passing score for charter schools. This did not affect scores by school size or spending. This practice is useful for changing specific parts of datasets without dramatically altering other aspects of the dataframe. 
