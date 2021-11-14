# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project is to analyze the outcomes of funding campaigns for theaters and plays to help Louise better understand the results of the funding campaign for her play "Fever". Her play came close to its funding goal and she would like to better understand how this compares against other campaigns in relation to both the start date and funding goal. By analyzing other campaigns, Louise is better able to determine if her campaign results are on par with similar ones.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Outcomes were analyzed based on the parent category of "Theater" and month of campaign launch. 
 - All subcategories under the "Theater" parent category were included in the analysis. 
 - All years of launch were included in the analysis. 
 - Outcomes of "successful", "failed" and "canceled" were considered; outcomes of "live" were excluded from the analysis.

The fundraising campaign for the play "Fever" was launched in the month of June. A total of 153 campaigns, including "Fever", were launched within the month of June with an outcome of either successful, failed or canceled. The breakdown of campaign success/failed/canceled rates is as follows:
 - Successful:  100 campaigns (65% of total)
 - Failed:  49 campaigns (32% of total)
 - Canceled:  4 campaigns (3% of total)

Based on the number of successful campaigns launched in June, the play "Fever" did not perform as well as the majority of other campaigns.

The launch month of June has the second highest successful outcomes; the month of May has the highest. While May has a higher number of successful outcomes, it also has a higher number of campaigns launched. The overall percentage of successful Theater campaigns in May is 67% of the total, compared to 65% for the month of June. "Fever" may have had only a slightly better chance of being successful had it been launched in May.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/93630042/141681124-81354d5d-fa60-4bb5-ab3d-65c6824d9eb2.png)

### Analysis of Outcomes Based on Goals
Outcomes were also analyzed based on the subcategory "plays" and total goal amount (currency).

The play "Fever" had a goal of $2,885.00, falling in the goal category of "1000 to 4999". This category had a 73% successful campaign rate and a 27% failed campaign rate. Based on the percentage of successful play campaigns within this goal range, the play "Fever" did not perform as well as the majority of other campaigns. 


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/93630042/141682483-4367131c-5fb8-4e65-bdba-2443b11f9a5c.png)

### Challenges and Difficulties Encountered
The video in Module 1.0.4 indicated that Louise was looking for funding of over $10,000 while the data set shows the play name "Fever" of having a goal of $2,885. This discrepancy made me question whether the analysis being completed was accurate. However, the video did not indicate the launch month. Without this information, we would not be able to perform an analysis by launch month. Based on this logic, I decided to move forward with the data in the spreadsheet for the play name "Fever - a workshop production" and considered the goal discrepancy to be a flaw in the recording.

The "Outcomes Based on Goals" instructions in the "Module 1 Challenge" fails to take into account goals equal to $50,000. The instructions state to create the last two goal ranges as "45000 to 49999" and "Greater than 50000". Following these ranges, the values equal to $50,000 would be excluded from the analysis. After further review, I found that the inclusion of campaigns with a goal equal to $50,000 changed the number of failed and total outcomes but did not change the percentages for each category. All outcomes equal to $50,000 were "failed" and since this analysis was based on percentages, it did not impact the overall results. For this reason, I kept the goal range of "45000 to 49999" in order to match the Module's instructions.

![Challenges1](https://user-images.githubusercontent.com/93630042/141683548-8f810b9f-e644-4751-8681-864db0c741a2.png)

## Results

### Conclusions - Outcomes based on Launch Date
Based on launch date, the campaign for "Fever" did not perform as well as other theater campaigns launched in the same month. 65% of campaigns were successful while "Fever" was not and failed to meet its goal.

When comparing all of the launch months' success and failure rates as a percentage of total, May and June have the highest percentage of successful campaigns. This indicates that while "Fever" did not perform as well as the majority of campaigns launched in June, launching in a different month would not have significantly increased the odds of being successful. The analysis indicates that launch month had a slight impact on the outcome but it's most likely not the only contributing factor the "Fever" campaign results. 

### Conclusions - Outcomes based on Goals
Based on the goal amount (currency), "Fever" did not perform as well as the majority of other campaigns within the "1000 to 4999" range. However, campaigns with a goal of "1000 to 4999" had the second highest success rate (73%); the range of "Less than 1000" had the highest with a 76% successful outcome rate. "Fever" may have had a slightly better chance of being successful had its goal been less than $1,000. 

### Limitation of Dataset
Below are limitations of the dataset available for analysis.
 - Length of campaign (time between date created and date ended) was not included. This could provide additional insight into the success and failure of campaigns, especially when coupled with other data points. For example, shorter campaigns with higher goal amounts may result in a higher failure rate. 
 - Demographic information was not included. Meaningful demographic information may include average income level within the country given and preferences within the country.
 - Categorization of play topic was not included. For example, drama vs comedy. This categorization would allow for a more in-depth comparison of play campaign outcomes. 
 - Columns "staff_pick" and "spotlight" were not defined. Without defining what these columns represent, we are unable to determine whether they could affect results and should, or should not, be included within the analysis.
 - Currency values were not standardized. Due to currency rate differences, comparison of goal amounts is skewed. For example, the play titled "Fishcakes" had a goal of $800 GBP. When converted to USD at today's rates, this is equal to $1,073 USD. In the analysis, the goal for "Fishcakes" was included in the "Less than $1,000" goal category but had the currency been standardized to USD it would have been inlcuded in the "1000 to 4999" goal category. 


### Other Possible Tables/Graphs
