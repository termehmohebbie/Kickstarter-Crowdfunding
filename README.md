# Kickstarter-Crowdfunding

## Background
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.

To receive funding, the project must meet or exceed an initial goal, so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. In this project, we organized and analyzed a database of 1,000 sample projects to uncover hidden trends.


## Statistical Analysis
Most people would use the number of campaign backers to assess the success of a crowdfunding campaign. Creating a summary statistics table is one of the most efficient ways that data scientists can characterize quantitative metrics, such as the number of campaign backers.

For gaining an in-depth understanding of campaign backers, we evaluated the number of backers of successful and unsuccessful campaigns by creating a new summary statistics table.


## Report
* Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?
The most successful campaigns are plays in “theater” category. After that, “film & video” and “music” campaigns were more successful.
56% of the total campaigns were successful, 37% were failed and less than 6% were cancelled.
The overall performance of successful campaigns was higher in June and July.

* What are some limitations of this dataset?
we only have access to 7 countries and 10 years of data. Difference in the currencies make some calculations less accurate or too hard to perform.

* What are some other possible tables and/or graphs that we could create, and what additional value would they provide?
We can use pie charts to have a better view of each category’s overall performance. we can also try to find what other variables could possibly have any impact on the success of a campaign such as the country, the length of the campaign, having the project on spotlight web page, being picked by the Kickstarter staff, etc. We can plot different scatterplots to find relations between any of these variables and a campaign’s success.

* mean or median better summarizes the data?
After plotting the box plot for successful and failed campaigns, we can see there are many outliers in this data set, so we can say the median is a better measure, but the minimum and maximum are very far from each other and the range is wide.
By looking at the IQR or size of the box we can understand that half of our observations are so close to the median and their values are not too far from each other, so our data is more consistent.
