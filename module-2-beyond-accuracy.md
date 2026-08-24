---
title: "Module 2 · Beyond the Basic Model"
parent: Syllabus
nav_order: 2
permalink: /syllabus/module-2/
---

# Module 2 · Beyond the Basic Model
{: .no_toc }

Additional topics beyond building an accuracy-focused model: the modern systems
you'll also build (foundation models and agents) and how to evaluate them, plus
the accountability lenses — ethics, causality, field evaluation, robustness,
uncertainty, interpretability, and fairness — each applied to the system your
team has built. (Weeks 9–14.)

<details open markdown="block">
  <summary>Sessions</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## ML ethics
Ethical stakes across the ML lifecycle: consent, harm, transparency,
accountability, and who bears the downside.
{: .note }
> **GenAI in practice:** hallucination as harm, representational harms, and the
> ethics of scale and automation.

**Required:** Loukides, Mason & Patil, *Ethics and Data Science*; Bender et al., *On the Dangers of Stochastic Parrots* (2021) (excerpt).

## Building with foundation models
The foundation-model paradigm: build vs. buy vs. fine-tune vs. prompt; retrieval
and grounding (RAG); cost, latency, and reliability as design constraints.

**Required:** Lewis et al., *Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks* (2020); Yan et al., *What We Learned from a Year of Building with LLMs*, Part III (O'Reilly, 2024).
**Optional:** Huyen, *AI Engineering* (2025).

## Building with agents
When multi-step / agentic designs (tool use, planning) help vs. add fragility;
reliability of compound systems.

**Required:** Schluntz & Zhang, [*Building Effective Agents*](https://www.anthropic.com/research/building-effective-agents) (Anthropic, 2024).
**Optional:** Yao et al., *ReAct: Synergizing Reasoning and Acting in Language Models* (2023).

## Evaluation in the field
Does the system actually improve outcomes? RCTs and quasi-experimental designs.
{: .note }
> **GenAI in practice:** the offline→online gap — a system that looks good on an
> eval set can still fail on the real decision it supports.

**Required:** [*A Guide to Running Randomized Controlled Trials*](https://media.nesta.org.uk/documents/a_guide_to_rcts_-_igl_09aKzWa.pdf) (IGL).
**Recommended case:** Rodolfa, Salomon, … Ghani, *Breaking the Cycle of Incarceration with Targeted Mental Health Outreach* (2025).

## Evaluating GenAI systems
Evaluating generative systems where there's no ground truth: task-specific eval
sets, human evaluation, LLM-as-judge and its traps, and eval-driven development
(regression testing, red-teaming).

**Required:** Zheng et al., *Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena* (2023); Husain, [*Your AI Product Needs Evals*](https://hamel.dev/blog/posts/evals/) (2024).
**Optional:** Shankar et al., *Who Validates the Validators? Aligning LLM-Assisted Evaluation of LLM Outputs with Human Preferences* (2024).

## Causality
Why prediction isn't explanation; the tools of causal inference and when you
actually need them.

**Required:** Pearl, *The Seven Tools of Causal Inference* (CACM, 2019).

## Distribution shift
Why models degrade over time and off-distribution; detecting and handling shift.
{: .note }
> **GenAI in practice:** prompt injection (incl. indirect), jailbreaks, and
> quiet drift as underlying models change.

**Required:** Greshake et al., *Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection* (2023).

## Uncertainty quantification
Distinguishing types of uncertainty; estimating, interpreting, and communicating
them to decision-makers.
{: .note }
> **GenAI in practice:** calibration and abstention — getting a system to say "I
> don't know" instead of confidently hallucinating.

**Required:** Hüllermeier & Waegeman, [*Aleatoric and Epistemic Uncertainty in Machine Learning*](https://arxiv.org/pdf/1910.09457.pdf), §1–3.

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

**Required:** Verma & Rubin, *Fairness Definitions Explained*; revisit Obermeyer et al. (2019).
