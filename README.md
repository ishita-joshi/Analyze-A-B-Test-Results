# Analyze-A-B-Test-Results
I worked on this project to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Your goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.
Through this dataset we tried to understand whether the company should implement a new page or keep the old page with following:

Probability based approach A/B test Regression approach

Probability based approach: Observation-

The probability of an individual receiving the new page is 0.5001
Meaning, there is almost the same chance that an individual received the old page
A/B test

In A/B test we set up our hypothesis to test if new page results in better conversion or not
We simulated our user groups with respect to conversions
We found the p_value to be 0.8191 almost 0.90
With such a p-value, we failed to reject null hypothesis
By using the built-in stats.proportions_ztest we computed z-score and p-value which confirmed our earlier p-value and failure to reject null hypothesis
Regression Approach:

I looked at exploring two possible outcomes. Whether new page is better or not.
With logistic regression results, I again encountered same z-score as well as p-value of 0.190, corresponding two-tailed case
By further adding and considering geographic location of the users, I tried to find if any specific country had an impact on conversion.
The result gave a similar results and suggested that the countries have no impact on the conversion rate.
Points to consider

The duration of the experiment was short approx 21 days which is a relatively short period of time to run the A/B test.
Due to Change aversion effect, a group of users may give an unfair advantage to the older page
Similarly, due to Novelty effect, users may give an unfair advantage to the newer page
