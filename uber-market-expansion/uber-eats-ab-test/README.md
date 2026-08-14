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

The experiment was evaluated using click-through rate and statistical significance to determine whether one page design performed better than the other.

The final decision should not be based on click-through rate alone. Any improvement should also avoid negatively affecting cancellation, dissatisfaction, or abandonment rates.

## Business Recommendation

Only implement the higher-performing page design if the difference is statistically significant and the guardrail metrics remain stable.

If the results are not statistically significant, additional testing or a larger sample may be needed before making a final decision.

## Skills Demonstrated

A/B Testing, Hypothesis Testing, P-Values, Excel, Statistical Analysis, Data Interpretation, Critical Thinking, Business Recommendations

## Course Context

This case study was developed from coursework completed as part of my Business Analytics studies.

The original course materials are not included in this repository. This summary reflects my own analysis, findings, and recommendations.
