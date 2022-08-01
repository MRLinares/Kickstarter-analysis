# Kickstarting with Excel
## Overview of Project
Performing analysis on Kickstarter data to learn how campaigns fare in relation to their launch dates and funding goals.
### Purpose
To give our client analytical insight on the campaign data and how certain variables effect one another, if at all.
## Analysis and Challenges

Using Microsoft Excel, Kickstarter data was sorted by various variables including launch dates, campaign outcomes, funding goal amounts, and pledged amounts, just to name a few.

### Analysis of Outcomes Based on Launch Dates

Data was extracted from the data set and filtered for campaigns having to do with theater as a category.  Next, Unix timestamps were converted to Month/Day/Year to find out exactly when the campaign was started.  A pivot table was then created to test for correlation between launch date and campaign outcomes.  Finally a graph was created from the pivot chart to visualize the results.  A line graph was chosen to best represent the data.

![Theater_Oucomes_vs_Launch](https://user-images.githubusercontent.com/108758105/181832299-03667918-fd84-41ca-ba43-c6c3517e92a6.png)

### Analysis of Outcomes Based on Goals

Like the analysis for outcomes based on launch dates, data was extracted from the data set and filtered for campaigns having to with theater as a category and further filtered for a subcategory of "plays".  Some theater projects may be real estate in nature and that may require much larger goals that may skew the results in the high range, so they were filtered out.  The majority of goals were then divided in increments of five thousand dollars, except the first two ($1000, or less, and $1000 to $4999 respectively) and the last (anything over $50K). A line graph was created to represent the success rate based on the goals and a bar chart was created to represent total projects to highlight the cluster of the data being within the $1 and $15,000 range.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/108758105/182052260-b1d76fad-57f7-4abf-a875-eaafd05ecdcc.png)

![Number_Projects_Based_on_Goal](https://user-images.githubusercontent.com/108758105/182052289-6ce344f9-d524-45b5-ae9f-dbc8572455ea.png)

### Challenges and Difficulties Encountered

One challenge encountered during the project was trying to visualize the conclusion I wanted to convey based on the rubric given.  Ultimately I decided adding a bar chart would paint a clearer picture.

## Results

#### Theater Campaigns vs Launch Dates

From an analysis solely based on how theater campaigns fared in relation to their launch dates, one can conclude that there is a precise window in which an individual can find increased chances of success in their theatrical endeavors with respect to a Kickstarter campaign.  By timing their launch date between early spring to mid summer, they can increase their odds of a successful campaign given the large spike of successful campaigns that start in this time period (shown in the chart below) and the proportion of success in relation to those that failed.  Given the nature of the curves of each line, it is apparent that there is a positive relationship between the the outcomes, meaning that launch dates impact whether you will find success or not in the same way, except for the months of November and December where it the curves have a negative relationship.  It is inadvisable to attempt a launch in either of these months as the chances for success decrease, while those of failure increase.

#### Theater Campaigns vs Funding Goals

From an analysis solely based on how theater campaigns fared in relation to their funding goals, one can conclude that there is a direct relationship between goal amounts and success rates.  Unlike the analysis above where both success and failures spiked up in March, albeit to a much lesser extent for failures, their is a direct correlation between how high you set your goal and the chance you would find success in that bracket.  By sorting the data into intervals of five thousand dollars, it becomes evident that low goals (below $5000.00) have high rates of success for theater campaigns in relation to those that have failed. With 92% of our data coming in the range of one to fifteen thousand dollars (more clearly defined by the bar chart), it becomes apparent that the higher your goal, the less likely you will find success in a theater campaign on Kickstarter.  The large interchange visible on the high side of the spectrum of the line graph is a small sample size of nine projects.

#### Limitations

One piece of information that may give clarity to the data is how many of these theater campaigns relied solely on Kistarter funding or whether they were able to secure funding from other sources and whether that had any effect on success rates.  It's possible that successful campaigns that set small goals already had the majority of their needs taken care of and the remainder would have been for non-essential things.
Another important piece of information that may effect funding is the popularity of the producer/product.  It's possible that they may have had success with a previous play or they have ties to the community and were able to easily raise the funds through those influences.
