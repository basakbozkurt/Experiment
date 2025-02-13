# Power Analysis for Sample Size Determination

## Overview  
This repository contains a power analysis examining the relationship between **statistical power, sample size, and effect size**. The objective is to determine an appropriate sample size for a study, ensuring sufficient power to detect meaningful effects while maintaining feasibility.

## Power Analysis Summary  
The analysis considers three effect sizes:

- **Small (0.10, blue dashed line)** – Requires a very large sample size to reach acceptable power levels.  
- **Moderate (0.29, green solid line)** – Reaches **80% power at around 800 participants.**
- **Large (0.35, orange dashed line)** – Achieves high power with a smaller sample size.  

A **red dashed line at 0.80 power** represents the standard benchmark for adequate study design.

### Power Analysis Plot  
Below is the power analysis visualisation:

![Power Analysis Plot](fig1.png)

## Why Choose an Effect Size of 0.29?  
The effect size of **0.29** was selected based on empirical evidence from prior research. Specifically, I relied on a **meta-analysis of 30 studies on fact-checking interventions**, which reported an **average effect size of d = 0.29 (95% CI: [0.23, 0.36])** (Walter et al., 2020). This suggests that 0.29 is a reasonable estimate for the expected effect in similar studies.  

Additionally, as shown in the power analysis plot above, an effect size of 0.29 reaches the **0.80 power threshold at approximately 850 participants**, making it a **statistically sound yet feasible** choice for study design. This balance ensures the study is adequately powered while avoiding unnecessarily large samples.

## Files in This Repository  

| File Name       | Description |
|----------------|-------------|
| **`figure.png`** | Power analysis plot showing the relationship between sample size and power for different effect sizes. |
| **`PowerAnalysis.R`** | Script used to generate the power analysis. |
| **`README.md`** | This document. |


