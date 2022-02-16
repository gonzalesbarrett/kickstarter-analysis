# kickstarter-analysis

Module 1

# Kickstarting with Excel

## Overview of Project

Analysis of Kickstarter campaigns utilizing pivot tables and pivot charts to simplify the data for the user.

### Purpose

The purpose of the analysis was to assist the user in identifying trends or opportunities with the presented Kickstarter data. The primary focus was on ‘Theater’ and ‘Plays’ campaigns since the user wishes to crowdsource their own play. Ideally, we would be able to identify trends or traits that successful campaigns utilized to get funding and identify mistakes or errors in campaigns that failed to meet their goals. The user would use the data presented to make an informed decision on their own Kickstarter campaign.

## Analysis and Challenges

I utilized excel and transformed the presented data into a table and created relevant columns with supplemental calculations. Functions utilized include: IFERROR/ROUND/YEAR/DATE. Also utilized the text to column feature to separate values via a delimiter. The only challenge I ran into was for some reason the pivot chart feature decides to jumble the order of the ‘Outcomes Based on Goals’ data specifically the ‘Goals’ column. Sorting did not solve the issue. Discovered that individual axis’ can be rearranged to a preferred order. No other issues experienced during this module.

 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The more successful month to launch a Kickstarter campaign in the Theater category is May and the worst month is December. However, the failure rate remains relatively steady from May throughout the Summer so while May and a few of the subsequent months have the highest rate of successful campaigns it also maintains the highest average of failures. The two conclusions we can draw from this is, launching a campaign during the winter holiday months should be avoided, and while May and early summer has the largest number of successful campaigns, failures are high as well which may indicate competition is highest during this time.


- What can you conclude about the Outcomes based on Goals?
The lower the dollar amount goal the higher the likelihood of success. However, there does seem to be a sweet spot in the 35k to 45k range where many campaigns have succeeded. This may show us that while a lower goal is usually more attainable, many successful plays have an average budget/goal in the 35k to 45k. The user would want to examine where there play falls into relation to this two areas. If the goal is a little high can it be trimmed down to meet an easier goal? Or can costs be increased a bit to present the best show possible?

- What are some limitations of this dataset?
We don’t know if a certain genre of play/theater production is more successful than others. Each Kickstarter campaign is unique, and results may vary based on the influence of the campaigner and how much effort/time/rewards they implement into their campaign. We also do not know how “successful” successful campaigns were. While the product was assumed to be created it does not mean it was received well. 

- What are some other possible tables and/or graphs that we could create?
We could review how many backers a project has and compare than to the results. Does a higher rate of traffic/users/”staff pick/spotlight help a campaign to be successful? Does theater/play campaigns follow similar patterns compared to other categories? Does average donation play a role in relation to specific projects/categories? All of these questions could be answered through pivot tables supplemented with pivot charts.
