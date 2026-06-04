# Project Cycle 3

## Smoking Behavior Analysis Using the YRBS 2007 Dataset

### Group Information

| Item         | Information                            |
| ------------ | -------------------------------------- |
| Group Number | 24                                      |
| Member 1     | 王靖慈  112A50033                         |
| Member 2     | 王薪崴  113370231                         |
| Dataset      | YRBS 2007 (Youth Risk Behavior Survey) |

---

## Project Overview

This project investigates smoking behavior among students using the YRBS 2007 dataset.

The project consists of one main inferential analysis and two extension analyses. The main analysis focuses on gender differences in current cigarette use, while the extensions explore behavioral characteristics of female smokers and behavioral trends across different smoking intensity levels.

---

## Main Analysis

### Gender and Current Cigarette Use

**Research Question**

Is the proportion of current cigarette use different between male and female students?

**Variables**

| Type              | Variable            |
| ----------------- | ------------------- |
| Group Variable    | WhatIsYourSex       |
| Response Variable | CurrentCigaretteUse |

**Method**

* Two-Proportion z-Test
* 95% Confidence Interval for Difference in Proportions

**Purpose**

To determine whether smoking prevalence differs significantly between male and female students.

---

## Extension 1

### Female Smoker Behavioral Profile

**Research Question**

Do female smokers and female non-smokers exhibit different health-risk behaviors?

**Groups**

* Female Smokers
* Female Non-Smokers

**Behavioral Variables Examined**

* Current Alcohol Use
* Marijuana Use
* Physical Fighting
* Sad or Hopeless Feeling
* Other selected risk behaviors

**Purpose**

To identify behavioral patterns associated with smoking among female students.

---

## Extension 2

### Smoking Intensity Trend Analysis Among Female Students

**Research Question**

As smoking intensity increases, do health-risk behaviors also increase?

**Groups**

* Non-Smoker
* Light Smoker
* Moderate Smoker
* Heavy Smoker

**Purpose**

To examine whether increasing levels of cigarette use are associated with higher levels of risk behaviors.

---

## Project Structure

```text
project-cycle-3/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── cycle3_gender_smoking.ipynb
│   ├── extension1_female_smoker_behavioral_profile.ipynb
│   └── extension2_smoking_intensity_trend_analysis.ipynb
│
├── outputs/
│   ├── figures/
│   ├── tables/
│   └── summary/
│
├── references/
│   ├── recoding_rules.md
│   └── variable_definitions.md
│
├── report/
│
└── README.md
```

---

## Statistical Methods

### Main Analysis

* Two-Proportion z-Test
* Confidence Interval for Difference in Proportions

### Extension Analyses

* Descriptive Statistics
* Group Comparison
* Trend Analysis
* Data Visualization

---

## Key Findings

### Main Analysis

Male students exhibited a higher prevalence of current cigarette use than female students.

### Extension 1

Female smokers generally showed higher levels of several health-risk behaviors compared with female non-smokers.

### Extension 2

Higher smoking intensity was associated with higher levels of multiple risk behaviors, suggesting a behavioral risk gradient among female students.

---

## Conclusion

The findings indicate that smoking behavior differs across demographic and behavioral groups within the YRBS 2007 dataset.

Gender is associated with differences in smoking prevalence, and among female students, smoking status and smoking intensity are related to broader patterns of health-risk behaviors.

These results provide a more comprehensive understanding of smoking-related behavioral profiles among adolescents.

---

## Notes

This project uses observational survey data from the YRBS 2007 dataset. Therefore, the analyses identify statistical associations rather than causal relationships.

---

## Presentation Video

Project presentation video:

[Watch the presentation video](https://ntutcc-my.sharepoint.com/:v:/g/personal/113370231_cc_ntut_edu_tw/IQBd6WrF7MwkQp_ugGQdDcgSAfY3GeQ0ez_C4YI-Pwt1LBg?e=KpkmIp)
