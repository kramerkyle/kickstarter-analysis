# Kickstarter Analysis
There are three pertinent files in this repository: Kickstarter_Challenge.xlsx, Outcomes_vs_Goals.png, and Theater_Outcomes_vs_Launch.png. The two .png files chart the results of the analysis. The analysis will be fleshed out more fully in subsequent paragraphs.

## Overview of Project
The Kickstarter Analysis was conducted to gain insights into the success of fundraisers based upon goal amounts and timing of fundraiser. More specifically, theater fundraisers are explored as the primary subject of the analysis. Two charts were created and saved as .pngs within this repository.

## Analysis and Challenges
### Outcomes vs Goals
The first branch of analysis centers on the percentage of outcomes that succeed, fail, or are canceled based upon the financial goal. The data is grouped across twelve buckets of goals. The scale of the y-axis will range from  0-120%, but no value will touch higher than 100%. This first figure is detailed below in the chart titled, "Outcomes Based on Goal."

![Outcomes vs Goals](https://github.com/kramerkyle/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Theater Outcomes vs Launch
The second branch of analysis centers on the success of specific theater fundraisers dependent upon the launch date. The x-axis is comprised of the months of the year, and the y-axis tracks the number of fundraisers. The lines across the chart separate the data in successful, failed, and canceled campaigns. This second figure is detailed below in the chart titled, "Theater Outcomes Based on Launch Dates."

![Theater Outcomes vs Launch Date](https://github.com/kramerkyle/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Challenges
The key challenge in this analysis was limited to the "Theater Outcomes vs Launch" section. Within this sub-analysis, the data of the file was presented using Unix time codes. It was necessary to convert the data using a formula that counted the seconds since 1971.

## Results
### Theater Outcomes vs Launch
The Theater Outcomes vs Launch analysis shows several learnings to the viewer. Two of those learnings will be focused on here. The first conclusion from this chart is that theater fundraisers are more likely than not to succeed. This should embolden the fundraiser's willingness to plan a campaign on Kickstarter. Not only this, but the second learning is clear as well. 

The second conclusion from this analysis is that the best month to launch the the campaign is in May. The justificiation for May isn't simply that there is the highest number of successful campaigns launched in the month, but that they outnumber failures by more than twice as much. June sees a similar proportion, but the ratio in May is still higher.

### Outcomes Based on Goals
Looking at the Outcomes Based on Goals analysis, it's important to gain an understanding of what level of goals have a probability equal to or greater than 50%. Goals that are less than $20,000 or are greater than $35,000 and less than $45,000 are at least as likely to succeed as fail. More specifically, goals that are less than $1,000 are the most likely to succeed.

### Limitations & Recommendations
Although the available data has given preliminary insight into the the probability of success on the amount of the goal, there is an undeniable need for deeper analysis. In particular, data that pertained to the exact timing of committed dollars would enable better understanding of donor decisions. Information on the marketing of each fundraiser is also absent from the data collected. Without any insight into the visibility or traffic of the fundraisers, it would be hard to estimate how one may over or under-perform.

Bucketing similar campaigns that were running within the same time period would help the viewer better understand the competition for donor dollars. It may also lend insight into when theater donors are most available, and could be incorporated into the planning of the future campaigns. This information can be ascertained, albeit only roughly, from the existing data. A simple addition from a charting perspective would be to show the percentage of successful, failed, and canceled campaigns by percentage, rather than by number.
