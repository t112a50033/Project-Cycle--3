# Project Cycle 3
## Gender and Current Cigarette Use

---

### Group Information

| Item | Information |
|--------|--------|
| Group Number | 4 |
| Member 1 | 王靖慈 112A50033 |
| Member 2 | 王薪崴 113370231 |
| Dataset | YRBS_2007.csv |

---

### Research Question

> Is the proportion of current cigarette use different between male and female students?

---

### Variables

#### Group Variable

| Variable | Description |
|-----------|------------|
| WhatIsYourSex | Student sex (Male vs Female) |

| Code | Group |
|--------|--------|
| 1 | Male |
| 2 | Female |

#### Response Variable

| Variable | Description |
|-----------|------------|
| CurrentCigaretteUse | Current cigarette use status |

---

### Recoding Rules

According to the Cycle 3 instructions:

| Original Code | Recoded Value |
|--------------|--------------|
| 1 | 0 (Non-current smoker) |
| 2–7 | 1 (Current smoker) |

Binary Variable Definition:

- 1 = Current cigarette user
- 0 = Non-current cigarette user

---

### Statistical Method

| Item | Description |
|--------|--------|
| Method | Two-Proportion z-Test |
| Confidence Level | 95% |
| Significance Level | α = 0.05 |
| Response Variable Type | Binary |
| Number of Groups | 2 Independent Groups |

---

### Hypotheses

$$
H_0 : p_{male} - p_{female} = 0
$$

$$
H_a : p_{male} - p_{female} \neq 0
$$

where

- $p_{male}$ = true proportion of male students who currently use cigarettes
- $p_{female}$ = true proportion of female students who currently use cigarettes

---

### Project Structure

```text
project-cycle-3/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│
├── outputs/
│   ├── figures/
│   ├── tables/
│   └── summary/
│
├── references/
│
├── report/
│
└── README.md
```

---

### Conclusion

This project examines whether the proportion of current cigarette use differs between male and female students using the YRBS 2007 dataset.

The analysis uses a two-proportion z-test to compare smoking proportions between the two groups. The results are interpreted using a 95% confidence interval and a significance level of 0.05.

Because the YRBS dataset is observational survey data, the findings indicate an association rather than a causal relationship.

---

### References

- Youth Risk Behavior Survey (YRBS) 2007
- Project Cycle 3 Instruction