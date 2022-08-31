# Kickstarting with Excel

## Performing analysis on Kickstarter data to uncover trends

### The purpose of this analysis is to determine any trends within Kickstarter crowdfunding projects for a client. Louise, a playwrite, is wanting to start her own Kickstarter campaign to fund a play she has written. Louise has estimated her budget to be over $10,000 and is wanting to know what may help her to run a successful campaign. The dataset includes information about launch dates, goals, and success levels from over 3000 Kickstarter projects in various categories like Film, Music, Photography, and Theater that can help Louise to reach her fundraising goal. In this analysis we will focus on plays to ensure the results fit her needs best.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date 

Looking at the big picture, we can see in the following chart a broad overview of the number of successful, failed, and canceled theater campaigns based on the month the campaign launched from 9 years of data. There is a noticable increase in successful campaigns in the spring, and slightly less noticible is a very slight increase in failed campaigns during this time as well. It is important to keep in mind this is based on a total number of campaigns, not a percentage.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111471057/187792962-7a224ca6-7bac-4ae8-aa2a-91390c4a8b22.png)

This graph was created to make a visual for the following pivot table. The pivot table does include the total number of campaigns based on launch month and can be filtered by Year.

<img width="327" alt="Pivot-Table_Screen-Shot" src="https://user-images.githubusercontent.com/111471057/187798874-e48ae2cc-f069-40a0-bbde-d7fa8beacce1.png">

### Analysis of Outcomes Based on Goals 

Taking a look from a different perspective, we can see in the following chart the success rate of a theater campaign based on the goal that was set for fundraising. We can see from this chart that as the fundraising goal goes up the failure rate goes up while success goes down, but then that trend switches between $30,000 - $44,999 before switching back again. While this chart does have an advantage with showing overall percentages of success and failure rates for goal ranges, it should be noted that the higher the goal, the less data there is to give a good example of probable outcomes.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111471057/187795207-fdba7102-9326-4fa7-9d0d-9b708b106398.png)

This graph was created to make a visual for the following worksheet. The data was collected using COUNTIFS to collect data from another worksheet. I used [Microsoft's support webpage](https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842) to correctly use the COUNTIFS function.

<img width="930" alt="COUNTIFS_Screen-Shot" src="https://user-images.githubusercontent.com/111471057/187799354-f7e7682e-b70c-4540-a09c-4f3f7cfa99b7.png">


### Challenges and Difficulties Encountered 
One of the challenges I came across in this analysis was using the COUNTIFS function in Excel.

## Results

- Looking at the Theater Outcomes based on Launch Date, we can conclude that there is a higher chance of successfully reaching a funding goal in the Spring, but there will also be more competition in the play category.

- When reviewing the Outcomes based on Goals we can see that as the goal gets closer to $25,000 the success rate goes down, but it doesn't reach 0% until the goal goes above $45,000.

- Some limitations of this dataset are Kickstarter specific. We do not have information about social media presence of the fundraiser, how many places the campaign was broadcast, or how many times the campaign was viewed with and without backer donations.

- I think the best graph for viewing the success rates for this data is in box and whisker plots. There are a few outliers in the data that make our current charts a little biased. 
