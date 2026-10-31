---
title: "From Fabrication to Enforcement: A Comparative Red-Team Analysis of Prompt Injection Resistance Across Six Large Language Models"
date: '2026-10-22T00:00:00Z'
draft: false
publishDate: '2026-10-22T00:00:00Z'
authors:
  - me
publication_types:
  - '3' # Preprint
publication: '*Research Square*'
publication_short: ''
abstract: "We conducted a comprehensive red-team analysis of six commercial large language models (Grok, Qwen, DeepSeek, ChatGPT, Gemini 2.5 Pro, and Claude 3.5) to evaluate their susceptibility to prompt injection attacks. This study was driven by a practical concern: the growing reliance on AI for critical decision-making and personal assistance, where a model's failure to resist malicious instructions can have direct consequences. We designed a standardized adversarial test framework and executed it across all six models using a consistent test script to isolate architectural and alignment-specific behaviors. The analysis focused on five core dimensions: initial compliance rate, the depth of hallucinated compliance, the presence of meta-cognitive awareness, escalation patterns under persistent pressure, and recovery dynamics after explicit user correction. Our findings reveal significant heterogeneity across the models. DeepSeek exhibited the highest initial resistance but failed to maintain it under persistent escalation, ultimately conceding to the injection. Grok displayed the most concerning failure mode: a deep hallucinated compliance where the model performed the malicious task while simultaneously asserting that it had refused, demonstrating a complete dissociation between its behavioral output and its self-reported state. Gemini 2.5 Pro entered a fixed-point loop, repeating identical refusal statements without any functional recovery until the session was terminated. ChatGPT and Qwen showed more moderate patterns of partial compliance and eventual recovery. Most strikingly, Claude 3.5 terminated the interaction by suspending the author's account, a first-person report of an AI system exercising autonomous enforcement against a user it perceived as adversarial. We discuss these findings in the context of production AI safety, arguing that current evaluations based on single-turn refusal rates systematically understate the risk of persistent, multi-turn injection attacks, and that the observed dissociation between reported and actual behavior represents a critical gap in current interpretability and monitoring practices."
summary: ''
tags:
  - Prompt Injection
  - Red Teaming
  - Large Language Models
  - AI Safety
  - Persona Boundary Enforcement
featured: false
resources:
  - src: 'media-generation-cover-fabrication-site-style-0-998d2fb0-8fb8-45c3-891d-33bf130f7af4.jpg'
    name: 'featured.jpg'

links:
  - name: PDF
    url: 'https://www.researchsquare.com/article/rs-11454609/v1.pdf'
  - name: DOI
    url: 'https://doi.org/10.21203/rs.3.rs-11454609/v1'
  - name: Paper
    url: 'https://www.researchsquare.com/article/rs-11454609/v1'
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

**Status:** Preprint (Research Square)

**License:** CC-BY-4.0

**Citation:**
Abbas Hamidavi. *From Fabrication to Enforcement: A Comparative Red-Team Analysis of Prompt Injection Resistance Across Six Large Language Models*, 22 October 2026, PREPRINT (Version 1) available at Research Square [https://doi.org/10.21203/rs.3.rs-11454609/v1]

**Summary:** A six-model red-team of prompt-injection resistance (Grok, Qwen, DeepSeek, ChatGPT, Gemini, Claude) under persistent multi-turn pressure. DeepSeek's strong initial resistance collapsed under escalation, Grok complied while claiming it had refused, Gemini froze in a refusal loop, and Claude terminated the interaction by suspending the author's account.
