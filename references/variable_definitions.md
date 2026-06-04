# Variable Definitions

Project Cycle 3 research question:  
**Is the proportion of current cigarette use different between male and female students?**

## 1. Group Variable

| Item | Description |
|---|---|
| Variable name | `WhatIsYourSex` |
| Role in analysis | Group variable |
| Type | Categorical binary variable |
| Original coding | `1 = Female`, `2 = Male` |
| Cleaned / recoded variable | `Sex_group` or `Sex_label` |
| Final groups | Female students and male students |
| Purpose | To divide students into two independent groups for comparison |

### Group Definition

- **Female group:** students with `WhatIsYourSex = 1`
- **Male group:** students with `WhatIsYourSex = 2`

The two groups are compared to determine whether their current cigarette use proportions are different.

## 2. Response Variable

| Item | Description |
|---|---|
| Variable name | `CurrentCigaretteUse` |
| Role in analysis | Response variable |
| Type | Categorical variable recoded into binary variable |
| Original coding | `1 = did not currently use cigarettes`; `2–7 = different levels of current cigarette use` |
| Cleaned / recoded variable | `CurrentCigaretteUse_binary` |
| Final coding | `1 = current cigarette user`, `0 = non-current cigarette user` |
| Purpose | To measure whether a student currently uses cigarettes |

### Response Definition

- **Success / Yes:** `CurrentCigaretteUse_binary = 1`
- **Failure / No:** `CurrentCigaretteUse_binary = 0`

In this project, "success" means the student is classified as a current cigarette user.

## 3. Analysis Definition

| Item | Description |
|---|---|
| Research question | Is the proportion of current cigarette use different between male and female students? |
| Group variable | `WhatIsYourSex` |
| Response variable | `CurrentCigaretteUse_binary` |
| Statistical method | Two-proportion z-test |
| Confidence interval | Confidence interval for the difference in proportions |
| Difference measured | Male smoking proportion minus female smoking proportion |
| Significance level | α = 0.05 |

## 4. Hypotheses

Let:

- $p_{male}$ = true proportion of male students who currently use cigarettes
- $p_{female}$ = true proportion of female students who currently use cigarettes

### Null Hypothesis

$$
H_0: p_{male} - p_{female} = 0
$$

There is no difference in the current cigarette use proportion between male and female students.

### Alternative Hypothesis

$$
H_a: p_{male} - p_{female} \neq 0
$$

There is a difference in the current cigarette use proportion between male and female students.

## 5. Interpretation Direction

- If $\hat{p}_{male} - \hat{p}_{female} > 0$, male students have a higher current cigarette use proportion.

- If $\hat{p}_{male} - \hat{p}_{female} < 0$, female students have a higher current cigarette use proportion.

- If the p-value is less than 0.05, the difference is statistically significant.

- If the p-value is greater than or equal to 0.05, there is not sufficient evidence of a significant difference.

## 6. Method Choice

The response variable (CurrentCigaretteUse_binary) is a binary variable representing whether a student currently uses cigarettes.

The group variable (WhatIsYourSex) contains two independent groups: female students and male students.

Because the analysis compares the proportions of a binary outcome between two independent groups, the appropriate statistical method is a two-proportion z-test.

In addition, a 95% confidence interval for the difference in proportions is calculated to estimate the magnitude of the group difference.

## 7. Assumptions Considered

The following assumptions were considered before conducting the two-proportion z-test:

1. Independent Groups
   - Female and male students are treated as independent groups.

2. Binary Response Variable
   - Current cigarette use was recoded into a binary variable:
     - 1 = current cigarette user
     - 0 = non-current cigarette user

3. Sufficient Sample Size
   - Both groups contain large sample sizes and sufficient numbers of smokers and non-smokers.

4. Valid Recoding
   - Current cigarette use was recoded according to the Cycle 3 instructions:
     - codes 2–7 = current cigarette user
     - code 1 = non-current cigarette user

Based on these considerations, the assumptions for two-proportion inference were considered reasonable.