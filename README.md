# Kickstarter Campaigns Analysis #
## Project Overview ##
Louise plans to launch a Kickstarter crowdfunding project for a theater play she would like to produce in the United States.  She would like us to analyze the success of other project goals vs. launch capital fundraising campaigns to understand better why some projects meet their goals and others do not.  A Kickstarter requirement is to have an initial goal amount established before launching.  The success of the project is measured by whether the goal is met or exceeds that initial goal.  Since Louise is producing a theater play, we focused our analysis on that area.

## Objectives ##
The requested focus was to analyze the success fail rate of the previous Kickstarter utilizing the service to raise capital. In addition, we reviewed average pledge amounts, duration, the best time of year to launch, and trends that would help her achieve her goal.

## Analysis and Conclusions ##
### Dataset ###
The Kickstarter data contained 4,115 projects in various categories, countries, goals, launch dates and outcomes.  The below information is a sampling of the type of information we used to analyise the data.  Three (3) countries makeup a majority of the data in Kickstarter's system.   
*	US - 3,038 projects (74%) and 1,651 successful projects (76%)
*	GB - 604 projects (15%) and 366 successful projects (17%) 
*	CA – 146 projects (3%) and 64 successful projects (3%)
*	Other – 327 projects (8%) and 104 successful projects (4%)

![Parent Category Outcome](https://user-images.githubusercontent.com/17502725/138762851-220b3377-98bb-433f-80ff-a2c79b3a6909.png)

Theather category are the most successful in fundraising using Kickstarter. 

![TheatherCategoryOutcome](https://user-images.githubusercontent.com/17502725/138762932-b9667357-9a50-47b2-ae2b-79c3727a7517.png)

Below is a breakdown of the theater category data, further analyzing three (3) additional subcategories; musicals, plays, and spaces represented below: 
*	Musical – 140 projects (10%) and 60 successful projects (8%)
*	Plays – 1,066 projects (77%) and 694 successful projects (83%)
*	Spaces (Theaters) – 187 projects (14%) and 85 successful projects (11%)

![SubcategoryPlayStatistics](https://user-images.githubusercontent.com/17502725/138763960-0662ac0c-5d50-4fba-bf3f-e49aa1d1be35.png)

## Outcome Analysis Using Launch Dates ##
The most sucessful time to launch a crowdfunding campagine is between May through July, and then in October with a duration time of approximately one month, give or take a few days. 

![TheatherOutcomeBasedOnLaunchDate](https://user-images.githubusercontent.com/17502725/138764193-323a314e-bdb5-44b8-916e-a1a4ec033d66.png)

## Edinburgh Music Project ##
There is also interest to gather and compane data on five plays Louise saw while in Edinburgh from Kickstarter.  They are Be Prepared, Checkpoint 22, Cutting Off Kate Bush, Jestia and Raedon, and The Hitchhiker's Guide to the Family.  All five plays raised capital using Kickstarter, and each one exceeded its goals.  Two of the five projects were launched in May, two in June, and one in July with an average donation of $40.48, and an average duration period of one month.  Cutting Off Kate Bush was the most successful exceeding the goal by $1,076, launched in June.

Name | Goal | Pledged
|------------------------------------|-------|-------|
Be Prepared | $2,000 | $2,020
Checkpoint 22 | $2,000 | $2,020
Cutting Off Kate Bush | $1,500 | $2,576
Jestia and Raedon | $1,000 | $1,168
The Hitchhiker's Guide to the Family | $4,000 |$4,137

# Limitations #
*	There was limited country representation, with the United States, Great Britain, and Canada representing most of the data related to plays. 

# Results & Recommendations #
*	In reviewing the play data, out of 1,066 launches relating to plays, they met or exceeded their expected goal by 694 or 66%. The most significant number of launches occurred between May through June, then peaking again in October. In comparison, 353 or 34% failed to meet or exceed their goals.
*	An additional observation is there were two (2) countries Luxemburg, and Singapore, that had only a few campaigns and were 100% successful, and Belgium was 50% successful with their fundraising projects.
*	Launching the crowdfunding campaign between May and June would be the most optimal time, and the initial goal of $4,000 is within range for a successful fundraising project based on the IQR goal and pledge.

Stat | Successful | Failed | Stat | Successful | Failed
|-----------------------|------|-------|-----------------------|------|-------|
Mean Goal| $5,049 | $10,554| Mean Pledge | $5,049 | $10,554|
Median Goal | $3,000 | $5,000 | Median Pledge | $3,000 | $5,000 |
Standard Deviation | $7,749 | $21,968| Standard Pledge | $7,749 | $21,968|
Upper Quartile of Goal | $5,000 | $10,000| Upper Quartile of Pledge | $5,000 | $10,000|
Lower Quartile of Goal | $1,500 | $2,000| Lower Quartile of Pledge | $1,500 | $2,000|
IQR Goal | $3,500 | $8,000| IQR Pledge | $3,500 | $8,000|

*	Additionally, there was mention of a future musical project in Great Britain with a budget of £4,000, but based on the graph below, to have a successful campaign, the goal would need to be set around £1,500.

![EdinburghMusicProject](https://user-images.githubusercontent.com/17502725/138763465-a9361961-54fb-4f86-9726-2a87141ec9d2.PNG)


