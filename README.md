# Coupon Acceptance Prediction

## Overview:
In this project, we aim to answer the question, “Will a customer accept the coupon?” The goal is to utilize visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not. 

## Data:
The data for this project is sourced from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey presents various driving scenarios, detailing destination, current time, weather, passenger, etc., and then asks respondents whether they would accept the coupon if they were the driver. Responses indicating immediate acceptance or acceptance before the coupon expires are labeled as “Y = 1”, while responses indicating refusal are labeled as “Y = 0”. The coupons offered cover five different types: less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).

## Contents:
- `README.md`: Summary of findings and link to notebook.
- `project_source.ipynb`: Jupyter notebook containing detailed analysis with appropriately formatted headings and text.

## Summary of Findings:
- We can hypothesize that drivers who accepted the bar coupons are more likely to be younger individuals who frequent bars more frequently, have passengers who are not children, and have occupations other than farming, fishing, or forestry. Additionally, they are less likely to be widowed and more likely to have lower incomes. Overall, the data suggests that younger individuals who have more social activities and lower financial resources are more inclined to accept bar coupons.
- Also, we can hypothesize that drivers who accepted the luxury restaurant coupons are likely to be individuals with occupations in healthcare, construction, office administration, healthcare support, or production occupations. They may also belong to the income range of $25,000 - $37,500, be frequent visitors of luxury restaurants, and possibly economic restaurants as well. They may be more inclined to accept coupons on warmer days, and if they are traveling with a partner, they are more likely to accept coupons. 
- Overall, these drivers may have a higher disposable income, enjoy dining out frequently, and be influenced by weather conditions and social factors such as traveling with a partner.
## Notebook Link:
<a href="project_source.ipynb">[Link to Jupyter Notebook]</a>
