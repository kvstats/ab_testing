# A/B Testing
Self-study to learn about the process of A/B testing.

A/B testing is a user experience research methodology that consists of a randomized experiment that usually involves two variants (A and B). The statistical method of two-sample hypothesis testing is typically used when conducting A/B tests.

A/B testing is a way to compare multiple versions of a single variable, for example by testing a subject's response to variant A against variant B, and determining which of the variants is more effective. This is particularly useful in the field of social media as it allows for understanding of user engagement and satisfaction of online features like a new feature or product.

# Data Description
The data for this analysis contains the results of an A/B test on 2 different designs of a website page (old_page vs. new_page). 

The dataset is available on [Kaggle](https://www.kaggle.com/datasets/zhangluyuan/ab-testing?select=ab_data.csv). 

# Scenario
The setup for this analysis is described in the scenario below:
> Suppose that a company has updated the "Click Here to Sign-up" button for their website in an attempt to make it easier for users to see the button and sign-up for their newsletter. The current sign-up or conversion rate is about 12% on average throughout the year. With this new button, the team would like to see an increase of 3% before rolling out the feature to all users.

Thus, the task at hand is to conduct an analysis to answer the following question:

> Does the new design perform differently than the old design? If so, does it perform better or worse?

To do this, we suggest running an A/B test on a random subset of the users to examine both a two-tailed and a one-tailed hypothesis test.

## Rendered Notebook
View the rendered notebook on [nbviewer](https://nbviewer.org/github/kvstats/ab_testing/blob/main/code/ab_test.ipynb).
