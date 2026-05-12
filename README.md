
# Eniac A/B Test Analysis

## Overview
This project analyzes an A/B test conducted on Eniac’s website to evaluate different button designs.

## Variants Tested
- White "SHOP NOW"
- Red "SHOP NOW"
- White "SEE DEALS"
- Red "SEE DEALS"

## Objective
To determine which version leads to higher click-through rate (CTR).

## Results
- Best performing version: **Version C (White "SEE DEALS")**
- White buttons outperformed red buttons
- "SEE DEALS" performed better than "SHOP NOW"

## Statistical Test
- Chi-square test p-value: 6.19e-48
- Result: statistically significant

## Conclusion
Version C is the best-performing variant and should be implemented.

## Tools Used
- Python (pandas, matplotlib, scipy)
- Google Colab

## Business Impact
Improving the button design can increase user engagement significantly.  
Even small improvements in CTR at scale can lead to higher conversions and revenue.

## Recommendation
Implement Version C (White "SEE DEALS") as the default button design.

##  What I Learned
- How to design and analyze an A/B test
- How to use chi-square testing for categorical data
- How to interpret statistical significance in business decisions
