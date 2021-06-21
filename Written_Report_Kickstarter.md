# Kickstarting with Excel 
**Fever's Fundrasing**
## Overview of Project
After working with Louise, she nearly has met her fundraising goal for her play Fever quickly. As she gets ready to open, she needs to evaluate how successful different campaigns were by funding and when they opened. This can also be analized through visuals and comparing how much money was raised for failed, successful and canceled campaigns. We will be able to conclude how much further money needs to be raised and when to open so Fever is the most successful. 

## Analysis and Challenges
To begin this challenge I needed to focus on when the campaigns were opened. Although the numbers in j and k were converted to dates we needed to just analyse the year to map trends. I pulled the year in Excel using **=year(R2)**. However it didn't give us the full picture. 

###### Visuals
Now that the years were seperated I wanted to use a pivot table to within each year which type of sub category succeeeded, failed and were canceled. Now as were are dealing with a play, we would want to filer our data for theatre we can identify which month was the most successful and which month failed. I also looked to see if any months had large amounts of canceled plans. Although the chart is helped to define the data, we need to se the trend lines. 

### Analysis of Outcomes Based on Launch Date
We this data we needed to extract the data from the pivot table and when put into a line chart you can see that the successful campaings opened in May. While, the failed campigns opened in October. 
### Analysis of Outcomes Based on Goals
Moving further into the data we wanted to look at the goal amount and see the number of campigns succeeded, failed or was canceled for each bracket of 
-Less than 1000
-1000 to 4999
-5000 to 9999
-10000 to 14999
-15000 to 19999
-20000 to 24999
-30000 to 34999
-40000 to 44999
-45000 to 49999
-Greater than 50000
For the number successful I used the count if formula and just updated the dates. I repeated the same formula for the other two coulmns and just replaced the comments to failed and canceled.  **=COUNTIFS(Kickstarter!$E:$E, "<1000", Kickstarter!$G:$G, "successful", Kickstarter!$P:$P, "plays")** 
Then I used the auto sum feature  to add up columns B:D. Then to caculate percentages I took **=B3/$B$15** I repeated this for columns C and D. 
From the data I uncovered that campaigns that the successful ones had a 50% chance of suceeeding, but also a 50% change of failing. 
### Challenges and Difficulties Encountered
The challenges were the line chart for the Outcomes based on Goals. I struggeled with the formatting. I would like to further analyize this with a bar chart. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
I can conclude that she should lauch at May 
She should also have a positive outcomes with 111% fund backing. 
- What can you conclude about the Outcomes based on Goals?
I can comclude that they goals need to be over 50,000
- What are some limitations of this dataset?
The number of kickstarters and the lenth of time. 
- What are some other possible tables and/or graphs that we could create?
I would create a box plot or scatter plot. 