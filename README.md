
# Abigail Ray || ECON 3916 Lab: Job Training Program Analysis

## Overview
This project analyzes the National Supported Work (NSW) job training program by comparing earnings between treatment and control groups. It uses hypothesis testing, effect sizes, statistical power, subgroup analysis, and multiple-comparison corrections.

## Objectives
- Compare average earnings between treatment and control groups.
- Conduct a Welch two-sample t-test.
- Calculate Cohen's d and evaluate statistical power.
- Analyze program outcomes across demographic subgroups.
- Apply Bonferroni and Benjamini–Hochberg corrections.
- Interpret statistical significance and the risk of false positives.

## Methodology
1. Calculate descriptive statistics for treatment and control groups.
2. Conduct a Welch t-test to test for differences in average earnings.
3. Calculate the effect size and examine statistical power.
4. Conduct hypothesis tests for five demographic subgroups.
5. Adjust subgroup p-values for multiple comparisons.
6. Interpret the results and discuss limitations.

## Key Results

### Overall Earnings
- Treatment group sample size: 185
- Control group sample size: 260
- Treatment group mean earnings: $6,349.14
- Control group mean earnings: $4,554.80
- Difference in means: $1,794.34
- Welch t-statistic: 2.6741
- p-value: 0.0079
- Cohen's d: 0.2727

The overall earnings difference is statistically significant at the 5% level. The estimated effect size is small.

### Subgroup Analysis
Before correcting for multiple comparisons, two subgroup tests were statistically significant:

- Black participants: difference of $2,029; p-value = 0.0073
- High school diploma or more: difference of $3,192; p-value = 0.0302

### Multiple-Comparison Corrections
After applying both Bonferroni and Benjamini–Hochberg corrections, only the Black-participant subgroup remained statistically significant.

Bonferroni controls the family-wise error rate, while Benjamini–Hochberg controls the false discovery rate.

## Interpretation
The results suggest that average earnings were higher in the treatment group. However, subgroup findings require caution because testing multiple hypotheses increases the risk of false-positive results.

Only the Black-participant subgroup remained statistically significant after multiple-comparison corrections. Policy decisions should consider adjusted p-values, effect sizes, uncertainty, program costs, and whether the findings can be replicated.

## Limitations
- Statistical significance does not necessarily imply practical importance.
- Subgroup sample sizes vary, affecting statistical power.
- Multiple subgroup tests increase the risk of false positives.
- The subgroups overlap and should not be treated as independent.
- These results alone are not sufficient to determine whether the program should be targeted to a specific demographic group.

## Reproducibility
Run the lab notebook from beginning to end to reproduce the descriptive statistics, hypothesis tests, power calculations, subgroup analysis, and multiple-comparison corrections.
