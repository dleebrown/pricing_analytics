# Pricing A/B Testing - Donald Lee-Brown
Originally a mock data challenge completed as part of the 2018B NYC [Insight Data Science Fellows Program](https://www.insightdatascience.com/).

The goal of this project is to generate insights from an A/B test that presented a random subset (the test group) of users with a higher price for a software product. The responses of these customers, as well as those of a control group shown the normal software price, were recorded along with some other information over a period of three months.

Key questions addressed by this project:

* What is the impact on conversion rate due to increasing the price of the software?
* What is the impact on overall revenue due to increasing the price of the software?
* Can A/B testing be made more efficient in the future by estimating how much data is needed to detect test/control differences at a significant level?
* What are some other insights from the data that can be used to increase customer conversion rate?

# Conclusions
To briefly summarize, we conducted a followup analysis of an A/B test designed to determine the effects of increasing the price of a software product. Data was collected by randomly presenting users with the normal software price (the control group) and a 50% increased price (the test group) over a period of 3 months.

Key Insights
* Effects of increasing the price on conversion rate. As expected, increasing the software price decreased conversion rate over the test period by 22% (>99.99% confidence). If the higher price is adopted, it may be worth conducting periodic longer-term conversion rate monitoring to ensure that, e.g., increased price dissatisfaction and a corresponding drop in referrals doesn't result in steadily declining sales over the long term.

* Effects of increasing the price on total revenue. While conversion rate decreased by 22%, net revenue per test user actually increased by 18% relative to the control group (>99.99 confidence), due to the higher price of the software.

* Retaining customers under an increase in price. Considering the test group, analysis shows with high confidence (>95%) that the fraction of conversions coming from Google ads increased while those coming from Facebook ads decreased. If the higher pricing is adopted, incentive programs can be designed to maintain the current Facebook conversion rate and/or Google ads can be increased to reach additional users.

* A/B testing efficiency. If the primary goal was to address the two above questions, then analysis shows that a high level of confidence (99.7%) could have been reached with approximately 10% of the total data. However, the customer retention analysis above was only made possible by the large sample we collected. My recommendation is to first define the goals of the A/B test and a level of significance desired, then design the test to meet those objectives.
