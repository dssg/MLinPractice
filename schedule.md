---
title: Schedule
nav_order: 3
nav_exclude: false
permalink: /schedule/
---

# Schedule
{: .no_toc }

Fall 2026 · Tuesday & Thursday, 2:00–3:20 pm · [POS 153](https://maps.app.goo.gl/FSHeY1jTBVzpsztA8).
Assignments are submitted on [Canvas](https://canvas.cmu.edu/courses/49132).

<details open markdown="block">
  <summary>On this page</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

## At a glance

| Week | Date | Topic | Project milestone |
| :--: | --- | --- | --- |
| 1 | Tue Aug 25 | Class overview | |
| 1 | Thu Aug 27 | Why ML systems can fail in practice | Team creation (Aug 28) |
| 2 | Tue Sep 1 | Scoping ML systems | Project idea (Aug 31) |
| 2 | Thu Sep 3 | ML systems in practice — student presentations | |
| 3 | Tue Sep 8 | Analytical formulation and baselines | |
| 3 | Thu Sep 10 | Data exploration | Proposal & scope (Sep 14) |
| 4 | Tue Sep 15 | **Project pitches** | 3-min pitch due (2pm) |
| 4 | Thu Sep 17 | Model selection (evaluation) | |
| 5 | Tue Sep 22 | Model performance metrics | |
| 5 | Thu Sep 24 | Feature engineering | |
| 6 | Tue Sep 29 | ML modeling & hyperparameter tuning | |
| 6 | Thu Oct 1 | ML pipelines | Baseline(s) due |
| 7 | Tue Oct 6 | **Project update presentations** | Update presentation due (2pm) |
| 7 | Thu Oct 8 | **Project update presentations** | |
| 8 | Oct 13 / 15 | *No class — Fall Break* | |
| 9 | Tue Oct 20 | ML ethics | Initial ML solution due |
| 9 | Thu Oct 22 | Building with foundation models | |
| 10 | Tue Oct 27 | Building with agents | |
| 10 | Thu Oct 29 | Evaluation in the field | |
| 11 | Tue Nov 3 | *No class — Democracy Day* | |
| 11 | Thu Nov 5 | Evaluating GenAI systems | Evaluation due |
| 12 | Tue Nov 10 | Causality | |
| 12 | Thu Nov 12 | Distribution shift | |
| 13 | Tue Nov 17 | Uncertainty quantification | |
| 13 | Thu Nov 19 | Interpretability | Iteration 2 due |
| 14 | Tue Nov 24 | Fairness | |
| 14 | Thu Nov 26 | *No class — Thanksgiving Break* | |
| 15 | Tue Dec 1 | **Project presentations** | Project presentation due |
| 15 | Thu Dec 3 | **Project presentations** | |
| — | Tue Dec 8 | **Project writeup & demo due** | |

---

## Detailed schedule & readings

Readings are **required** unless marked *(optional)*. Module 1 = [Building ML
Systems]({{ '/syllabus/module-1/' | relative_url }}); Module 2 = [Beyond the
Basic Model]({{ '/syllabus/module-2/' | relative_url }}).

### Week 1 · Aug 25 & 27
**Tue Aug 25 · Class overview.** The class, its goals, and the applied project.
*Readings:* none.

**Thu Aug 27 · Why ML systems can fail in practice.** Failure modes beyond
accuracy — data, deployment, incentives, governance, and LLM-specific failures.
*Readings:* none.

### Week 2 · Sep 1 & 3
**Tue Sep 1 · Scoping ML systems.** Should this be ML? Defining success;
balancing efficiency, effectiveness, equity.
*Readings:* [Data Science Project Scoping Guide](https://datasciencepublicpolicy.org/our-work/tools-guides/data-science-project-scoping-guide/).
*Project:* team creation due Aug 28; submit project idea due Aug 31.

**Thu Sep 3 · ML systems in practice — student presentations.** Students present
and critique real deployed ML/AI systems.
*Readings:* none.

### Week 3 · Sep 8 & 10
**Tue Sep 8 · Analytical formulation and baselines.** Label design, available
features, and the status-quo baseline you must beat.
*Readings:* Obermeyer et al., *Dissecting Racial Bias…* (Science, 2019); Passi &
Barocas, *Problem Formulation and Fairness* (FAT\*, 2019).

**Thu Sep 10 · Data exploration.** Exploration in service of modeling decisions.
*Readings:* none.
*Project:* project proposal and scope due Mon Sep 14.

### Week 4 · Sep 15 & 17
**Tue Sep 15 · Project pitches.** 3-minute team pitches: problem, stakes, data.
*Readings:* none.
*Project:* 3-minute pitch due (in class, 2:00pm).

**Thu Sep 17 · Model selection (evaluation).** Validation strategy and how it
maps to how you hope the model generalizes; why k-fold often lies.
*Readings:* Roberts et al., *Cross-validation strategies for data with temporal,
spatial, hierarchical, or phylogenetic structure* (Ecography, 2017).

### Week 5 · Sep 22 & 24
**Tue Sep 22 · Model performance metrics.** Precision@k / top-k under capacity
constraints; calibration; why one number misleads.
*Readings:* *The Misuse of AUC: What High-Impact Risk Assessment Gets Wrong* (2023).
*Project:* baseline work — Implement Baseline(s) due Thu Oct 1 (incl. an LLM zero/few-shot baseline).

**Thu Sep 24 · Feature engineering.** Encoding domain knowledge; outliers and
missingness without leaking.
*Readings:* none.

### Week 6 · Sep 29 & Oct 1
**Tue Sep 29 · ML modeling in practice & hyperparameter tuning.** Where to
start; a sensible grid; pitfalls.
*Readings:* Riley, *Three Pitfalls to Avoid in Machine Learning* (Nature, 2019);
Ghani et al., *Top 10 ways your ML models may have leakage* (DSSG blog).


**Thu Oct 1 · ML pipelines.** Modular, config-driven pipelines vs. notebooks;
RAG and agent systems as pipelines.
*Readings:* none *(slides provided)*.
*Project:* Implement Baseline(s) due tonight (11:59pm).

### Week 7 · Oct 6 & 8
**Tue Oct 6 & Thu Oct 8 · Project update presentations.** Progress, formulation,
baselines, early results; structured peer feedback.
*Readings:* none.
*Project:* update presentation due (in class, 2:00pm).

### Week 8 · Oct 13 & 15
*No class — Fall Break.*

### Week 9 · Oct 20 & 22
**Tue Oct 20 · ML ethics.** Consent, harm, transparency, accountability; GenAI
harms and the ethics of scale.
*Readings:* Loukides, Mason & Patil, *Ethics and Data Science*; Bender et al.,
*On the Dangers of Stochastic Parrots* (2021, excerpt).
*Project:* Initial ML Solution due tonight (11:59pm).

**Thu Oct 22 · Building with foundation models.** Build vs. buy vs. fine-tune
vs. prompt; retrieval & grounding (RAG); cost, latency, reliability.
*Readings:* Lewis et al., *Retrieval-Augmented Generation for Knowledge-Intensive
NLP Tasks* (2020); Yan et al., *What We Learned from a Year of Building with
LLMs*, Part III (O'Reilly, 2024). *(optional:* Huyen, *AI Engineering*, 2025*)*.

### Week 10 · Oct 27 & 29
**Tue Oct 27 · Building with agents.** When agentic designs (tool use, planning)
help vs. add fragility; reliability of compound systems.
*Readings:* Schluntz & Zhang, [*Building Effective Agents*](https://www.anthropic.com/research/building-effective-agents)
(Anthropic, 2024). *(optional:* Yao et al., *ReAct*, 2023*)*.

**Thu Oct 29 · Evaluation in the field.** Does the system improve outcomes? RCTs
and quasi-experimental designs; the offline→online gap.
*Readings:* [*A Guide to Running Randomized Controlled Trials*](https://media.nesta.org.uk/documents/a_guide_to_rcts_-_igl_09aKzWa.pdf)
(IGL). *(recommended case:* Rodolfa, Salomon, … Ghani, *Breaking the Cycle of
Incarceration…*, 2025*)*.


### Week 11 · Nov 3 & 5
*Tue Nov 3 · No class — Democracy Day.*

**Thu Nov 5 · Evaluating GenAI systems.** Eval without ground truth: task
eval sets, human eval, LLM-as-judge and its traps, eval-driven development.
*Readings:* Zheng et al., *Judging LLM-as-a-Judge with MT-Bench and Chatbot
Arena* (2023); Husain, [*Your AI Product Needs Evals*](https://hamel.dev/blog/posts/evals/)
(2024). *(optional:* Shankar et al., *Who Validates the Validators?*, 2024*)*.
*Project:* Evaluation due tonight (11:59pm).

### Week 12 · Nov 10 & 12
**Tue Nov 10 · Causality.** Why prediction isn't explanation; the tools of
causal inference and when you need them.
*Readings:* Pearl, *The Seven Tools of Causal Inference* (CACM, 2019).

**Thu Nov 12 · Distribution shift.** Why models degrade over time and
off-distribution; prompt injection, jailbreaks, and LLM drift.
*Readings:* Greshake et al., *Not What You've Signed Up For: Compromising
Real-World LLM-Integrated Applications with Indirect Prompt Injection* (2023).

### Week 13 · Nov 17 & 19
**Tue Nov 17 · Uncertainty quantification.** Types of uncertainty; calibration;
abstention; communicating uncertainty to decision-makers.
*Readings:* Hüllermeier & Waegeman, [*Aleatoric and Epistemic Uncertainty in
Machine Learning*](https://arxiv.org/pdf/1910.09457.pdf) (2019), §1–3.
*Project:* Iteration 2 due Thu Nov 19 — add one component from Module 2.

**Thu Nov 19 · Interpretability.** Global vs. local explanation; matching
explanation to user and use case; tracing/grounding for LLMs.
*Readings:* Amarasinghe et al., *Explainable Machine Learning for Public Policy:
Use Cases, Gaps, and Research Directions* (2020).

### Week 14 · Nov 24 & 26
**Tue Nov 24 · Fairness.** Fairness definitions and their incompatibilities;
where bias enters the pipeline; equity auditing; bias evals for LLMs.
*Readings:* Verma & Rubin, *Fairness Definitions Explained*; revisit Obermeyer
et al. (2019).

*Thu Nov 26 · No class — Thanksgiving Break.*

### Week 15 · Dec 1 & 3
**Tue Dec 1 & Thu Dec 3 · Project presentations.** The full arc: problem,
approach, evaluation, honest limitations, recommendations.
*Readings:* none.
*Project:* Project Presentation due Tue Dec 1.

### Finals
**Tue Dec 8 · Project writeup and demo due.** The final writeup and demo (see
[Assignments & Grading]({{ '/grading/' | relative_url }})).
