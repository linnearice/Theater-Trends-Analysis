# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
![Excel Pivot Table - Parent Title Outcomes ALL Data](https://user-images.githubusercontent.com/35401581/129459871-8814602c-eacc-475a-b445-d83a6ddc1cfd.png)

# Kickstarting with Excel
## Overview of Project
Louise works in theater and produces plays and other theatricals.  It’s our mission to provide Louise enough data to support her goal of campaigning for and producing successful theatrical pursuits and plays.  Louise has provided us with an Excel dataset (Kickstarter) which we (analysts) can use to provide Louise meaningful insights, trends and visualizations of the data which will help Louise develop future successful campaigns.  For the current time, we are providing data or outcomes and visualizations of how different campaigns fared in relation to their launch dates and their funding goals, which were successful, and which were not. We must also provide Louise a written summery and access to the data findings to help her in future campaign decisions.
### Purpose
We'll be performing data analysis on several thousand crowdfunding projects to uncover any hidden trends to help Louise in decision making. Also, the purpose of the exercise is for us analysts to learn an array of data calculations, presentations and visualizations within Excel that can answer Louise’s questions.  We can also learn to expand on these tools to answer other questions (some simple and some complex) that may be useful for this project and others. 
## Analysis and Challenges
1.	Produce theater outcomes based on launch dates and provide pivot chart visual.  A pivot table is developed to show the numbers of successes, failures and cancelations for  theaters by month.  A line chart representing this data is provided.
  ![2021-08-15](https://user-images.githubusercontent.com/35401581/129507928-8aa165fe-f4ba-48a4-851f-7dda7e52fc87.png)

2.	Produce plays outcomes based on goals for plays and provide a line chart visual.  The data is calculated and presented in a tabular chart.   The chart provides 12 breakouts of goal ranges for example "<1000", "1000 to 4999", etc.  For each range a countifs function are used to calculate the number plays by successes, failures and cancelations.  Totals are summed and percentages are calculated for on each category.  The results are presented in a line chart. 
  ![2021-08-15 (2)](https://user-images.githubusercontent.com/35401581/129508972-78797548-5a37-4500-93cc-712174d987b3.png)

3.	Produce a written analysis of outcomes

### Analysis of Outcomes Based on Launch Date
The analysis showed the highest number of successful theatrical productions occurred in the May months and these successes significantly outnumbered the failures in this month.  The fewest successes were in December months and were roughly the same as the number of failures which indicates close to a 50/50 chance of success in this month.  Also October shows the highest number of failures with successes only having a slightly higher outcome.  Cancelations appear not to be impacted by month of launch.
### Analysis of Outcomes Based on Goals
The highest percentage of successes for plays is within the ranges a) less than $1000 and b) ranges $35000 to $39999 and $40000 to $45000.  The least probability for successes is $45000 or higher.  The highest numbers of failures are also within this $45000 or higher range and then the $25000 to $25,999 range.  There were no cancellations of plays.    
### Challenges and Difficulties
I forget to add plays as a filter within the countifs function.  I overlooked this and it took me a bit to realize what I had done wrong, but once I entered the right data if fell into place.  I also realized the countifs and other statements will provide data on “all” data even if filters are in place within the main kickstarter data.  You must either use a filter in the countifs function or you could filter the data in kickstarter and then copy the filtered results into another sheet and then use countifs on this data in the new sheet.  There are multiple ways to get to it and should use the most efficient.
## Results
***-	What are two conclusions you can draw about the Outcomes based on Launch Date?*** The best time to initiate a theatrical campaign is in May and the worst chances for success are in December most notably and October also shows a high potential for failures.  Cancelled productions seem to show no change month to month and must happen due to other factors.

***-	What can you conclude about the Outcomes based on Goals?*** Starting a campaign for plays with a goal of $45000 or greater is too risky.  A better bet are a) those less than $1000 and b) then those with a goal range of $35000 to $45000.  But why is there a dip in successes in the range $25000 to $30000?  We might pursue another data point to help answer this question.    

***-	What are some limitations of this dataset?*** The success or failure of a play could be based on many other factors like the subject matter likability factor, who the actors are, etc.  Analysis could get quite complex as you add more criteria and all of these criteria may not be easily measured.  Also cancelations of theatrical productions appear to happen based on other factors.  Perhaps this could be explored.

***-	What are some other possible tables and/or graphs that we could create?***  You can also filter out just US or other countries.  I might like to see a bar chart of successes, failures, etc. percent funded by country – where is best to produce a play?  Perhaps an analysis of successes is based on percent funded.  A line graph could be helpful here too.
