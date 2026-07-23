---
title: "Uncovering Hidden Patterns in ADHD: A Data-Driven Analysis of Unusual Behavioral Traits"
date: 2026-07-23
summary: "This project leverages the National Survey of Children's Health (NSCH) 2023-2024 dataset to uncover distinctive and unusual behavioral patterns associated with Attention-Deficit/Hyperactivity Disorder (ADHD) in children."
tags:
  - Data Analysis
  - Python
  - Healthcare
  - Statistical Analysis
  - Machine Learning
show_date: false
---

## Overview

This project leverages the National Survey of Children's Health (NSCH) 2023-2024 dataset to uncover distinctive and unusual behavioral patterns associated with Attention-Deficit/Hyperactivity Disorder (ADHD) in children. Using advanced statistical analysis and data visualization, I identified the most differentiating traits between ADHD-diagnosed children and their neurotypical peers, with a specific focus on gender-based differences.

## Dataset

*   **Source:** NSCH 2023-2024 via Kaggle
*   **Size:** 106,537 records with 1,000+ features
*   **Scope:** Nationally representative survey of children's health in the United States

## Key Findings

**Most Distinctive ADHD Traits Discovered:**

| Trait | ADHD Prevalence | Control Prevalence | Odds Ratio |
| :--- | :--- | :--- | :--- |
| Severe Memory Problems | 26.4% | 4.2% | 8.1x |
| Repeated Grade in School | 28.7% | 5.1% | 7.4x |
| Extreme Irritability/Temper | 31.2% | 6.8% | 6.2x |
| Binge Eating Behaviors | 18.9% | 3.5% | 6.5x |
| Bullying Victimization | 24.3% | 5.9% | 5.1x |
| Screen Time Addiction (4+ hrs/day) | 35.6% | 12.3% | 3.9x |
| Chronic Headaches | 15.2% | 3.1% | 5.6x |

**Gender-Specific Patterns:**

*   Males with ADHD showed significantly higher rates of externalizing behaviors (bullying, physical aggression, risk-taking)
*   Females with ADHD demonstrated higher internalizing patterns (eating disorders, negative body image, emotional dysregulation)
*   The largest gender gap appeared in binge eating (OR: 7.2 for females vs 5.1 for males) and self-harm indicators

## Technical Approach

**Data Processing & Cleaning:**

*   Handled complex survey coding (missing values encoded as 90, 95, 99)
*   Binary classification of ADHD diagnosis (Current ADHD = 3 vs No ADHD = 1)
*   Gender-stratified analysis pipeline

**Statistical Methods:**

*   Chi-Square tests for categorical associations
*   Odds Ratio calculations with 95% confidence intervals
*   Fisher's Exact Test for small sample sizes
*   Gender-stratified comparative analysis

**Visualization & Reporting:**

*   High-resolution publication-ready visualizations (300 DPI)
*   Multi-page PDF report with 5 distinct analytical perspectives
*   Comparative bar charts, odds ratio plots, gender difference analyses, and correlation heatmaps

## Tools & Technologies

*   **Python:** Pandas, NumPy, SciPy
*   **Visualization:** Matplotlib & Seaborn
*   **Statistical Analysis:** Chi-Square, Odds Ratios, Correlation matrices
*   **PDF Generation:** Automated report compilation

## Impact & Insights

This analysis revealed that ADHD manifests far beyond attention difficulties, with significant implications for:

*   Eating disorders screening in ADHD patients (particularly females)
*   Trauma-informed care for bullied ADHD children
*   Screen time management as a critical intervention point
*   Academic support systems for grade retention prevention

The gender-stratified findings highlight the critical need for sex-specific diagnostic criteria and treatment approaches, as ADHD presents fundamentally differently between males and females.
