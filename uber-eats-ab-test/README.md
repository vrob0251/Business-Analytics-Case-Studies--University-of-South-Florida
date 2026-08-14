# Uber Eats A/B Testing Analysis

## Business Problem

Uber Eats wanted to determine whether changing the amount of detail shown on an order page could improve the rate at which customers add food items to their cart.

## Objective

Compare two versions of the order page and determine whether one version produced a statistically meaningful improvement in click-through rate.

## Primary Metric

Click-Through Rate from the order page to adding a food item to the cart.

## Analysis Approach

- Compared Treatment A and Treatment B
- Calculated click-through rates
- Evaluated the p-value
- Compared the p-value against the Type I error threshold
- Determined whether to accept or reject the null hypothesis
- Considered possible confounding variables

## Guardrail Metrics

- Cancellation rate
- Customer dissatisfaction
- Abandonment rate

## Key Finding

Treatment A had a click-through rate of 50.00%, while Treatment B had a click-through rate of 52.13%.

The p-value was used to determine whether the difference between the two treatments was statistically significant.

The final decision should not be based on click-through rate alone. Any improvement should also avoid negatively affecting cancellation rate, customer dissatisfaction, or abandonment rate.

## Decision

If the p-value is greater than 0.05, fail to reject the null hypothesis.

If the p-value is less than 0.05, reject the null hypothesis.

## Business Recommendation

Do not implement a new page design based only on a small difference in click-through rate.

The higher-performing treatment should only be implemented if the difference is statistically significant and the guardrail metrics remain stable.

If the results are not statistically significant, additional testing or a larger sample may be needed before making a final decision.

## Analysis File

The Excel workbook used for the experiment analysis is included in this folder and contains the treatment data, click-through rates, hypothesis setup, p-value calculation, and final decision.

## Skills Demonstrated

A/B Testing, Hypothesis Testing, P-Values, Excel, Statistical Analysis, Data Interpretation, Critical Thinking, Business Recommendations

## Course Context

This case study was developed from coursework completed as part of my Business Analytics studies.

The original course materials are not included in this repository. This summary reflects my own analysis, findings, and recommendations.
