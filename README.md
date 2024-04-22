# A/B testing 

A/B testing involves methodically conducting experiments and assessing the statistical significance of their results. These experiments aim to enhance websites or other user interfaces by measuring business-relevant metrics like click-through rates in online stores. However, these methods are equally applicable for determining the statistical significance of any measurement.

The steps that should be followed in A/B testing:

1. Establishing a null hypothesis: This suggests that altering a specific explanatory variable has no impact on a given response variable.
2. Formulating an alternative hypothesis: This proposes that the null hypothesis is invalid.
3. Determining a significance level: This indicates the probability of rejecting the null hypothesis, even if it's true, based on the experiment's results.
4. Calculate the necessary sample size based on the desired significance level and the probability distribution of the response variable.
5. Conducting the experiment and gathering data.
6. Computing the test statistic.
7. Calculating and interpreting the p-value concerning the established significance level.


## Context
On the Montana State University (MSU) Library website there is a search bar and three big items: “Find”, “Request” and “Interact”, all of which need to have similar click-through rates (CTR).
 ![website_montana](https://github.com/HeleneRebelo/A-B-Test/blob/main/images/website_montana.png)

 Everyone has access to important information and services, however, Website Analytics shows that the "Interact" button almost doesn't have interaction, as we can see in the image below:
 ![interactions_website](https://github.com/HeleneRebelo/A-B-Test/blob/main/images/interactions_website.png)
