# MarketingCampaignExperimentationAnalysis
Simple marketing campaign A/B testing with experiment and control group data analysis

## Background
Marketing companies want to run successful campaigns but the market is complex and several options can work. So normally they run A/B tests, which is a randomized experimentation process wherein two or more versions of a variable (web page, page element, banner, etc.) are shown to different segments of people at the same time to determine which version leaves the maximum impact and drive business metrics.
The dataset I am interested in exploring is the results of an A/B test run by a company. The company has conducted A/B tests with the majority of the people exposed to ads and a small portion of people to a Public Service Announcement (PSA) (or nothing).

## Data overview
The data comes from Kaggle and contains 588101 observations and 6 variables. There are no missing values. The 6 variables provided are:
* User id
* Test group - If "ad" the person saw the advertisement, if "psa" they only saw the public service announcement
* Converted - If a person bought the product then True, else is False
* Total ads - Amount of ads seen by person
* Amount of ads seen by person - Amount of ads seen by person
* most ads day: Day that the person saw the biggest amount of ads
* Most ads hour - Hour of day that the person saw the biggest amount of ads

## Research design:
The business question that I am interested to answer are:
* Does Number of ads people see contribute to conversion?
* At what day, people watch the highest number of ads?

## Hypothesis
* Do people who converted have been shown a bigger number of ads on average than people who are not converted?
* Is there a significant difference in the number of ads seen on average from Monday to Friday? If yes, Which day do people see the biggest number of ads?

## Results
Able to identify that ad campaign leads to conversion but the day of ads ran doesn’t impact the conversion. These insights let the business to continue running ad campaigns and avoid running additional ad campaigns targeted for weekends, thereby saving the expense associated with additional campaigns.

## Next Steps
Examine how much of the campaign success could be attributed to the ads.
