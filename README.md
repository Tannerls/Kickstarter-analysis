> # An Analysis of Kickstarter Campaigns with Excel
> 
## Overview of Project
An analysis was performed on Kickstarter data to uncover trends related to theaters launch date over the years as well as outcomes for plays based on Goals . The information presented was on all Kickstarter campaigns for a variety of different entertainment opportunity's. In this document, I will present my analysis of the data, the challenges I encountered, as well as the results. 
### Purpose
The purpose of this analysis was to determine the outcomes of Theater Kickstarters based on launch date as well as their outcome based on its goal. Then to present the results in order to suggest the best time and goal range for launching. 
## Analysis and Challenges
The dates launched was used in order to determine successfulness over time during a specific month. In the analysis of the Kickstarter Campaigns, dates had to be converted in order to be readable.  Also the category and subcategory needed to be separated to just find the outcomes for plays based on their goals and how successful they where. 
### Analysis of Outcomes Based on Launch Date
When looking at the result for Outcomes Based on Launch Date. There is a small increase in success during the month of February but falls back down come March. While can see a large increase in how successful the theater campaign was from March through May, with a steep climb from April to May. After May there is a steady decline in theater success with a small spike in failed campaigns in October. Canceled theater campaigns remains fairly steady with very low numbers and no canceled campaigns in October.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/83738699/122655157-00edc400-d116-11eb-942d-750bb09fa269.png)
### Analysis of Outcomes Based on Goals
When looking at Plays and how successful they are compared to their goal funding. The highest success rate are with Plays that have a goal less than $5000, similarly the failure rate for under $5000 is also the lowest. As the goal for the plays increases, failure also increases almost mirroring each other. Where goals with a rage between $25,000 and $45,000 have a steady success rate and covers a wider range on funding goals. This would be a target area in order to increase ROI in the campaign and success rate. 

![Outcomes_Based_On_goals](https://user-images.githubusercontent.com/83738699/123502255-973b5180-d610-11eb-8100-b2e02d1e70e0.png)
### Challenges and Difficulties Encountered
Some challenges I ran in to was getting the PivotTable to show months rather than the number associated with the month. I also ran in to difficulties when using the =COUNTIFS() formula to calculate the number of Successful, Failed, Canceled, and live plays. The use of the Greater than > and less than < had me turned around for a bit, until I realized my mistake and corrected it. I did have to double check that there was in fact no canceled plays because that seemed odd to have none at all. 
# Recommendations
Based on the research, you should focus more on Theater campaigns from March through May and expect successful campaigns to start to decrease through out the rest of the year. There is a small increase in success in October which can probably be attributed to Halloween and fall festivals which can be an area of opportunity if you set your funding goals less than $5000 in order to gain the most success. For your more successful period of March through May your funding goals should lie less than $5000 and/or between $25,000 and $45,000. Based on the information in both charts this would be the target area for plays, having a smaller smaller margin for failure. 
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?

	--One conclusion I can come to is that the months such as February and October that have big holidays with festivals and date nights seem to be the outliners, while the hotter months have the biggest success rate. 
	--Another conclusion is that there is a big correlation to funding goal and its success. It would be interesting to dig deeper and figure out what types of plays have a funding goal between $5000 and $25,000 to determine if its the type of play or just the funding goal itself.
  
- What can you conclude about the Outcomes based on Goals?

  --That the funding Goal is directly correlated to its outcome. You are able to clearly see that there are certain ranges that success seems to be higher but going over $45,000 causes almost complete failure.
- What are some limitations of this dataset?
--The data was presented in a way that required extra work to clean it up and make it usable. Beyond that you are limited to what can be analyzed and extracted. By having a column for genre for the plays, the analysis could provide a better look in to what causes failure and at what time of year based on the genre of the play.  

- What are some other possible tables and/or graphs that we could create?
--You could a Radar chart or Combo Clustered Column- Line chart although they would be a little more difficult to determine true outcomes from. 
 
Written with [StackEdit](https://stackedit.io/).
