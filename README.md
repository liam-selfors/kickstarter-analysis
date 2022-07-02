# Kickstarting with Excel

## Overview of Project

The client, **Louise**, ran a campaign promoting her play, *Fever*. After the campaign came close to meeting its fundraising goal, Louise is interested in some additional analysis.

### Purpose

The purpose of this analysis is to determine how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### Pivot Table

A pivot table showing values of campaign counts was created filtered to include only campaigns with a *Parent Cateogry* of *"theater"* and also exclued all *live* campaigns. The columns sliced the data by outcome, showing three categories: *"successful"*, *"failed"* and *"canceled"*.

![Excel Pivot table for Outcomes Based on Launch Date analysis](/resources/Theater_Outcomes_vs_Launch_Pivot_Table.png)

#### Pivot Chart

The data in the pivot table described above was translated to a line graph. The graph shows three lines, each representing one of the three outcomes in the pivot table. The X-axis represents the month of the year, and the Y-axis represents the number of campaigns.

![Excel Pivot chart for Outcomes Based on Launch Date analysis](/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. Campaigns with successful outcomes were most frequently launched in May through July
2. The highest volume of successful campaigns was launched in May

- What can you conclude about the Outcomes based on Goals?

Smaller campaigns with goals less than $5,000 were most successful, and, in general, campaigns were less likely to be successful as their goal increases. However, campaigns with goals between $30,000 and $45,000 break this trend with 67% of campaigns succeeding.

- What are some limitations of this dataset?

The dataset does not include descriptive data on the size of each campaign such as the budget or size of target audience.

- What are some other possible tables and/or graphs that we could create?

The *Theater Outcomes Based on Launch Date* graph charts campaigns based on their launch date, but We may want to show the same visualization by deadline to see what time of year is most successful to show a play. We may also want to create additional tables/graphs showing success rates across other variables such as whether or not the Kickstarter campaign was a staff pick or spotlight campaign. Additional breakouts for tables and graphs that may provide meaninful insights are annual trends and duration of the campaign.
