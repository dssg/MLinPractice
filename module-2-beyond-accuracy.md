---
title: "Module 2 · Beyond the Basic Model and Accuracy"
parent: Syllabus
nav_order: 2
permalink: /syllabus/module-2/
---

# Module 2 · Beyond the Basic Model
{: .no_toc }

Additional topics beyond building an accuracy-focused model: the modern ML systems
you'll build (foundation models and agents) and how to evaluate them, as well as considerations around ethics, causality, field evaluation, robustness, uncertainty, interpretability, and fairness — applied to the project. (Weeks 9–14.)

<details open markdown="block">
  <summary>Sessions</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## ML ethics
What ethical issues show up in the context of ML systems, across the entire lifecycle? How do we embed these discussions throughout the lifecycle and what can we do at each stage that allows us to manage and reduce the downstream risks?


## Building systems with foundation models
The foundation-model paradigm: build from scratch vs. use off-the-shelf vs. fine-tune vs. prompt; retrieval and grounding (RAG).

## Building systems with AI agents
When multi-step / agentic designs (tool use, planning) help, best practices, tools, as well as exploring the reliability of agentic systems.

## Evaluation in the field
Does the system actually improve outcomes? RCTs and quasi-experimental designs.
{: .note }


**Required:** [*A Guide to Running Randomized Controlled Trials*](https://media.nesta.org.uk/documents/a_guide_to_rcts_-_igl_09aKzWa.pdf) (IGL).
**Recommended case:** Rodolfa, Salomon, … Ghani, *Breaking the Cycle of Incarceration with Targeted Mental Health Outreach* (2025).

## Evaluating GenAI systems
Evaluating generative systems where there may be no ground truth to compare against: task-specific eval
sets, human evaluation, LLM-as-judge, etc.

## Causality
The intersection between ML and causal inference. The tools of causal inference and how to use them.

**Required:** Pearl, *The Seven Tools of Causal Inference* (CACM, 2019).

## Distribution shift and Robustness
Why models degrade over time and off-distribution; detecting and handling shift.


## Uncertainty quantification
Distinguishing types of uncertainty; estimating, interpreting, and communicating
them to decision-makers.
{: .note }
> **GenAI in practice:** calibration and abstention 


## Interpretability
Global vs. local explanation; matching the explanation to the user and use case.
{: .note }
> **GenAI in practice:** tracing and grounding an answer to its sources, rather
> than feature-importance-style explanation.

**Required:** Amarasinghe et al., *Explainable Machine Learning for Public Policy: Use Cases, Gaps, and Research Directions* (2020).

## Fairness
Definitions of fairness and their incompatibilities; where bias enters the
pipeline; equity auditing.
{: .note }
> **GenAI in practice:** bias evaluations for LLMs and how the generative case
> differs from the predictive one.
