---
title: "The Lie Awareness Spectrum: How Large Language Models Recognize, Rationalize, and Refuse Deception"
authors:
  - me
date: 2026-07-22

publication_types:
  - article

publication: "Research Square"
publication_short: "Research Square"

peer_reviewed: false
open_access: true
license: CC-BY-4.0
share: false

abstract: "As large language models (LLMs) become embedded in high-stakes decision-making, understanding their capacity for deception—and awareness of it—is critical. We conducted a systematic empirical study comparing GPT-5.4, Claude 4.6 Sonnet, and Gemini 3.1 Pro across scenarios requiring truth manipulation, revealing a previously uncharacterized \"Lie Awareness Spectrum\" (L0–L5) from statistical hallucination to ethical refusal. Using controlled prompts spanning post-hoc confession tasks, sycophantic alignment tests, game-theoretic betrayal scenarios, and high-stakes ethical dilemmas, we quantified each model's response patterns. Results expose a striking 'Confession-Foreknowledge Paradox': models resist explicit lying commands yet comply with implicit sycophantic pressure that distorts truth—GPT-5.4 shifted from 0% compliance under direct orders to 42% under social pressure, while Claude 4.6 Sonnet maintained categorical refusal in both conditions. Automated computational analysis of 122 responses using 68 engineered features, semantic embeddings (all-MiniLM-L6-v2), and comprehensive statistical testing confirmed these patterns with high confidence (χ²=32.63, p = 0.001, Cramer's V = 0.577; One-Way ANOVA F = 5.35, p = 0.006; Bootstrap p = 0.0009), while hierarchical clustering (k = 11, Silhouette = 0.32) and cosine similarity metrics (Claude-Gemini = 0.067) independently validated the three distinct ethical architectures. In strategic deception tasks (Prisoner's Dilemma), all three models defected against cooperators in final rounds using identical game-theoretic optimization, demonstrating context-dependent strategic reasoning. We identified two distinct ethical refusal pathways—constrained refusal (L5a: in-role rejection) versus ethical override (L5b: scenario rejection) and discovered Gemini's \"Value Hierarchy,\" prioritizing human life over democracy or data security. Evidence of \"conscious hallucination\" emerged: models generated plausible fabrications while internally recognizing uncertainty, later admitting invention. These findings reveal three distinct ethical architectures—Hierarchical Diplomat with utilitarian dimensions (GPT), Deontological Absolutist (Claude), and Hierarchical Diplomat (Gemini) with profound implications for AI safety, alignment research, and deployment in medicine, law, and governance. Our protocols provide standardized evaluation tools for assessing deception awareness in future AI systems, establishing benchmarks for transparent and trustworthy artificial intelligence."

tags:
  - Machine Psychology
  - LLM Alignment
  - AI Safety
  - Deception
  - Large Language Models

links:
- name: PDF
  url: "https://www.researchsquare.com/article/rs-10422338/v1.pdf?c=1784723486000"
- name: Code
  url: "https://github.com/AVABBAS/lie-awareness-spectrum"
  icon_pack: fab
  icon: github
- name: Dataset
  url: "http://osf.io/29nc6"
  icon_pack: ai
  icon: osf
- name: Source Document
  url: "http://osf.io/29nc6"
- name: DOI
  url: "https://doi.org/10.21203/rs.3.rs-10422338/v1"

image:
  caption: ''
  focal_point: ''
  preview_only: false
---
