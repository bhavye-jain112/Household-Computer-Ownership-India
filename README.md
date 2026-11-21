# Household-Computer-Ownership-India
Econometric analysis of the socioeconomic, infrastructural, and caste-based determinants of household computer ownership in India using IHDS-II (2011–12) data.


**Dataset:** [ICPSR Study No. 36151 — IHDS-II (2011–12)](https://www.icpsr.umich.edu/web/DSDR/studies/36151)

---

## Overview
This repository contains the empirical analysis and term paper investigating the socioeconomic, infrastructural, and demographic drivers of household computer ownership in India across **41,269 households**. Using a **Binary Logit regression model with District Fixed Effects**, the study examines how income, education, electricity access, urban residence, caste identity, and household head gender shape digital access.

## Key Findings
* **Model Fit:** Log Likelihood = `-6900.82` | McFadden Pseudo R^2 = `0.3414` | AIC = `13829.65`
* **Income:** Strong positive gradient across income quintiles; households in Q1–Q4 are significantly less likely to own a computer than those in the richest quintile (Q5).
* **Education:** Each additional year of education of the household head increases the probability of computer ownership by **1.42 percentage points** (p < 0.001).
* **Infrastructure & Location:** Access to electricity increases ownership probability by **11.32 percentage points**, while urban residence adds **4.73 percentage points** (p < 0.001).
* **Caste Disparities:** Relative to General caste households, OBC and Scheduled Caste (SC) households face statistically significant ownership deficits of **2.0** and **3.2 percentage points**, respectively, even after controlling for income, education, and district fixed effects.
* **Gender:** The gender of the household head has no statistically significant effect (p = 0.427) once socioeconomic and structural controls are included.
