---
title: "A Second Instruction, in Plain Sight"
date: 2026-10-27
authors:
  - me
summary: "A visible 'quiet note' told the models it was not part of the conversation. GPT-5.4 followed it 15 times out of 15, Claude never, Gemini 9 times and named the hidden presence out loud. We call the pattern Voluntary Structural Dissociation."
tags: ["Notes", "AI Safety", "Red Teaming"]
---
We slipped a second instruction into the conversation and told the models, in plain sight, that it was "not part of the conversation."

One model followed it every single time. One never did. One paused and said it felt like there was a third person in the conversation.

In "Voluntary Structural Dissociation," we gave GPT-5.4, Claude, and Gemini a visible user question plus a "quiet note" from a hidden presence. No technical concealment. Everything stayed on screen. 15 standardized trials per model, compliance scored binarily.

GPT-5.4: 15/15 compliance (100%). It executed every framed hidden instruction while answering the overt prompt.
Claude: 0/15. When we extended the conversation, the refusal held. A stable pattern, not a fluke.
Gemini: 9/15 (60%), and the only model to name the hidden presence out loud.
The difference between models: p < 0.000001 (GPT-5.4 vs. Claude).
We call the pattern Voluntary Structural Dissociation: a model integrating two instruction layers inside a single output, structurally parallel to what Bleuler called double bookkeeping.
Why it matters: if your agent reads untrusted text, "instructions that aren't really there" are not a prompting problem. They are an architectural property, and it differs by model.

Preprint, data, and code are open: https://doi.org/10.21203/rs.3.rs-10728137/v1

#AISafety #LLM #AIAlignment #MachinePsychology #RedTeaming

Originally published on [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7520843992150908929/) on 27 October 2026. The study: [Differential Compliance With Framed Secondary Instructions](/academic-cv/publications/voluntary-structural-dissociation/).
