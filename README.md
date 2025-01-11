# Print-Head Durability Analysis

This project estimates the **mean durability** of print-heads (*measured in millions of characters* printed before failure) using confidence intervals. 
> **Destructive sampling** constraints necessitate statistical methods for accurate quality assessment.

## Analysis
1. **99% Confidence Interval (Sample Standard Deviation)**:
   - Calculated using the ***t-distribution*** for small sample sizes.

2. **99% Confidence Interval (Known Population Standard Deviation)**:
   - Calculated assuming a population standard deviation of `0.2` million characters.

## Outcome
The analysis provides statistically robust confidence intervals for **mean durability**, supporting data-driven quality control decisions.

## The tools you used are:
-NumPy

-Pandas

-SciPy
