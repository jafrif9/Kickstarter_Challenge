# Kickstarting with Excel

## Overview of Project

### Purpose
Louise desired to start a fundraiser for her play ‘Fever’ but was unsure on its potential success. She compiled data consisting of information regarding other fundraisers to potentially aid her in her own campaign. The purpose of the project was to sort and analyze the data compiled by Louise to determine any variables that affected the overall outcome of the various campaigns. The analysis would then later aid Louise in orchestrating a fundraiser of her own.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The year of creation for each campaign was retrieved from the Unix timestamps in Louise's raw data table, and further added as its own column. From there, a pivot table was created to show the number of successful, failed, and canceled campaigns in each month. The pivot table had to be filtered so the outcomes present were only of campaigns falling under the "Theatre" category. Implementing this filter was necessary to ensure only data relevant to Louise's own findings was present. The data was sorted in descending order and used to create a line chart for ease in analysis.

### Analysis of Outcomes Based on Goals
Due to the goals of the campaigns falling under a relatively large range, twelve smaller ranges were created to better divide and visualize the raw data. From there, the number of successful, failed, and canceled campaigns pertaining to plays, falling under each goal range, were calculated, and added to a separate table. Campaigns pertaining to plays were only used to ensure data was relevant to Louise's own campaign fundraiser. From the new table, percentage of successful, failed, and canceled campaigns in each range were calculated and shown in a line chart for ease in analysis.

### Challenges and Difficulties Encountered
The main difficulty faced was working with a large sample size and raw dataset. The difficulty was mainly overcome by being meticulous with all formulas and changes to the data, to ensure the greatest efficiency.

## Results

When comparing the outcomes based on the launch dates, it is visible most campaigns launched from April-August, with the highest success rates being in May and June. In addition, the few campaigns launched in December had a relatively even success and failure rate. With this, it can be concluded that the best time to launch a campaign is during the spring and summer months, while the worst time is during the winter, specifically in December.

When comparing the outcomes based on goals, the lowest goal range had the greatest percentage of successful campaigns. In addition, the largest goal range had the lowest percentage of successful campaigns and the highest number of failed campaigns. From this, it can be concluded that the lower the goal for the fundraiser, the greater the chances of being successful in reaching said goal.

A big limitation of the dataset is its relevance. The data obtained by Louise is at least five years old and therefore does not take into consideration what modern outcomes would be. Another limitation to the dataset is the large sample size. The sample size for the analysis of outcomes based on launch date and the analysis of outcomes based on goal was about 25% and 33% of the raw data respectively. The large sample size increases risk of outliers that can skew the overall values being analyzed.

Another graph that could be created with the given data would be a comparison between the duration of the campaign and the percentage of the goal which was funded. By having this information, Louise can determine how long her campaign should be live for to meet the fundraising goal.

