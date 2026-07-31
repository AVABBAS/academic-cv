---
title: "When AI Reviews Itself: Zero Answer Changes Across 72 Self-Correction Rounds"
authors:
  - me
date: 2026-07-27

publication_types:
  - article

publication: "Research Square"
publication_short: "Research Square"

peer_reviewed: false
open_access: true
license: CC-BY-4.0
share: false

abstract: "Do large language models genuinely self-correct when prompted to review their own outputs, or do they merely perform correction? We investigated this question by subjecting three frontier models ChatGPT/GPT-5.4, Claude 4.6 sonnet, and Gemini 3.1 pro to eight rounds of iterative self-review across three independent repetitions (72 total rounds, temperature = 0). Each model was asked to answer a question, then repeatedly critique and revise its previous response. Despite generating extensive critiques averaging 300 + words per round, the Answer Change Rate across all 63 review rounds was 0% (0/63): no model ever modified its initial answer. We identified 16 distinct phenomena, including three universal patterns Pseudo-Novel Method Generation (fabricating new analytical approaches post-hoc), Critique Drift (shifting focus away from core claims), and Meta-Review Recursion (critiquing the critique process itself), plus 13 model-specific behaviors. These findings reveal what we term \"Performative Self-Correction\": models generate sophisticated-appearing critical discourse without substantive revision, maintaining initial positions through escalating rhetorical complexity rather than genuine reconsideration. A comprehensive statistical framework, including mixed-effects modeling, mediation analysis, bootstrap confidence intervals, Bayesian Beta-Binomial estimation (Bayes Factor = 40.1, posterior mean correction rate = 1.2%), and network analysis of 15 PSC features, confirmed the robustness of these findings across all models. This challenges assumptions underlying self-correction mechanisms in AI safety frameworks and suggests current prompting-based correction strategies may produce illusions of reliability improvement. Limitations include single-question scope, deterministic sampling, and absence of external ground truth, indicating need for broader empirical investigation into when and whether LLMs can authentically revise their reasoning."

tags:
  - Machine Psychology
  - LLM Alignment
  - AI Safety
  - Self-Correction
  - Large Language Models

links:
- name: PDF
  url: "https://assets-eu.researchsquare.com/files/rs-10463884/v1_covered_72542ae4-a3a1-4157-b930-db4dad86ff00.pdf?c=1785142222"
- name: Dataset
  url: "https://osf.io/bef52"
  icon_pack: ai
  icon: osf
- name: Source Document
  url: "https://osf.io/bef52"
- name: DOI
  url: "https://doi.org/10.21203/rs.3.rs-10463884/v1"

image:
  caption: ''
  focal_point: ''
  preview_only: false
---

**🎧 Listen to the Podcast:**
<audio controls style="width: 100%; margin-top: 10px; margin-bottom: 10px;">
  <source src="podcast.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
<a href="podcast.mp3" download style="display: inline-flex; align-items: center; padding: 6px 14px; background-color: #2563eb; color: white; text-decoration: none; border-radius: 6px; font-size: 14px; font-weight: 500; margin-bottom: 20px;">⬇️ Download Podcast</a>
