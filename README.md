# Kickstarting with Excel

## Analyzing Kickstarter data to uncover trends

### In order to help advise Louise on maximizing the probability of reaching her Kickstarter funding goal, we are exploring Kickstarter data to see how a project's launch date and funding goal impacts the outcome

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### The Outcomes Based on Launch Date chart provides us with a very helpful breakdown of how various Kickstarter campaigns from the theater parent category performed based on the month in which they were launched. The line chart allows us to clearly see that camnpaigns launched in May, June, and July had a much higher number of successful campaigns than other months, while maintaining a similar number of failed campaigns. This would suggest Louise should perhaps consider launching her campaign in May.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/82119497/116020308-0813bc80-a614-11eb-9b1f-d91d2fb8b9bd.png)

### Analysis of Outcomes Based on Goals

#### The Outcomes Based on Goals chart provides us with a breakdown of campaign success rate based on the goal. The line chart allows us to see the negative correlation between campaign goal and success rate for our ranges that have sufficient sizes. As the campaign goal increases, the success rate of hitting the goal decreases. The ranges that have the highest success rates are the "Less than 1000" and "1000 to 4999" ranges. This suggests that Louise should consider keeping the goal of her campaign to under $5,000.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/82119497/116020689-d51df880-a614-11eb-93b4-eefc8f2e33bd.png)

### Challenges and Difficulties Encounter

#### When working with any large data set, it can always be a challenge to narrow down your raw data to allow yourself to be working with data that is most pertinent to your analysis. Our Kickstarter campaign raw data has over 4,000 campaigns for projects in a range of different categories. The first challenge was narrowing down and filtering our raw data to campaigns most similar to Louise's project. A second challenge was the small sample size for some goal ranges in the Outcomes Based on Goals chart. We had fewer and fewer data points as the goal range increased, with hundreds of campaigns for the first few ranges and less than ten campaigns for some of the higher goal ranges. Because of this, we have more confidence in the results for success rate of the first few goal ranges since the sample size is larger.

## Results

- One conclusion I drew from the Outcomes Based on Launch Date is that campaigns launched in May, June, and July had a higher number of successful campiagns than any other month. At the same time, they had a similar number of failed campaigns as other months so the success rate percenatge was also higher in those months in addition to the absolute number of successful campaigns. This would have me suggest to Louise that she launch her campaign in one of those months. A second conclusion I drew from the Outcomes Based on Launch Date is the month of December had almost the same number of successful and failed campaigns. This would have me suggest to Louise she avoid launching her campign in December, as it has the worst success rate percenatge of any month.
- The conclusion I made about the Outcomes Based on Goals is that it appears best to keep the campaign goal less than $5,000. There is a negative correlation between the campaign goal and success rate as the success rate falls as campaign goal increases. The exception to this trend spotted in the line chart is the high success rate in the 35000 to 39999 and 40000 to 44999 ranges but considering the very samll sample sizes of 6 and 3 respectively, I am considering these results to be outliers. This would led me to suggest to Louise she keep her campaign goal under $5,000.
- One limitation of the dataset could be the small sample size of campaigns with higher campaign goals mentioned above. With such small sample sizes for campaigns with goals of 25000 or more, it is difficult to have high confidence in the conclusions for the success rate in those ranges. 
- Some other tables or graphs we could look at that I think would be helpful is Outcomes Based on Campiagn Duration. If we took the difference between Campaign Deadline and Campign Launch Date, we'd know how long the campign lasted for. We could then make a table for duration ranges and the outcomes of campaigns based on duration. Plotting that in a line chart could provide Louise and us with some good insights into what an ideal campiagn duration to increase the probability for success.
