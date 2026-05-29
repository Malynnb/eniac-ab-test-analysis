# Eniac A/B Test Analysis

## Overview

This project analyzes an A/B test conducted on Eniac's website to determine which call-to-action (CTA) button design generates the highest click-through rate (CTR).

The analysis compares variations in button color and button text to identify the most effective design for increasing user engagement.

---

## Experiment Design

Four variants were tested:

| Variant | Button Color | CTA Text  |
| ------- | ------------ | --------- |
| A       | White        | SHOP NOW  |
| B       | Red          | SHOP NOW  |
| C       | White        | SEE DEALS |
| D       | Red          | SEE DEALS |

### Objective

Determine which button design maximizes click-through rate and whether observed differences are statistically significant.

---

## Methodology

1. Calculated click-through rates (CTR) for each variant.
2. Compared user engagement across all test groups.
3. Performed a Chi-Square test to evaluate statistical significance.
4. Identified the highest-performing variation.

---

## Results

| Metric                  | Result                    |
| ----------------------- | ------------------------- |
| Best Performing Variant | C (White "SEE DEALS")     |
| Best Button Color       | White                     |
| Best CTA Text           | SEE DEALS                 |
| Statistical Test        | Chi-Square                |
| P-Value                 | 6.19 × 10⁻⁴⁸              |
| Significance            | Statistically Significant |

---

## Key Findings

* White buttons outperformed red buttons.
* "SEE DEALS" generated higher engagement than "SHOP NOW".
* The differences between variants were statistically significant.
* Variant C achieved the highest click-through rate among all tested designs.

---

## Business Recommendation

Implement **Variant C (White "SEE DEALS")** as the default website button.

The results suggest that both visual design and wording influence user behavior, and optimizing these elements can improve engagement and downstream conversion performance.

---

## Tools

* Python
* Pandas
* SciPy
* Matplotlib
* Google Colab

---

## Skills Demonstrated

`A/B Testing` • `Hypothesis Testing` • `Chi-Square Analysis` • `Statistical Inference` • `Data Visualization` • `Business Analytics` • `Experiment Design`

---

## What I Learned

* Designing and evaluating A/B experiments
* Applying Chi-Square testing to categorical data
* Interpreting statistical significance in a business context
* Translating analytical results into actionable recommendations
