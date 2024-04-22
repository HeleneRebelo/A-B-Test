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

 The University therefore wants to improve the Headline of the category Interact. An A/B Test is conducted and to measure the performance of each of the three big buttons it is used the click-through rate (CTR). The CRT measures the number of clicks on each item divided by the total number of website visits.

#### User survey

A survey was carried out with student users of the site, the feedback revealed that there is confusion and preferences regarding the terminologies used, here are some of the responses from three of the students:

Sophomore student:

“I didn’t know that ‘About’ was under Interact.'”
“Connect is too vague and too close to Interact.”
“Services is more accurate. Help is stronger.” 
In order of preferences of the choices, this student responded: Help, Services, Interact, Connect, Learn

Junior student:

“I am not a native English speaker, so I look for strong words. I look for help, so Help is the best, then Services too.”

Senior student:

“Help makes sense. When I’m in the library, and I think I need help, it would at least get me to click there to find out what sort of help there is.”
In order of preferences of the choices, this student responded: Help, Services, Connect, Interact, Learn

## Main Objective

1. Make the CTR similar across the three large items: “Find”, “Request” and “Interact” on the MSU website.

## Challenge - A/B Test

The website team has made the decision to conduct testing on four new variations in comparison to the original "Interact" button. These variants include Connect, Learn, Help, and Services. The primary objective of this experiment is to ascertain which version produces a superior click-through rate (CTR).

#### Specifications: 
duration 21 days
5 Versions for the headline: Interact / Connect / Learn / Help / Services
Measured primary KPI: CTR
second KPIs: drop off on category site / Homepage return rate
Minimum detectable effect: 20% in CTR

## Folder Structure

/A/B testing: Learning the steps of the A/B test

/Montana: Montana State University Case Study. Within this folder, there are the following subfolders:

/docs: This directory contains images of the website with its interactions when using the words: "Interact", Connect, Learn, Help, and Services.

/src: Inside this folder, you will find the Notebook with the codes.

