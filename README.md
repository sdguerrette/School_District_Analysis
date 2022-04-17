# School District Analysis Challenge
## Project overview
After our initial analysis of school performance for the District, we were informed by the School Board that they suspected academic dishonesty had occured at a Thomas High School at the 9th grade level. We were instructed to remove the dishonest scores from the data set and re-run our analysis. The following is a look into how the changes to the data set impacted the reults of Thomas High School and the Distrcit as a whole.  
## Results
* ### District Summary 
  - Removing the Dishonest scores had a small but measurable impact on the overall district summary. As seen in the tables below, the removal of 461 scores from the total dataset caused a drop of .2 or less across the measured statistics.
  - #### Original Data Set
  ![Screen Shot 2022-04-16 at 9 00 28 PM](https://user-images.githubusercontent.com/100643755/163699791-abc9edff-5056-4ffb-9174-7252163ae886.png)

  - #### Adjusted Data Set
  ![Screen Shot 2022-04-16 at 9 01 12 PM](https://user-images.githubusercontent.com/100643755/163699807-70140c30-4de4-4b4a-997d-7534d27d0f22.png)


  
* ### School Summary
  - Since all of the removed scores came from the single school, the school summary was largely unchaged. The only alterations are present on the line representing Thomas High School, as shown in the following images. 
  - #### Original Data Set
  ![Screen Shot 2022-04-16 at 8 06 03 PM](https://user-images.githubusercontent.com/100643755/163698496-b59677b2-fce8-41b5-86f3-f99ac8247d5c.png)
  - #### Adjusted Data Set
  ![Screen Shot 2022-04-16 at 8 02 28 PM](https://user-images.githubusercontent.com/100643755/163698434-ffc0b779-0f36-41af-ac71-1185977a45f4.png)

* ### Thomas High School Performance
  - While the removal of the dishonest scores was enough to drop the "% Passing Overall" at Thomas High School by around a third of a percent, it did not have any affect on the school's ranking relative to the rest of the district. Thomas High School remained the second highest performing school after the data was adjusted and sorted by top performing schools.
  - Original Data Set
  ![Screen Shot 2022-04-16 at 8 16 29 PM](https://user-images.githubusercontent.com/100643755/163698710-3498751a-5b95-4a04-8150-d80fad01e86a.png) 
  - Adjusted Data Set 
  ![Screen Shot 2022-04-16 at 8 18 04 PM](https://user-images.githubusercontent.com/100643755/163698738-a67816ca-bff8-4c17-89e7-ab75c166630a.png)
* ### Math and Reading Scores by Grade
  - The only change to the reading and math scores when viewed by grade is the complete removal of all scores for Thomas High School's 9th grade. 
  
* ### Scores by School Spending
  - The adjusted data set for performance based on school spending per studend showed no significant change comapared to the original.
  - Original Data Set
  ![Screen Shot 2022-04-16 at 8 41 36 PM](https://user-images.githubusercontent.com/100643755/163699342-393f3c89-7079-4455-bd85-7afd240f1f1b.png)
  - Adjusted Data Set
  ![Screen Shot 2022-04-16 at 8 42 06 PM](https://user-images.githubusercontent.com/100643755/163699353-01640966-0aa7-43b3-b5d5-e243fc5e479f.png) 
* ### Scores by School Size
  - The adjusted data set for performance based on school size no significant change comapared to the original.
  - Original Data Set
  ![Screen Shot 2022-04-16 at 8 45 37 PM](https://user-images.githubusercontent.com/100643755/163699443-7e207ac5-9353-4f78-a31a-256be99e5746.png)
  - Adjusted Data Set
  ![Screen Shot 2022-04-16 at 8 44 44 PM](https://user-images.githubusercontent.com/100643755/163699415-f75231c4-22f7-457e-b95c-d7b665502fc5.png)
* ### Scores by School Type
  - The adjusted data set for performance based on school type no significant change comapared to the original.
  - Original Data Set
  ![Screen Shot 2022-04-16 at 8 50 52 PM](https://user-images.githubusercontent.com/100643755/163699575-c15c9990-93c9-4f5e-88fb-c6c79c19eaad.png)
  - Adjusted Data Set
![Screen Shot 2022-04-16 at 8 50 30 PM](https://user-images.githubusercontent.com/100643755/163699565-845c5285-6ce8-44f4-8567-3130650ecb38.png) 

## Summary
In summary, the removal of the dishonest scores from the data set produced slight but measurable changes in the following derived statistics:
  1. The average math score for the district fell from **79.0** to **78.9**
  2. The percentage of students passing math fell from **75.0%** to **74.8%**
  3. The percentage of students passing reading fell from **85.8%** to **85.7%**
  4. The percentage of students passing overall (both reading **and** math) fell from **65.2%** to **64.9%**
