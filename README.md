# Kickstarter Campaigns Analysis #
# **Table of Contents** ##
1. [Project Overview](#project-overview)
    1. [Objectives](#objectives)
1. [Analysis and Conclusions](#analysis-and-conclusions)
    1. [Dataset](#dataset)
        1. [Parent Category Outcomes](#parent-category-outcomes) 
        1. [Theater Category Breakdown](#theater-category-breakdown)
    1. [Outcome vs Launch and Goals](#outcome-vs-launch-and-goals)
        1. [Theater Outcomes vs Launch](#theater-outcomes-vs-launch)
        1. [Outcomes vs. Goal](#outcomes-vs-goals)
    3. [Edinburgh Plays Analysis](#edinburgh-plays-analysis)
1. [Limitations](#limitations)
1. [Results and Recommendations](#results-and-recommendations)
    1.  [Future Great Britian Music Project](#future-great-britian-music-project)

# Project Overview <a name="project-overview"></a>
Louise launched a Kickstarter crowdfunding project for a United States theater play called Fever.  Kickstarter requires all projects using their platform to establish a goal before launch.  Projects are considered live during the fundraising period and last on average 33.41 days.  The success of the project is measured by whether the goal is met or exceeds that initial goal.

As a result of the campaign, she requested additional analysis on outcomes based on launch date and goals to better understand why some projects meet their goals while others do not.

## Objectives <a name="objectives"></a>
The requested focus was to analyze the success fail rate of the previous Kickstarter utilizing the platform to raise capital. In addition, we reviewed average pledge amounts, duration, the best time of year to launch, and trends that would help her achieve her current and future goals.

# Analysis and Conclusions <a name="analysis-and-conclusions"></a>
## Dataset <a name="dataset"></a>
We are using the Kickstarter dataset [^1] to analysis the outcomes of other theather play to identify success of other project goals vs. launch capital fundraising campaigns to understand better why some projects meet their goals, and others do not.The Kickstarter data contained 4,115 projects in various categories, countries, goals, launch dates and outcomes.  The below information is a sampling of the type of information we used to analyise the data.  Three (3) countries makeup a majority of the data in Kickstarter's system.

Country | No. of Project | Project % | Successful Projects | Successful Project %
|:-------:|-------------:|:---------:|-------------------:|:--------------------:|
US | 3,038 | 74% | 1,651 | 76% | 
GB | 604 | 15% | 366 | 17% |
CA | 146 | 3% | 64 | 3% |
Other | 327 | 8% | 104 | 4%

### Parent Category Outcomes <a name="parent-category-outcomes"></a>

![Parent Category Outcome](https://user-images.githubusercontent.com/17502725/138762851-220b3377-98bb-433f-80ff-a2c79b3a6909.png)

### Theater Category Breakdown <a name="theater-category-breakdown"></a>

The theater category as shown below is the most successful in fundraising using Kickstarter platform. Within each category are subcatagories and more detail information which we drilled down on in order to better understand the data which we will demonstrate below.    

![TheatherCategoryOutcome](https://user-images.githubusercontent.com/17502725/138762932-b9667357-9a50-47b2-ae2b-79c3727a7517.png)

Theater category data is broken down into three categories musicals, plays, and spaces:

Subcatagory | No. of Project | Project % | Successful Projects | Successful Project %
|:----------|-------------:|:---------:|-------------------:|:--------------------:|
Musical | 140 | 10% | 60 | 8% | 
Plays | 1,066 | 77% | 694 | 83% |
Spces (Theaters) | 187 | 14% | 85 | 11% |

![SubcategoryPlaysStatistics](https://user-images.githubusercontent.com/17502725/138763960-0662ac0c-5d50-4fba-bf3f-e49aa1d1be35.png)

## Outcome vs Launch and Goals <a name="outcome-vs-launch-and-goals"></a>
### Theater Outcomes vs Launch <a name="theater-outcomes-vs-launch"></a>
The most successful time to launch a crowdfunding campaign is between May through July, with an average duration time of 33.41 days.

![TheaterOutcomesvsLaunch](https://user-images.githubusercontent.com/17502725/139151257-f385ffad-8020-4852-ac2f-a9d690a13993.PNG)

### Outcomes vs. Goal <a name="outcomes-vs-goals"></a>
The Outcomes vs. Goals showed there are two markets investors that have a greater success raching the initial goals ranging between lower end of the range to $5k, and then $35k - $45k. 

![OutcomesvsGoals](https://user-images.githubusercontent.com/17502725/139151367-ecb42d92-818a-4a65-81e5-e6259473e319.PNG)

## Edinburgh Plays Analysis <a name="edinburgh-plays-analysis"></a>
There is also interest to gather data on five plays Louise saw while in Edinburgh from Kickstarter platform.  They are Be Prepared, Checkpoint 22, Cutting Off Kate Bush, Jestia and Raedon, and The Hitchhiker's Guide to the Family.  All five plays raised capital using Kickstarter, and each one exceeded its goals.  Two of the five projects were launched in May, two in June, and one in July with an average donation of $40.48, and an average duration period of one month.  Cutting Off Kate Bush was the most successful exceeding the goal by $1,076, launched in June.

Name | Goal | Pledged
|:------------------------------------|-------:|-------:|
Be Prepared | $2,000 | $2,020
Checkpoint 22 | $2,000 | $2,020
Cutting Off Kate Bush | $1,500 | $2,576
Jestia and Raedon | $1,000 | $1,168
The Hitchhiker's Guide to the Family | $4,000 |$4,137

# Limitations <a name="limitations"></a>
*	There was limited country representation, with the United States, Great Britain, and Canada representing most of the data related to plays. 

# Results and Recommendations <a name="results-and-recommendations"></a>
*	In reviewing the play data, out of 1,066 launches relating to plays, they met or exceeded their expected goal by 694 or 66%. The most significant number of launches occurred between May through June, then peaking again in October. In comparison, 353 or 34% failed to meet or exceed their goals.
*	An additional observation is there were two (2) countries Luxemburg, and Singapore, that had only a few campaigns and were 100% successful, and Belgium was 50% successful with their fundraising projects.
*	Launching the crowdfunding campaign between May and June would be the most optimal time, and the initial goal of $4,000 is within range for a successful fundraising project based on the IQR goal and pledge.

Stat | Successful | Failed | Stat | Successful | Failed
|:----------------------|------:|-------:|:-----------------------|------:|-------:|
Mean Goal| $5,049 | $10,554| Mean Pledge | $5,602 | $559|
Median Goal | $3,000 | $5,000 | Median Pledge | $3,168 | $103 |
Standard Deviation | $7,749 | $21,968| Standard Pledge | $8,335 | $1,331|
Upper Quartile of Goal | $5,000 | $10,000| Upper Quartile of Pledge | $5,699 | $501|
Lower Quartile of Goal | $1,500 | $2,000| Lower Quartile of Pledge | $1,717 | $9|
IQR Goal | $3,500 | $8,000| IQR Pledge | $3,982 | $492|

## Future Great Britian Music Project <a name=future-great-britian-music-project></a>
Additionally, there was mention of a future musical project in Great Britain with a budget of £4,000, but based on the graph below, to have a successful campaign, the goal would need to be set around £1,500.

![EdinburghMusicProject](https://user-images.githubusercontent.com/17502725/138763465-a9361961-54fb-4f86-9726-2a87141ec9d2.PNG)

### Footer
[^1]: https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_1/data-1-1-3-StarterBook.xlsx
