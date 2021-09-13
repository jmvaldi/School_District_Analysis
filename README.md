# School_District_Analysis
We are given school data and student data reports by the school board to analyze. Our job is to come up with a conclusion as to how the school board  should priorities their budget regarding school performance. 

Link to the challenge <https://github.com/jmvaldi/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb>
<br />
## Overview of the Analysis
The school board happpened to discover that there was academic dishonesty with regards to the reading and math grades for the ninth graders of Thomas High School. We were tasked with replacing the math and reading scores for Thomas High school with NaNs while at the same time as keeping the rest of the data in the dataset intact.
<br />
## Results
When going over the ninth grade data to replacing the reading and math scores, their was a total of 461 student records that were altered. Compared to the entire dataset it is not that much that is being altered to change the results significantly.
<img width="946" alt="School District Summary" src="https://user-images.githubusercontent.com/88690258/133007943-6ed26722-33c1-4675-829f-7edd1cabcbf4.png">
When going over the school summary for all 15 high schools there was minimal change to the other high schools overall. Now looking closely at the data for Thomas High school you can see a discrepancy in the data. 
This is the altered high school summary after the changes to the reading and math scores for Thomas High School:
<img width="992" alt="School Summary" src="https://user-images.githubusercontent.com/88690258/133008991-35ab1273-4c1f-4f89-88da-059aa2263548.png">
This is a snippet of the original school summary for Thomas High School before the discovery of academic dishonesty:<img width="1001" alt="Thomas High School Summary Original" src="https://user-images.githubusercontent.com/88690258/133009067-0b391489-f155-4f0a-9397-83fee616afa9.png">
You can see that there is minimal change in the "Average Math Score" and "Average Reading Score" but looking at the "% Passing Math" there is a difference of 26.4% passing. For the "% Passing Reading" there is a difference of 27.6% passing, clearly an indication that alludes academic dishonesty. 
Originally when going over the overall passing percentage of the top five schools, Thomas High School placed second due to the questionable passing math and reading percentages respectably. However when we went and replaced the values, Thomas High Schools position among the 15 schools changed. One thing to note is that the data being replaced did not change math and reading score by grade since the only grade being altered is the ninth grade data.
Average Math Score by school and grade: 

<img width="436" alt="Altered Average Math Scores by grade and school" src="https://user-images.githubusercontent.com/88690258/133010616-a3d3a940-ce4c-47aa-90b0-4cb91edbf504.png">
Average Reading Score by school and grade:

<img width="437" alt="Altered Average Reading Score  by grade and school" src="https://user-images.githubusercontent.com/88690258/133010916-20e8c51c-ecf5-47e7-a8d9-2cd2fcea30b5.png">

## Summary
When going over the School Spending summary there was no chnage done to the spending ranges for the average math and reading scores. what did get impacted was the spending ranges for all three passing percentage columns in the $630-675 range.
<img width="843" alt="School Spending Summary" src="https://user-images.githubusercontent.com/88690258/133011595-b21fe26b-5037-46b7-a810-6ef254d79fbf.png">
When going over the School Size summary and removing the ninth grade scores there was no change done to the average math score and the average reading score. Now the data did change in for the mediumm-sized schools. In the new data there was a decrese of 6% for the passing math percentage, a 6% decrease in the passing reading percentage, and a 6% decrease in the overall passing percentage. Thomas High School must belong to the mediumm size range.
<img width="776" alt="School Size Summary" src="https://user-images.githubusercontent.com/88690258/133013698-35d786a5-4553-4e97-8a9b-915dce53fde7.png">
Lastly when going over the School Type summary, there was a decrease in the charter school type. For the math and reading percentage there was a decrease on 4% respectively and a 3% decrease in the overall passing percentage. Even with the data change charter schools overall had better rate values compared to district schools. There seems to be more flexiblity and direct involvement as to how charter schools conduct their budget, curriculum, and regulations with their school board.  
<img width="746" alt="School Type Summary" src="https://user-images.githubusercontent.com/88690258/133013840-f715ebed-6818-4934-9d13-719615240dbd.png">
