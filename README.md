
title: "README File for American Attitudes Towards Artificial Intelligence"
subtitle: A Data Visualization Project
date: "April 18th, 2023"
authors: "By Meher Wadhawan & Michelle Tran"
---

## Executive Summary

Rising ethical concerns in data governance and artificial intelligence (AI) may differ across populations with varying degrees of trust. Given the unprecedented capabilities of artificial intelligence, the role of public opinion may greatly shape AI’s implementation to include future regulation and critical decision-making processes. Discerning these attitudes is valuable in capturing the current culture of technology development and understanding. 

Our team used a 2019 dataset assembled by Baobao Zhang and Allan Dafao that collected a series of survey responses to questionnaires regarding artificial intelligence, ranging from questions about its governance to its potential harms. We focus on examining the relationship between education levels and survey responses. We then measure the differences in these responses by gender. 

The two survey response questions are as follows:

Q1_9 - The Likelihood of a Global Event in the Next 10 Years - Harmful consequences of AI 
Q2_9 - The Size of Negative Impact Should an Event Occur - Harmful consequences of AI 

---

## Dataset

Zhang, Baobao and Allan Dafoe. "Artificial Intelligence: American Attitudes and Trends." Oxford, UK: Center for the Governance of AI, Future of Humanity Institute, University of Oxford, 2019.

The source Rmd can be found here:
ai_public_opinion_us_2018_report_dataverse.Rmd - File for "Artificial Intelligence: American Attitudes and Trends" (January 2019) Report Replication Files

---

## Research Question

How does education level impact perceptions of AI harms?
How do male and female respondents differentiate in their perceptions of AI harms?
Do gendered responses change by education level?

---

## Methodology

The ggplot2 package is used to create the box plots, and the gtsummary package is used to create the summary table. The box plots are used to visualize the distribution of two variables, Q1_9 (Likelihood of AI Harms) and Q2_9 (Severity of AI Harms), while the summary table provides an overview of the gender, education level, and two survey questions (Q1_9 and Q2_9).

Given the explanatory dataset, utilizing box plots allow us to see the distribution of responses classified by education levels. For the purpose of our project, this was effective in visualizing variable tendencies specifically for gender. 

--- 

## Findings

In response to the likelihood of AI Harms, respondents perceive lower risk of AI harms within 10 years as education level increases.

Respondents are less extreme about the severity of AI harms as education level increases. Therefore, they are more moderate in their disposition. 

Female respondents have a tighter range of neutral-somewhat unlikely answers than male respondents, but both genders found AI harms to be more unlikely as education levels increased.

Male respondents favored a more severe disposition in lower education levels (no HS, HS, some college, two-year college), dropping to a more moderate disposition as education levels increased to 4-year college and post-grad. Conversely, female respondents remained consistently moderate despite education levels with a slight favor toward a moderate-severe disposition as their education levels increased.

In short, as education levels increase, the perceived risk and severity of AI harms slightly decreases across both genders. However, female respondents remain more consistent in their perceived risk of AI harms and severity. Males with lower education levels perceived greater severity in AI harms, declining towards a moderate disposition as education levels increase.
