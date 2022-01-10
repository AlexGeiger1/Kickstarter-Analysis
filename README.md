Alexander Geiger      
Kickstarter Challenge
1/9/22

# Analysis of Theatre-Related Kickstarter Performance


## Overview of Project

The purpose of this project was to analyze theatre fundraising data from prior years in order to determine how various campaigns performed in relation to their funding goals and launch months.  The goals and timing data may be useful for recommending future Kickstarter efforts.

## Analysis and Challenges

### Theatre Analysis - Outcomes by Month Launched.
Using the Kickstarter data for all years provided, the first analysis centered on the parent category ‘Theatre’ and compared ‘successful’, ‘failed’ and ‘canceled’ outcomes by month launched. The pivot table below was created to reflect the summarized data by these outcomes, filtered for Theatre.  Next a chart was created from this table in order to visualize results by outcome and month, which showed May was the highest successful month followed by June.  The line chart can be viewed in the Results section below.


![Pivot Table](https://github.com/AlexGeiger1/Kickstarter-Analysis/blob/main/Resources/pivot%20table.png)


### Play Analysis – Percentages by Goal Amount.
For the next analysis, the percent of ‘successful’, ‘failed’, and ‘canceled’ plays, a subcategory of theatre, were compared by the funding goal amount, which were combined to create ranges as can be seen in column A below.  The numbers in these ranges were created using EXCEL’s COUNTIFS() function and then converted to percentages.  These percentages were graphed to show result visually by goal ranges, which can be found in the Results section below.

![Goal Ranges](https://github.com/AlexGeiger1/Kickstarter-Analysis/blob/main/Resources/table%20goal%20ranges.png)


### Challenges
In analyzing theater outcomes by launch date, creating the pivot table was a challenge to obtain the correct selection criteria and display the months from the dates.   I overcame the challenge through trial and error while referring to my notes and figured how to display months instead of years or dates.
When analyzing outcomes based on goals, challenges arose in creating the formulas. First copying formulas more quickly required learning how to anchor the fields so they did not change when copying to the next cells.  I googled this and found that F4 added the needed ‘$’s for quicker copying.  Also, I needed to be more detail-oriented and pay attention to the formulas as well as checking my work carefully. As can be seen in the formula bar below, the ranges needed could get very complicated and I found I had missed some necessary parts the first time through.


![Formula Bar](https://github.com/AlexGeiger1/Kickstarter-Analysis/blob/main/Resources/countifs%20formula%20bar.png)


## Results
Theatre fundraising outcomes of ‘successful’, ‘failed’, and ‘canceled’  by month can be seen in the line graph below.  May was the most successful month followed by a fairly steady decline for the rest of the year.  December was the least successful month; almost all December Kickstarters failed.   Overall,  canceled Kickstarters remained relatively low and constant throughout the year and failed Kickstarters were also mostly flat with lower numbers than successful theatre campaigns.   
The results indicate that new theatre campaigns would likely be best to start in May and least likely to succeed in December.


![Theatre Outcomes Graph](https://github.com/AlexGeiger1/Kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)


The results of the analysis of outcomes based on goals are represented visually in the graph below.  Based on the line graph, one can see that for a goal of less than $5000, there was around a 50% better chance of being successful than of failing. Generally, between  goal ranges of $15,000 through $34,999, the percentage of failed campaigns were above the successful ones and at $45,000 to $49,999, the success rate dropped completely to zero where all Kickstarters failed.
Based on these results, having a campaign fund goal of less than $5000 or between $25,000 and $35,000 would be reasonable targets for a successful campaign.


![Outcomes Goals](https://github.com/AlexGeiger1/Kickstarter-Analysis/blob/main/Resources/Outcomes_vs_Goals.png)


## Limitations and Recommendations

### Limitations
A limitation is that the data lacks the authors/creators/directors’ names that may influence the backers. For example, a famous celebrity actor would draw more funds more quickly than a ‘no-name’ of another category.  Another limitation may be the economic situation of the country where the kickstarters were launched. If the economy changes, or a pandemic hits, previous data may not be a good predictor.

### Recommendations
Additional tables and charts might be helpful before deciding the details of the next campaign.  For one, looking at the category by year instead of consolidating years may be useful to see if some kickstarter categories could have been more popular in the past but are no longer trending. 
Another helpful analysis would be to check the percent successful by subcategory within the parent category of theatre.  It may be helpful o know if one or more subcategories contributed to the success rate in May.
