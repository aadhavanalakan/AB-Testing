# AB-Testing in a Digital Product

## Problem Definition

Performing A/B testing on a frictional app (Kittengram). Kittengram is an app where users can share their cat pictures and users can only comment or like about other user’s pictures. The business model is based on Ads. The company is still functioning on investors money because they are not making enough money on their own. The ads are not relevant to the user’s interest. They are not affecting the user engagement in a good way

The goal is to determine whether new feature (sponsored post) is liked by the users and the company’s revenue increases.

## Key Performance Indicators (KPIs)
### Daily Active Users (DAU)
To check if the users are coming back to the app on a daily basis.

### Click-Through Rate (CTR)
Checking the CTR between the new type of sponsored posts vs. the old type of sponsored posts that were not tailored to our user base.

## Learnings from this project
What is an A/B test and its desin analysis?

How to define metrics and KPIs?

How long & how many users are required to run the test?

When to stop an A/B test?

How to determine P-value and its significane?

Data Tracking

A/B test design 

How to present results

## Conclusion
H1 - with the introduction of the tailored ads, users are more likely to click on the ads, therefore the CTR difference  > 5.5% per user.

H0 - Tailored ads will have no effect on the user engagement with the ads, and CTR difference < 5.5% per user.

We observed a mean ctr of 33 ad-clicks per user in the control group whereas in the test group we got 36.24 ad-clicks - an increase of 9.81% per user.

The user activity also saw a massive 42.24% increase. This might be good news for the business, but we should calculate user retention since high user activity rates may often result in user burnout.

We can conclude that the above A/B test has been successful because we rejected the Null hypothesis since the difference in CTR between the groups was well above 5.5%.
