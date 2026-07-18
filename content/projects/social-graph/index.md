---
title: "🧬 68-Dimensional Social Graph: Computational Social Science on 10M Persian Telegram Messages"
summary: "A 68-dimensional computational social science framework revealing hidden personality traits, mental health indicators, and relationship dynamics from 10 million real-world chat messages."
tags:
  - Python
  - PyTorch
  - ParsBERT
  - NLP
  - Graph Neural Networks
  - Neo4j
  - Computational Social Science
date: 2024-01-01
show_date: false
---

## Overview

A large-scale computational social science project that constructs a **68-dimensional hypergraph** from 10 million real Persian chat messages, modeling the complete social, psychological, and behavioral dynamics of an online community.

---

## Key Metrics

| Metric | Value |
|---|---|
| Messages Analyzed | 10,000,000 |
| Users (Nodes) | 7,636 |
| Relationships (Edges) | 310,732 |
| Node Dimensions | 68 |
| Edge Dimensions | 20 |
| Total Data Points | ~6.7 million |
| Time Span | 23 months |

---

## Technical Architecture

- **GPU Server:** NVIDIA A100 (40GB VRAM) + 128GB RAM + 32 vCPUs
- **NLP Engine:** ParsBERT v3 (fine-tuned on Persian chats)
- **Graph Database:** Neo4j (Cypher queries) + Parquet (analytics) + PyTorch Geometric (GNN)
- **ML Stack:** XGBoost, Random Forest, Gradient Boosting, Ensemble Voting, K-Means
- **Pipeline:** Prefect orchestration, Polars data processing, CUDA acceleration

---

## 9 Analytical Layers

| Layer | Dimensions | Description |
|---|---|---|
| 🎭 Personality | 10 | Big Five traits, gender, age, name authenticity |
| 🧠 Psychology | 13 | Depression (PHQ-9), anxiety (GAD-7), narcissism, bipolar, PTSD, self-harm risk |
| 🤝 Relational | 12 | Deception detection, diplomacy scoring, social masking, genuine vs. fake closeness |
| 🔗 Network | 9 | PageRank, Betweenness, Community Detection (Louvain), Broker Score |
| ⏱️ Temporal | 6 | Chronotype, mood volatility, recovery time, leave prediction |
| 📝 Content | 8 | Lexical richness, sarcasm detection, BERTopic, metaphor usage |
| 🛡️ Cybersecurity | 3 | Bot detection (emoji signature), sockpuppet identification, social engineering risk |
| ❤️ Digital Health | 3 | Screen addiction, sleep deprivation, wellbeing index |
| 👑 Power & Influence | 4 | Opinion leaders, gatekeepers, trendsetters, echo chamber contributors |

---

## Key Discoveries

- **"Silence Before the Storm":** 5/5 major conflict events were preceded by 10–15 consecutive silence (bradycardia) patterns — a statistically significant early warning signal.
- **Emojis Outperform BERT:** Emoji-based clustering achieves **4.5× better** personality separation than ParsBERT embeddings (Silhouette: 0.265 vs 0.058).
- **Killer Words:** The word "bye" (بای) caused **676 group-wide silences**, acting as a conversation terminator.
- **Bot Fingerprinting:** Bots exhibit **630× distinct emoji signatures** (✔, ➖, ❓), detectable with **99.2% accuracy** without text analysis.
- **Paradox of Toxicity:** Toxic relationships last **3× longer** than healthy ones.
- **Masked Selves:** Average social masking score is **43%** — users hide nearly half their true personality during daytime interactions.

---

## 100 Research Analyses

The hypergraph enables **100 distinct analyses** across 9 layers, with potential for **19 Q1 journal papers** in venues such as:

- *Nature Human Behaviour*
- *PNAS / Science Advances*
- *Nature Communications*
- *Journal of Personality and Social Psychology*
- *Computational Linguistics*
- *EPJ Data Science*

---

## Technologies Used

`Python` `PyTorch` `ParsBERT` `HuggingFace Transformers` `Neo4j` `Cypher` `PyTorch Geometric` `XGBoost` `Scikit-learn` `Polars` `NetworkX` `Prefect` `Docker` `CUDA` `Plotly` `BERTopic` `Leiden Algorithm`

---

## Publication Potential

> **19 Q1 papers | 100 analyses | 4.6M+ data points | 23-month longitudinal data**
>
> *"When Emojis Outperform BERT: A 68-Dimensional Framework for Personality, Mental Health, and Relationship Dynamics in Digital Communities"*
