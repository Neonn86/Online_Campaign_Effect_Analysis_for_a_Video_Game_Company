# Online Campaign Effect Analysis for a Video Game Company
## Objective
The goal is to examine the effect of online community by evaluating its impact on **revenue, retention, and Customer Lifetime Value (CLV).**

## Structure
### 1. Evaluate the change in revenue
Using the **diff-in-diff model**, we found that joining the online community resulted in a statistically significant increase in spend of $29.02.

### 2. Estimate the customer churn
We use **logistic regression** to estimate the customer churn.

<img width="500" alt="Screen Shot 2022-03-26 at 3 39 26 PM" src="https://user-images.githubusercontent.com/98130185/160259296-f436e479-009f-4fca-b495-92994cc45471.png">

- For retention, using the **two-sample t-test**, we observe that joining the online community reduces the retention rate by 19%, which is statistically significant.
- For CLV, using the **two-sample t-test**, there is no statistically significant difference between join the campaign or not.

### 3. The effect of mode of customer acquisition
- Using two-sided t-test and two-sided F-test, we confirm that acquisition method's indepence to other predictors.

<img width="500" alt="Screen Shot 2022-03-26 at 4 35 42 PM" src="https://user-images.githubusercontent.com/98130185/160260541-4a06a07d-7d51-433a-b7b0-f54a887e9985.png">

After confirm the independence, form the new **logistic regression** and calculate the CLV again.

- Using **two-sample t-test** between the campaign and organic users, we observe no statistically significant difference.
## Conclusion
- Although the user spend increased by $29 in the short term, but joining the online community reduces the retention rate by 19%, which ultimately resulted in no significant difference in CLV among the joined users.

***In other words, customers who join the online community are willing to spend more in the short term but do not retain on the game in the long term. As a result, their aggregated value provided to the firm is not significantly different from the users who were not invited to the community.***

- The method of customer acquisition has no statistically significant impact on churn and also other predictors.

***In other words, since there are no significant differences between organic and inorganic users, the retention efforts need not be bifurcated based on method of acquisition.***
