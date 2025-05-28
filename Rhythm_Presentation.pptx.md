---
title: "Student Mental Health During Online Learning"
author: "Ibtesam Ifaz"
format: 
  pptx:
    slide-level: 2
    transition: fade
    keep-md: true
execute:
  echo: true
---




## Title Slide {.animated.zoomIn}

# Student Mental Health During Online Learning
### Ibtesam Ifaz  
Exploring Behavioral Correlates of Wellbeing

---

## Problem Introduction {.animated.slideInLeft}

- Mental health concerns among students have escalated during the shift to online learning.
- Increased screen time, reduced social interaction, and academic pressures are key stressors.
- This analysis explores how digital behavior and lifestyle choices impact **student mental well-being**.

---

## Dataset Overview {.animated.slideInRight}

- Dataset contains **1000 observations** from students across high schools and universities.
- Captures behavioral and psychological metrics including:
  - `Phone Usage (hours)`
  - `Sleep Duration`
  - `Stress Level`, `Anxiety Level`, `Depression Level`
  - Demographics like `Gender`, `Year of Study`, and `Institution Type`


library(readr)
library(dplyr)
df <- read_csv("Student Mental Health Analysis During Online Learning.csv")
glimpse(df)
