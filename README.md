# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to identify trends. 

## Overview of Project
### Background
Louise, a playwrite, needs the help of an Excel Power-User to determine how the Kickstarter campaign for her play "Fever" compared to different campaigns of a similar type. Louise stated her funding goal was $10,000 and was almost met in a very short amount of time after launching the campaign.
### Purpose
Using Kickstarter data containing 4,114 observations of past fundraiser campaigns, a review of the data will help Louise determine how the various launch dates and funding goals relate to the success of a campaign. Given that Louise's fundraising campaign was for a play with a budget of $10,000, the analysis will focus on funraisers that have similar characteristics.

## Analysis and Challenges
With fundraising, the two main factors that influance the success of a campaign are the date or time period of lauching the campaign, and the overall funding goal the campaign is attempting to meet. In this analysis, these two factors are used to better understand the expected outcome of a fundraiser and in turn, we may be able to support why Louise's campaign was successful. 
### Analysis of Outcomes Based on Launch Date
The first factor is Launch Date. By looking at Kickstarter campaigns in the same category as Lousie's campaign (Theater), the number of campaigns in each outcome per month were obtained to create the graph below. As shown in the graph below, most successful campaigns begin in May, June, or July. However, by looking at the campaigns that failed to meet their goal, May, June, and July also happen to be some of the more likely months for failure as well. This indicates two things, the first being that a larger number of campaigns begin during these months, so there will be a larger number of both failures and successes, the second being that there may be other factors that influance the outcome of the campaign. 

![Theater_Outcomes_vs_Launch](https://github.com/rmchartman/kickstarter-analysis/blob/master/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The analysis of the second factor, Goal Amount, explains more about the influance of factors on a campaigns outcome. Although it can be seen that the Launch Date may paly an important part in the outcome, Goal Amount shows a more definitive difference between outcomes. The graph below was created by extracting the number number of plays within the specific numerical groupings of the Goal Amount that were categorized under each outcome, then turing those numbers into a percentage of the total for the Goal Amount grouping. In reviewing the data in this manner, we can determine what Goal Amount has the highest percent of success or failure. As seen on the graph below, the highest percent of success occurs when the Goal Amount is less than $1,000. On the other hand, the failure rate is highest when the Goal Amount is between $45,000-$49,999. However, if we were simply lookign to see where there was a higher percentage of success over failure, it would be when the Goal Amount is less than $15,000, or between $35,000-$44,999. Using this data, we could have predicted that Louise's campaign would be successful because there was a higher percentage of success at a $10,000 Goal Amount.

![Outcomes_vs_Goals](https://github.com/rmchartman/kickstarter-analysis/blob/master/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
There were no particlar difficulties or challenges encountered during this analysis, however I think that this analysis could be taken to another level to determine clear predictive factors for success. Based on the analysis completed, it is clear that there are a combination of factors used to determine whether a campaign with specific variables will be successful. The results are not as clear with only evaluating Launch Date and Goal Amount, and it out be more informative to Louise if other factors were also evaluated for thier impact on the outcome of a campaign.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
For campaigns in the Theater category, the best month to begin a campaign would be May, and the worst month to begin would be October, based solely on the ratio between successes to failures.

- What can you conclude about the Outcomes based on Goals?
There is a higher rate of success over failure when the Goal Amount is less than $15,000, or between $35,000-$44,999.

- What are some limitations of this dataset?
A larger sample size would be more helpful to determine with greater accuracy, as well as data on how the campaigns were advertised to determine if that impacted the outcome.

- What are some other possible tables and/or graphs that we could create?
Instead of looking only at the number of successes or failures in a month, it would be better to transform them into a percentage of the total for the month so that the number are normalized to the fluctuation in the number of campaigns in each month. I could show this by either doing a line graph of the percentages, or by doing a 100% stacked bargraph using the data as is. 
