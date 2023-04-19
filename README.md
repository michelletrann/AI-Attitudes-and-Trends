# README File for American AI Attitudes and Trends
---
A Data Visualization Project by Meher Wadhawan and Michelle Tran
|
Date: "April 18th, 2023"

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

What is the relationship between education level and perceptions of AI harms?
What is the relationship between gender, as an additional variable, education level and perceptions of AI harms?

---

## Methodology

1. We first developed our research question by looking at the available data and what interesting relationships we may want to investigate. 
2. We then cleaned and wrangled the data to suit the needs of our project, including the creation of new data frames and variables.
3. We decided that we would use a summary table, stacked bar plots and box plots to investigate the questions. 
4. We used the gtsummary package to create the summary table and the ggplot2 package to create the stacked bar plot and box plots for our visualization and analysis. 
5. The summary table provides important information regarding our selected variables and observations in the data set:  gender, education level, and two survey questions (Q1_9 and Q2_9). 
6. The stacked bar plot is used to visualize the variation in perceptions of AI harms seen in variables Q1_9 (Likelihood of AI Harms) and Q2_9 (Severity of AI Harms), along different education levels. 
7. The box plots are additionally used to map gender onto this variation, allowing us to see the distribution of responses grouped by education levels.
8. We then conducted an analysis based on the visualizations we made to observe any relationships between our chosen variables. 

--- 

## Findings

In response to the likelihood of AI Harms, respondents generally perceive lower risk of AI harms within 10 years as education level increased. With regards to the gender differences for the first prompt on the likelihood of AI harms, female respondents had a tighter range of neutral to somewhat unlikely answers than male respondents, but both genders found AI harms to be more unlikely as education levels increased.

In response to the severity of AI Harms, respondents perceived the magnitude of harms more moderately as education increased, with lower levels of extreme opinions. Male respondents favored a more extreme disposition on the severity of AI harms in lower education levels (no HS, HS, some college, two-year college), dropping to a more moderate disposition as education levels increased to 4-year college and post-grad. Conversely, female respondents remained consistently moderate despite education levels with a slight favor toward a moderate to severe disposition as their education levels increased.

In short, as education levels increase, the perceived risk and severity of AI harms generally decreased across both genders. However, female respondents remain more consistent in their perceived risk of the likelihood of AI harms and severity. Males with lower education levels perceived greater severity in AI harms, followed by a more moderate disposition as education levels increased.

---

## Limitations

Firstly, this data set had very limited survey prompts relating to artificial intelligence. The authors acknowledge that they were aiming for breadth over depth of the survey. In the future, it would be useful to conduct surveys that have more specific scenarios for AI use cases in order for respondents to truly understand the content of AI applications, and thus their potential harms. 

We intended to measure age and race as variables as well initially. However, we opted against age as the relationship to education felt more relevant to measure correlations for perceptions of AI and we could not see any interesting observations from our preliminary data analysis. We also opted against race as a variable since the sample was not equally representative from different racial groups. This made it hard to observe any clear relationships and felt futile to draw findings from. A larger sample size and more racial variation of respondents to represent the groups in equal numbers, rather than their proportion as seen in the population, may help with this. 

We also want to acknowledge that our data was limited to the binary classifications of male and female, which may not be representative of respondents whose gender identity was not provided as an option.
