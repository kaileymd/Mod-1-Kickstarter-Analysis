# Kickstarting with Excel

## Project Overview
So you want to crowdfund your dream project - now what? This project will delve into Kickstarter campaign data to discover any trends between campaign outcomes.

#### Purpose
This analysis will look at the performance of projects in the 'Theater' category, including plays, musicals, and theater spaces, to provide insight and actionable takeaways to make *Fever*, Louise's play, a possibility. Louise is an upcoming playwright who anticipates needing $10,000 to fund *Fever*.

## Analysis and Challenges
What makes up a Kickstarter? According to the [Kickstarter Creator Handbook](https://www.kickstarter.com/help/handbook?ref=rules), there are several parts that can be summarized as:
* The Project
* The Funding Goal
* Promotion and Rewards

This analysis will focus on Project and Funding Goal data trends for the Theater category.

#### Timing is Everything
One of the benefits of Kickstarter is the flexibility to start your campaign once you have your project pitch together. If your project can be launched *whenever*, then when is the right time to get started? The graph below takes a look at Theater campaigns and their outcomes relative to their start date:

![Theater_Outcomes_vsLaunch](https://raw.githubusercontent.com/kaileymd/Mod-1-Kickstarter-Analysis/44b25e9e22a917b73ebf5b6475db0f3fb4d2ffc3/images/Theater_Outcomes_vsLaunch.png)

There is an overall increase in theater projects in Quarter 2 but also a significant spike in successful campaigns, particularly in May and June. This can be contrasted with the decreasing rate of successful projects in Quarter 4, finally wrapping up the year with nearly an even amount of successful and failed number of campaigns in December.

#### Money, Money, Money
Now for the hardest part: convincing strangers on the internet to give you money to fund your dream. To account for different types of theater projects requiring different budgets, we limited the data to show *only* plays:

![Outcomes_vs_Goals](https://raw.githubusercontent.com/kaileymd/Mod-1-Kickstarter-Analysis/44b25e9e22a917b73ebf5b6475db0f3fb4d2ffc3/images/Outcomes_vs_Goals.png)

An important detail missing from this chart is that 50% of over 1,000 Kickstarter plays set their goals to less than $5,000, and 60% less than $10,000. while there appears to be a small range of successful higher budget plays, that is due to the low amount of campaigns setting their goals that high to begin with. In addition to few plays exceeding goals of $15,000, the graph shows a high rate of failure.

#### Challenges and Difficulties Encountered
The data presented two main challenges:
1. Unix time codes for launch and end dates, which required further formatting to become readable.
2. Qualitative data in the blurb which could not be further analyzed.

The Unix time code challenge was easily solved, but qualitative data is not easily studied in mass analysis. This will deny deeper analysis on unique aspects of plays that could change their outcome. Other challenges involved the quantity of the data slowing down my equipment, thus making analysis take longer.

## Results

#### Takeaways & Recommendations
The conclusion of our analysis has revealed several important takeaways:
1. Theater related campaigns have significantly higher rates of success when launching in May or June.
2. Theater related campaigns have significantly higher rates of failure in the Quarter 4.
3. Plays with budgets less than $15,000 have higher success rates, and budgets less than $5,000 have significantly higher success rates.

For Louise's play *Fever*, I would recommend launching in May or June and lowering the budget. If reducing the budget is not possible, I recommend further analysis to focus on the remaining component of Kickstarter campaigns, Promotion and Rewards. If there are trends connecting certain reward items, donation levels, or promotional tactics to higher rates of success, that could increase Louise's odds of success with her budget at $10,000. 

#### Study Limitations
Unfortunately, this data set is limited and does not provide information on types of rewards or any promotional tactics taken on behalf of the creator and would need to come from somewhere else. We also cannot drill down further into the data to reveal genres of successful plays, or where in the U.S. the plays were expected to perform.

#### Moving Forward
To continue the analysis, we could create more graphs to reveal if a certain time of day produces higher success, the average donation amount, and length of Kickstarter campaigns to help Louise determine how to set up her campaign and how long she should expect to fundraise before her goal is met.

If Louise determines more analysis is necessary, check back soon for further project updates.
