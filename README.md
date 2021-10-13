# An Analysis of Kickstarter Campaigns 
## Overview of the Project
An upcoming playwright Louise is interested in beginning a crowdfunding campaign to fund her upcoming play Fever. The project analyzes data from other crowdfunding campaigns to come up with trends that can help her make decisions about her own campaign.  

### Purpose
The purpose of the project is to determine various factors associated with crowdfunding that have made similar projects successful in the past. 
The project uses Excel to organize, sort and analyze the data which will be presented to the playwright Louise, to enable her to make decisions on how to best execute her campaign.

![Picture2](https://user-images.githubusercontent.com/90416094/137037676-bb13ad0e-ddb6-498b-885e-de9ebaa8b448.png)

This chart for example shows that ‘Theater’ Kickstarter campaigns had the most successful campaigns in all categories in the United States.

## Analysis and Challenges
The dataset used for analysis was huge and had different types of data including:
1. Text
2. Numerals
3. Currency
4. Dates

To ensure the final analysis was accurate, data had to be assessed to ensure it was classified correctly. 
Examples
*While assessing the Data before analysis, it was discovered that launch dates were set in Unix timestamps and needed to be converted. Using the dates as they were presented   originally would have led to errors in the analysis 
*Some formulas used resulted in errors.When calculating the average donations by backers, productions that  did not have backers returned an error because numbers cannot be divided by zero. Debugging errors on an ongoing basis is therefore crucial while working with data
different types of data including:

### Analysis of Outcomes Based on Launch Date

The line chart below shows the analysis of Kickstarter campaigns based on launch date.

![Theater_Outcomes-vs-Launch png](https://user-images.githubusercontent.com/90416094/137051298-30677b1a-c89d-4659-b5e6-b5400eeee429.png)


The analyzed data indicates the following:

The launch date and the length of a campaign is crucial for success. 
Successful Campaigns were launched  between the months of April and August, with the most successful ones in the months of May and June.
Campaigns at the beginning and the end of the year did not meet their goals.
 
### Analysis of Outcomes Based on Goals

The line chart below shows the analysis of Kickstarter analysis campaigns based on goals

![Outcomes_vs-Goals](https://user-images.githubusercontent.com/90416094/137052401-2c643195-3146-49c2-8f04-280d7d44bc6b.png)

The Analyzed data indicated the following
1. The highest percentage of successful campaigns had a goal of less than $ 1000.
2. The highest percentage of failed campaigns are those that had a budget of over $ 45,000.



### Challenges and Difficulties Encountered




## Results

### Conclusions drawn on outcomes based on Launch Date
1.Louise play is most likely to succeed if it is launched between the months of May and June
2.Theater is the most popular campaign in Kickstater 


### Conclusion drawn on outcomes based on Goals
1.With a budget of 10,000 dollars, Louise’s play has a 55% chance of reaching its goals and 45% chance of not reaching her campaign goals
2.Analyzed data indicates that the higher the campaign goals the lower the success of the camapign meeting its goals.
3. The most successful campaigns had a goal of less than $ 1000 


### Limitations of this dataset?
1. There  are other ways other than Kickstarter campaigns for Louise to raise money to produce her play. Without taking into consideration other crowfundings, conclusion drawn  may not necessarily be the best
2. Without establishing the popularity of Kickstater, it is possble that there are backers who may not be aware of kickstarter for crowdfunding.
3. To get a more current picture on crowfunding, more recent data should be used. The data set used in this case is based on campaigns run between 2010 and 2017. 


### Other possible tables and/or graphs that we could create
1. For futher analysis, we could add country as a filetr for both outcomes based on launch date, and goals to get a clear understanding of sucsess based on location
2. A box and whiskers chart can also help us identify outliers that might be skewing the data in one direction or another.
