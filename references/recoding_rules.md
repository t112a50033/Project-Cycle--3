# Recoding Rules

Project Cycle 3 uses two-sample inference.  
Selected research question: **Is the proportion of current cigarette use different between male and female students?**

## 1. Group Variable: WhatIsYourSex

Original variable: `WhatIsYourSex`

| Original Code | Meaning | Recoded Variable | Recoded Value |
|---:|---|---|---:|
| 1 | Female | `Sex_group` | 0 |
| 2 | Male | `Sex_group` | 1 |

Notes:
- Only valid responses coded as `1` or `2` are kept.
- Missing values and invalid codes are removed.
- Female students are used as the comparison group.
- Male students are used as the exposed / main comparison group.

## 2. Response Variable: CurrentCigaretteUse

Original variable: `CurrentCigaretteUse`

According to the required Cycle 3 recoding rule, current cigarette use is recoded as a binary variable:

| Original Code | Meaning | Recoded Variable | Recoded Value |
|---:|---|---|---:|
| 1 | Did not currently use cigarettes | `CurrentCigaretteUse_binary` | 0 |
| 2–7 | Currently used cigarettes | `CurrentCigaretteUse_binary` | 1 |

Notes:
- `1` means success / yes / current cigarette user.
- `0` means failure / no / non-current cigarette user.
- Only valid responses coded from `1` to `7` are kept.
- Missing values and invalid codes are removed.

## 3. Final Cleaned Dataset Rule

The final analysis dataset keeps only observations that meet all of the following conditions:

1. `WhatIsYourSex` is valid: `1` or `2`.
2. `CurrentCigaretteUse` is valid: `1` to `7`.
3. Both variables are non-missing.

## 4. Method Connection

Because the response variable is binary and the group variable has two groups, the appropriate method is a **two-proportion z-test**.

The analysis compares:

$$
\hat{p}_{male} - \hat{p}_{female}
$$

where:

where:

- $\hat{p}_{male}$ = proportion of male students who currently use cigarettes
- $\hat{p}_{female}$ = proportion of female students who currently use cigarettes


