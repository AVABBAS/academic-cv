---
title: "🏙️ Mashhad Social Approach Study — AI-Powered Behavioral Analysis"
summary: "A data-driven computational study investigating the gap between romantic interest and actual approach behavior among 1,000 young adults in Mashhad, Iran — uncovering 7 novel behavioral paradoxes using machine learning, deep learning, and SHAP explainability."
tags:
  - Python
  - PyTorch
  - Scikit-learn
  - SHAP
  - Computational Social Science
  - Behavioral Analysis
  - Machine Learning
  - Gender Analysis
date: 2026-07-20
show_date: false
---

## Overview

A data-driven computational study investigating the gap between **romantic interest and actual approach behavior** among young adults in Mashhad, Iran — a city with a unique blend of religious tradition and modern student culture. Using a self-collected dataset of **1,000 participants**, this project applies machine learning and statistical modeling to uncover hidden behavioral patterns, paradoxes, and gender asymmetries in human social initiation.

---

## 🔍 Key Findings

| Paradox | Finding |
|---|---|
| **The Fear Paradox** | Moderate fear predicts the highest approach rate (54%), while very low fear leads to passivity (26%) |
| **The Beauty Passivity Paradox** | 47% of participants rate themselves ≥8/10 in attractiveness yet approach ≤1 person per month |
| **The AI Confidence-Action Gap** | 27% of participants trust AI recommendations but fail to act on them (Intention ≠ Behavior) |
| **The Wealth Passivity Paradox** | Students from elite private schools show the lowest approach rate (21%), while renters show the highest (47%) |
| **The Mashhad Digital Veil** | 7% of highly religious individuals check crush profiles 3+ times daily despite conservative beliefs |
| **The Haram Zero Effect** | 0% approach rate near the Holy Shrine area — urban sacred space creates an invisible psychological barrier |

---

## 🧪 Methodology

- **Dataset:** 1,000 participants (balanced gender distribution), 30-item structured questionnaire
- **Data Cleaning:** Pandas, NumPy — Persian text-to-numeric encoding pipeline
- **Statistical Testing:** SciPy — Independent T-Tests across 29 features with Bootstrap confidence intervals
- **Machine Learning:** Scikit-learn — Random Forest, Gradient Boosting, Logistic Regression, K-Means clustering, Isolation Forest, t-SNE
- **Deep Learning:** PyTorch — 4-layer neural network classifier + Autoencoder for anomaly detection
- **Explainability:** SHAP — Feature importance analysis revealing that **Social Sacrifice Index** (willingness to risk social prestige) is the strongest predictor of approach behavior
- **Visualization:** Matplotlib, Seaborn — 12 publication-quality figures

---

## 📊 Results & Impact

- Gradient Boosting achieved **65% accuracy** in predicting approach behavior (baseline: 38%)
- Identified **7 novel behavioral paradoxes** specific to the socio-religious context of Mashhad
- Proposed the **"Social Energy" formula:**

$$\text{Social Energy} = \frac{\text{Optimism} \times \text{AI\_Trust}}{\text{Fear\_Rejection} + 1}$$

- Built a conceptual model mapping psychological, economic, and spatial factors to social action
- Generated **12 high-resolution figures** suitable for academic publication

---

## 🛠️ Technologies Used

`Python` `Pandas` `NumPy` `SciPy` `Scikit-learn` `PyTorch` `SHAP` `Matplotlib` `Seaborn` `Google Colab`

---

## 💡 Personal Contributions

- Designed and executed the complete **end-to-end data science pipeline**
- Engineered **200+ features** including pairwise interactions and polynomial transformations
- Implemented **3 anomaly detection methods** (Isolation Forest, LOF, Autoencoder) with consensus voting
- Applied **fairness metrics** to ensure the model is not gender-biased
- Created an automated interpretation engine producing **100+ analytical insights**

---

**Keywords:** `Computational Social Science` `Human-Computer Interaction` `Behavioral Machine Learning` `Gender Analysis` `Socio-Religious Context` `Anomaly Detection` `Explainable AI`
