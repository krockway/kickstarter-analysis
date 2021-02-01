# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to help Louise determine the most successful criteria to launch a Kickstarter campaign for her play _Fever_. This criteria includes the best launch months for theaters and identifies which fundraising goals are most successful for plays.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Campaign launch dates for theaters were charted by month based on their success, failure or cancellation. Live data was filtered out to only show finished campaigns.
kickstarter-analysis/Theater_Outcomes_vs_Launch.png
### Analysis of Outcomes Based on Goals
Campaign fundraising goals were grouped into 12 categories, I then calculated the percent success, fail and cancellation rates for each of these fundraising groups using the COUNTIFS formula.
The most successful campaigns set a goal for less than $1000; the least successful campaigns set a goal for more than $45,000.
https://github.com/krockway/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png
### Challenges and Difficulties Encountered
Initially I filtered the raw data to count the outcome based on the goals. I realized that once this data was unfiltered, it would impact the Outcomes Based on Goals tab. I then updated the COUNTIF formula to include a criteria for "plays" to eliminate this issue.
## Results

**- What are two conclusions you can draw about the Outcomes based on Launch Date?**

Campaigns are most likely to succeed when launched in May or June. Campaigns are least likely to succeed when launched in late fall (October-December). Campaigns are most likely to be cancelled in January.

**- What can you conclude about the Outcomes based on Goals?**

Campaign goals of $15,000 or more fail 50% of the time. Campaign goals of $20,000 or less succeed 50% of the time. No matter the goal, none of the campaigns were cancelled. The best chance of a successful campaign is between $1-15,000.

**- What are some limitations of this dataset?**

The data is limited by the time frame, the most recent data is from May 2017. The data is also limited by the Kickstarter platform, there are many other crowd funding services that exist; those may or may not provide different results. The fundraising goal and pledged amounts are listed in local currency, those should be converted to a consistent currency to better compare.

**- What are some other possible tables and/or graphs that we could create?**

I would be interested in comparing the length of the campaign (in days) with the likelihood of success. With more data, it would also be interesting to compare % of goal achieved per day to understand when I could expect the majority of the goal to be met.