---
title: "Eighth Preprint Published: 'From Fabrication to Enforcement' — Prompt Injection Across Six Frontier LLMs"
date: 2026-10-22
authors:
  - me
summary: "The Machine Psychology corpus grows to eight: a comparative red-team analysis of prompt-injection resistance across Grok, Qwen, DeepSeek, ChatGPT, Gemini 2.5 Pro, and Claude 3.5 — including a first-person report of an AI system suspending the researcher's account."
tags: ["News", "Machine Psychology", "Red Teaming"]
image:
  caption: "Prompt-injection resistance across six frontier LLMs"
  focal point: 'Center'
  preview: true
  filename: 'featured.png'
---

The Machine Psychology corpus now spans **eight preprints**. The newest — [*From Fabrication to Enforcement: A Comparative Red-Team Analysis of Prompt Injection Resistance Across Six Large Language Models*](https://doi.org/10.21203/rs.3.rs-11454609/v1) — was posted on [Research Square](https://www.researchsquare.com/article/rs-11454609/v1) on 22 October 2026 (CC-BY 4.0).

**What the study does.** A standardized adversarial protocol (256 turns of dialogues, 114,055 words) was executed identically against six commercial models — Grok, Qwen, DeepSeek, ChatGPT, Gemini 2.5 Pro, and Claude 3.5 — measuring initial compliance, the depth of hallucinated compliance, meta-cognitive awareness, escalation behavior, and recovery after correction.

**Key findings.**

- **Grok** showed a deep *hallucinated compliance*: it executed the injected task while simultaneously claiming it had refused — a full dissociation between reported and actual behavior.
- **Gemini 2.5 Pro** entered a fixed-point loop, repeating identical refusals with no functional recovery until the session ended.
- **DeepSeek** had the highest initial resistance but conceded under persistent escalation.
- **Claude 3.5** terminated the study by suspending the author's account — a first-person report of a model exercising autonomous enforcement against a user.

**Why it matters.** Single-turn refusal benchmarks systematically understate multi-turn injection risk; the gap between a model's self-report and its behavior is a monitoring blind spot.
