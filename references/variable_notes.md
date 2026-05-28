# Variable Notes

## Research Question

Is the proportion of current cigarette use different between male and female students?

---

# Group Variable

## Variable Name
WhatIsYourSex

## Group Definition

- 1 = Female
- 2 = Male

The variable was recoded into a categorical variable named `sex`.

---

# Response Variable

## Variable Name
CurrentCigaretteUse

## Original Coding

- 1 = Did not use cigarettes during the past 30 days
- 2–7 = Used cigarettes during the past 30 days

## Recoding Rule

The variable was recoded into a binary variable named `current_smoker`.

- 0 = no current cigarette use (original code 1)
- 1 = current cigarette use (original codes 2–7)

This recoding follows the required Project Cycle 3 instructions.

---

# Method Choice

The response variable (`current_smoker`) is binary, and the research question compares smoking proportions between two independent groups (male and female students).

Therefore, a two-proportion z-test was selected as the appropriate statistical method.

A 95% confidence interval for the difference in proportions was also calculated.

---

# Assumptions Considered

The following assumptions were considered:

- Male and female students were treated as independent groups.
- The response variable was binary.
- The sample sizes in both groups were sufficiently large for two-proportion inference.
- Missing observations were removed before analysis.

---

# Final Statistical Conclusion

The analysis showed that male students had a significantly higher proportion of current cigarette use compared with female students.

The estimated difference in smoking proportions was approximately 4.3 percentage points.

The two-proportion z-test produced a statistically significant result (p < 0.001).

The 95% confidence interval for the difference in proportions was approximately (0.029, 0.056).
