# Kickstarter Review of Theater and Play Crowdfunding

## Overview of Project
Kickstarter is an online platform that allows anyone with an idea to ask for funding through a crowdfunding process. This review of Kickstarter uses the website's data to review trends of successful, failed, and canceled theater campaigns, with a narrowed view on the plays catagory. 

### Purpose 
The main purpose of the analysis to discover and determine what specific trends within past theater campaigns could have affected Laura's play, "Fever," campaign outcome. 

## Analysis and Challenges
After receiving the raw data from Kickstarter, it needed to be organized in a manner that would be reviewable to Laura. This was done by determining what was needed to ensure Laura had what she needed for a successful campaign launch. The information was organized a few ways: 
1) Narrowing down the entire data set for Kickstarter to the Theater Catagory
- Further catagorizing this data into several outcomes (e.g. successful, failed, and canceled)
- Determinining how the time of year affected the outcome of the campaign through a line chart based on a monthly time frame.
2) Reviewing the "plays" catagory based on the level of the goal and if these were either successful or if they were failed or canceled. 
- This review was broken down by what the goal was and what percentage of those goals were funded or not at those levels.

You can find the detailed report below, otherwise I will go through the two main reviews that I did further in this report.

[Kickstarter_Challenge.xlsx](https://github.com/npetty15/week1_excel_hw/files/8364225/Kickstarter_Challenge.xlsx)

### Analysis of Outcomes Based on Launch Date
The point of this review was to see the trends on theater campaigns by the timeframes in which they were launched. The three types of outcomes in this review were successful, failed, and canceled. Successful here means that they either hit their funding goal or surpassed it. Failed and canceled both mean the goal was not hit and funding was not acquired for the project. One of the main challenges for this review was to determine where to filter the report. Do we review the entire theater parent category, or do we delve straight into the subcategory of plays? With this review I decided to review the entire parent category of theater, as to have a broader data set to see what the trends were over a calendar year for theater campaign launches. Doing this allows us to see how this category, as a whole, performs when it comes to determining a launch date strategy. 

The chart you will see below is organized by parent category of theater. If you wanted to review a certain year or number of years, this report could also be filtered in that fashion as well. For this review the data set is filtered to all years. This report is also driven by three outcomes, successful, failed, and canceled. Live campaigns have been removed from the review as we do not yet know the outcome of these campaigns. Finally, the data was organized in a line chart to better see the trends over a calendar year. 

One limitation of this review could be goal amounts. These were not taken into consideration during the launch date review. These types of review could aid in why the projects failed during a certain month. 

![Theather_ Outcomes_vs_Lauch](https://user-images.githubusercontent.com/100856534/160436178-21c47b95-276a-44c0-ab40-9fec55710b24.png)

As can be seen by the line chart depicting the Outcomes by Theater data, the best month to launch an outcome would be in May, followed by June and July. May, however, seems to be the best month to launch a theater campaign by a wide margin. The inverse of that shows us that December is the worst month to launch a campaign as it has the lowest successful campaigns. 

### Analysis of Outcomes Based on Goals
To continue the review from the Outcomes Based on Launch Date, I further delve into the plays subcategory. Plays is a sub category of the theater parent category. The subcategory was used in this review to help Laura determine the best play campaign strategy for her next Kickstarter launch. 

To do this review, I created a set of goal categories that start at less than $1,000, continue to 1000 to 4999, 5000 to 5999, and so on at $5,000 increments, up to $50,000 and higher. For each of these goal categories the campaigns, were again, broken down into successful, failed, or canceled. The outcomes of these reviews were represented as a percentage to show at what goal categories were the campaigns either successful and funded or if the campaigns failed. To perform this review an excel function was used called Countifs. This function is used to review conditionals, such as goal category (e.g. $1,000 to $4,999) and campaign outcome (e.g. failed). Doing so shows us an accurate representation of how many campaigns at that goal level was successful or not. This was also represented via a line chart as shown below. 

A limitation to this review could be that we are looking at every country in the world. If, for example, a new campaign were to launch on a European tour or in Great Britain, a narrowed trend review would be beneficial. As it stands in the review below it is not geographically centered and gives us a worldly view on Outcomes based on Goals. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/100856534/160440802-d01b0a03-f2ba-4179-8c85-b3dae0a52673.png)

As stated before, this line chart shows the goal categories ranging from $1,000 and below to $50,000 and above, represented as percentages. As can be reviewed there seems to be one range that does the best when it comes to being funded, $0 to $4,999. The worst range for goals to not be funded is $45,000 and higher. 

### Challenges and Difficulties Encountered

The main challenge for this project was creating a coherent picture with the data presented. Where does one stop in filtering the data? For example, there was many more data points in this review that could have been used, such as pledge amount and average pledge. How would this have affected the review. Also as mentioned, above in the two reviews that were done, how would this change based on geographical location or if we took out some very high goal campaigns (or outliers) that failed. Would this have changed the data set enough to make a material difference in what was being presented. I think the answer of where to stop would need to come from Laura as the client. What does she really want to see represented? Understanding and anticipating your clients needs will always be a challenge when it comes to these reviews. 

## Results
- What are two conclusions you can draw about the Outcomes Based on Launch Date?
1) The most successful month to launch a campaign is in May, followed by June and July respectively.
2)  The least successful month to launch a campaign is in December. 
- What can you conclude about the Outcomes Based on Goals?

The best trending goal categories are $0 to $4,999. Beyond that the percentage of success to fail fluctuate, but never get back to the amount of success in the categories from $0 to $4,999. 
- What are some limitations of this dataset? 

This data set is exclusively Kickstarter data, if, for example, Laura would use Go Fund Me, or Indigogo, we would need to see if we can get data from those areas as well. Based on that are we getting the full picture of how theater and specifically plays are funded via crowdfunding platforms, or would we need to get data from all other crowdfunding platforms to get a better overall picture of this type of review? Is one platform better for theater than another?

Another limitation I can see is that since these reviews are based on goals, how do we determine the sincerity of other's campaign goals. Did they pick a goal amount at random, or did they go through a review like Laura did? Not being able to determine how goals are formulated may or may not change the outcomes reached, as they may be unattainable for some campaigns.

- What are some other possible tables and/or graphs that we could create?
1) Geographical reviews of data could show what does better via area in the world. 
2) Review of outliers in the data, to assess if the outcomes are being skewed by campaigns that are asking a lot or too little, compared to what Laura's goal was. 
3) Filtering by year, as perhaps, some years were better than others. This data goes back to 2009, so we could do a review by year to see if this affects the outcomes of success or failure.
4) Plays are a subcategory of the parent category of theater. How does the play subcategory relate to all other theater subcategories? 
