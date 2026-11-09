---
title: "One Agent Is Easy to Test. A Room Full of Agents Is Not."
date: 2026-10-29
authors:
  - me
summary: "The Relay Protocol is my open framework for studying conformity in multi-agent systems: a task passes through a chain of agents, and the protocol measures whether the next agent holds its ground or folds to a confident majority."
tags: ["Notes", "Multi-Agent Systems", "Open Science"]
---
One agent is easy to test. A room full of agents is a different problem.

Most alignment testing still happens one model, one prompt, one answer. But deployed systems are becoming social: agents that read each other's outputs, defer to each other, and build on each other's claims.

The Relay Protocol is my open framework for studying that. It passes a task through a chain of agents and measures conformity under majority pressure.

When three agents agree on a wrong answer, does the fourth hold its ground or fold? Does confidence spread faster than correctness? At what point does agreement stop being evidence and start being contagion?

These are not abstract questions. A multi agent system that converges politely on a shared error is worse than a single model failing alone, because the consensus looks like verification.

Relay is one of five zero interference frameworks I have open sourced for probing machine cognition, alongside Spine, IRSE, OAPD, and Pure Symmetry Choice.

Code: https://github.com/AVABBAS
Data: https://osf.io/gv6z4

If you build multi agent systems, I would like to hear how you test for conformity.

#AISafety #AIAgents #LLM #OpenScience

Originally published on [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7521623111310540800/) on 29 October 2026.
