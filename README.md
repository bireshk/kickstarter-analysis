# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this project is to visualize campaign outcomes based on their launch date and corresponding funding goals.


## Analysis and Challenges

In order to analyze the campaign outcomes, we looked at month wise count of successful/failed/canceled campaigns
and plotted the line graph to showcase the data distribution. The graph clearly depicts
the time frame when more successful campaign happened and when not.

We also created percentage outcomes (successful/failed/canceled) and plotted a line chart based on different 
goal ranges. This chart demonstrates percentage variations of outcomes in different ranges of goal.

The real challenge of this analysis was to count the outcomes based on the goal ranges. The corresponding IF
statement was tricky and took most of the time of this analysis. In order to check whether the logic is working correctly it was cross checked with the actual Kickstarter sheet filtering the corresponding columns and thereby count (e.g., outcomes = successful and then subcategory = plays and then goal value less than 1000)  


### Analysis of Outcomes Based on Launch Date

The below graph depicts most successful campaign occurs during the month of May through July for Theater and December month is probably not a good time for any campaign

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/62515666/122686729-5c808600-d1d8-11eb-9218-ba75bee672f1.png)

### Analysis of Outcomes Based on Goals

Percentage of successful campaign happened more when goal range is set below $4,999. Above the range of $50,000 chnaces of campaign failure is more obvious

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/62515666/122686739-65715780-d1d8-11eb-9256-41bee27065b7.png)

### Challenges and Difficulties Encountered

The real challenge of this analysis was to count the outcomes based on the goal ranges. The corresponding IF
statement was tricky and took most of the time of this analysis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. Most successful campaign occurs during the month of May through July for Theater. This could be because of summer vacation time
2. December month is not a good time for any campaign. This could be because of the holiday period

- What can you conclude about the Outcomes based on Goals?

1. Percentage of successful campaign happened more when goal range is below $4,999 and above the range of $50,000 chnaces of campaign failure is more obvious

- What are some limitations of this dataset?
1. Since this is an excel file the maximum data limitation is 1,048,576 rows by 16,384 columns
2. This dataset does not have any countries GDP information - this information could have provided the economic health of the country and therefore whether goal was set realistically or not

- What are some other possible tables and/or graphs that we could create?

1. A graph Goal vs pledged could have been provided a picture of how realistic the goal was set 
2. A graph based on country vs goal could provide a visualization of realistic projection of goal based on countries economic condition
