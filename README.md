# Kickstarter with Excel

## Overview of Project

This project attempts to determine a relationhsip between campaign launch dates and goal amounts within the "plays" subcategory of Kickstarter campaigns. 

### Purpose

The purpose of this project is to provide an analysis on how different kickstarter theatre campaigns fared in relation to their launch dates and their funding goals. 

## Analysis and Challenges

The analysis for this project was divided into two main deliverables: theatre outcomes based on launch date and play outcomes based on goals. 

### Analysis of Outcomes Based on Launch Date

A pivot table was created to filter the number of successful, failed, and canceled theatre campaigns. The information summarized on the table was then used to visualize the relationship between threate outcomes and launch month in a line chart.

![Theater_Outcomes_vs_Launch](path/to/Theater_Outcomes_vs_Launch.png).

### Analysis of Outcomes Based on Goals

A summary report was generated to organize play outcomes based on campaign goals. The projects were grouped based on their campaign goal amount using the following ranges: Less Than 1000, 1000 to 4999, 5000 to 9999, 10000 to 14999, 15000 to 19999, 20000 to 24999, 25000 to 29999, 30000 to 34999 35000 to 39999, 40000 to 44999, 45000 to 49999 and greater than or equal to 50000 and their outcome in terms of Successful,  Failed, or Canceled. The percentage of successful, failed, and canceled projects for each goal range were then calculated. A line chart was created to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis.

![Outcomes_vs_Goals](path/to/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

A challenge I encountered was applying the COUNTIFS() functions to every column as the goal range had to be manually changed for each cell. 

## Results

Based on these analysis we can conclude the following: 

  From the Theatre Outcomes by Launch date, we can see the highest successful theater Kickstarters campaigns were in May and     lowest in December.
  The graph does not show significant trends on failure and canceled theater Kickstarter campaigns through out the year.
  
  From the Outcomes based on Goals, the goal of less than $1000, had the most successful play campaigns, almost 3 times more 
  that of failed campaigns, in contrast to higher goal amounts. Therefore, one can conclude most successful campais are under   $5000 as they averaged a 74% success rate.  For instance, when the goal amount was greater than $500000, it accounted for     the highest percentage of failed play campaigns. This could entail there is a negative correlation between success of a       campaign and amount of money requested. 

One limitation of the data is the lack of metrics to describe the success of theatres and/or plays during the full covered time period of the campaign. This would help show relevant time periods during the campaign where an industry/subcategory is most successful. In turn, we could use this to account for external factors.

It would be helpful to show location of theatre campgains to determine if there is a relationship between the country where it was launched and campaign performance. Also, displays showing the averge time organizations had to complete the campaigns for the most successful to the canceled as perhaps having more time would lead to greater rates of success. 
