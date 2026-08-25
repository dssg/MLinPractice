---
title: Schedule
nav_order: 3
nav_exclude: false
permalink: /schedule/
---

# Schedule
{: .no_toc }

Fall 2026 · Tuesday & Thursday, 2:00–3:20 pm · [POS 153](https://maps.app.goo.gl/FSHeY1jTBVzpsztA8).
Assignments are submitted on [Canvas](https://canvas.cmu.edu/courses/56403).

This page is the single source for session descriptions, readings, and slides.
Click any topic in the table to jump to its details.

## At a glance
{: .no_toc }

| Week | Date | Topic | Project milestone |
| :--: | --- | --- | --- |
| 1 | Tue Aug 25 | [Class overview](#class-overview) | |
| 1 | Thu Aug 27 | [Why ML systems can fail in practice](#why-ml-systems-can-fail) | Team creation (Aug 28) |
| 2 | Tue Sep 1 | [Scoping ML systems](#scoping) | Project idea (Aug 31) |
| 2 | Thu Sep 3 | [ML systems in practice — student presentations](#systems-in-practice) | |
| 3 | Tue Sep 8 | [Analytical formulation and baselines](#formulation) | |
| 3 | Thu Sep 10 | [Data exploration](#data-exploration) | Proposal & scope (Sep 14) |
| 4 | Tue Sep 15 | [**Project pitches**](#project-pitches) | 3-min pitch due (2pm) |
| 4 | Thu Sep 17 | [Model selection (evaluation)](#model-selection) | |
| 5 | Tue Sep 22 | [Model performance metrics](#metrics) | |
| 5 | Thu Sep 24 | [Feature engineering](#feature-engineering) | |
| 6 | Tue Sep 29 | [ML modeling & hyperparameter tuning](#modeling) | |
| 6 | Thu Oct 1 | [ML pipelines](#pipelines) | Baseline(s) due |
| 7 | Tue Oct 6 | [**Project update presentations**](#update-presentations) | Update presentation due (2pm) |
| 7 | Thu Oct 8 | [**Project update presentations**](#update-presentations) | |
| 8 | Oct 13 / 15 | *No class — Fall Break* | |
| 9 | Tue Oct 20 | [ML ethics](#ethics) | Initial ML solution due |
| 9 | Thu Oct 22 | [Building systems with foundation models](#foundation-models) | |
| 10 | Tue Oct 27 | [Building systems with AI agents](#agents) | |
| 10 | Thu Oct 29 | [Evaluation in the field](#field-evaluation) | |
| 11 | Tue Nov 3 | *No class — Democracy Day* | |
| 11 | Thu Nov 5 | [Evaluating GenAI systems](#evaluating-genai) | Evaluation due |
| 12 | Tue Nov 10 | [Causality](#causality) | |
| 12 | Thu Nov 12 | [Distribution shift and robustness](#distribution-shift) | |
| 13 | Tue Nov 17 | [Uncertainty quantification](#uncertainty) | |
| 13 | Thu Nov 19 | [Interpretability](#interpretability) | Iteration 2 due |
| 14 | Tue Nov 24 | [Fairness](#fairness) | |
| 14 | Thu Nov 26 | *No class — Thanksgiving Break* | |
| 15 | Tue Dec 1 | [**Project presentations**](#final-presentations) | Project presentation due |
| 15 | Thu Dec 3 | [**Project presentations**](#final-presentations) | |
| — | Tue Dec 8 | **Project writeup & demo due** | |

---

# Module 1 · Building ML Systems
{: #module-1 }

Building end-to-end ML systems for real problems — scoping, formulation,
validation, metrics, features, and pipelines.

## Class overview
{: #class-overview }

**Tue Aug 25.** The class, its goals, and the applied project we use as a
motivating example all semester.

*Slides:* TBD

## Why ML systems can fail in practice
{: #why-ml-systems-can-fail }

**Thu Aug 27.** Failure modes beyond model accuracy: data, deployment,
incentives, governance.

> **GenAI in practice:** Are there LLM-specific failure modes?

*Slides:* TBD
*Project:* team creation due Aug 28.

## Scoping ML systems
{: #scoping }

**Tue Sep 1.** Can and should this be solved with ML? What goals is the system
supposed to achieve? How is success measured? What actions and decisions does the
system enable? What ethical discussions need to happen?

> **GenAI in practice:** Does scoping change for GenAI systems?

*Required:* [Data Science Project Scoping Guide](https://datasciencepublicpolicy.org/our-work/tools-guides/data-science-project-scoping-guide/)
*Slides:* TBD
*Project:* submit project idea due Aug 31.

## ML systems in practice — student presentations
{: #systems-in-practice }

**Thu Sep 3.** Students present and critique real deployed ML/AI systems across
domains and problem types.

## Analytical formulation and baselines
{: #formulation }

**Tue Sep 8.** Turning the scope into an ML problem. What design decisions need
to be made? Defining the label, the available features, and the baseline we need
to compare against — which should reflect the status quo or easy-to-implement
approaches, rarely "random."

> **GenAI in practice:** an LLM zero/few-shot prompt is an example of an
> easy-to-implement baseline.

*Required:* Obermeyer et al., *Dissecting Racial Bias…* (Science, 2019); Passi & Barocas, *Problem Formulation and Fairness* (FAT\*, 2019).
*Slides:* TBD

## Data exploration
{: #data-exploration }

**Thu Sep 10.** Data exploration in the context of ML systems. How does data
exploration support making modeling decisions? What phases of an ML project
require doing data exploration?

> **GenAI in practice:** LLMs for wrangling, parsing, and extracting structure
> from messy/unstructured data.

*Slides:* TBD
*Project:* project proposal and scope due Mon Sep 14.

## Project pitches
{: #project-pitches }

**Tue Sep 15.** 3-minute team pitches: the problem, why it matters, who the
decision-maker is, and what data exists.

*Project:* 3-minute pitch due in class (2:00pm).

## Model selection (evaluation)
{: #model-selection }

**Thu Sep 17.** Validation strategy: how it relates to how you want the model to
generalize during deployment/test time, and why k-fold often fails in practice.

*Required:* Roberts et al., *Cross-validation strategies for data with temporal, spatial, hierarchical, or phylogenetic structure* (Ecography, 2017).
*Slides:* TBD

## Model performance metrics
{: #metrics }

**Tue Sep 22.** How do we back into the metric we care about? Metrics that match
the decision and the deployment setting: precision@k / top-k under capacity
constraints, calibration, and why we may need multiple metrics.

> **GenAI in practice:** What metrics do we need for GenAI systems?

*Required:* *The Misuse of AUC: What High-Impact Risk Assessment Gets Wrong* (2023).
*Slides:* TBD

## Feature engineering
{: #feature-engineering }

**Thu Sep 24.** Tabular data still requires serious feature engineering to
express domain knowledge through features. How do we create such features? What
are common templates? How do we handle outliers and missingness without leaking?

> **GenAI in practice:** LLMs for feature extraction, labeling / weak
> supervision, and embeddings.

*Slides:* TBD

## ML modeling in practice & hyperparameter tuning
{: #modeling }

**Tue Sep 29.** Where to start on a real problem: what models to explore, what is
a reasonable hyperparameter grid, why optuna is not always the right answer,
common pitfalls, and how to avoid them.

*Required:* Riley, *Three Pitfalls to Avoid in Machine Learning* (Nature, 2019); Ghani et al., *Top 10 ways your ML models may have leakage* (DSSG blog).
*Slides:* TBD

## ML pipelines
{: #pipelines }

**Thu Oct 1.** Modular, config-driven pipelines vs. monolithic notebooks.

> **GenAI in practice:** RAG and agent systems *are* pipelines — prompts,
> retrieval, and tools are components you can test and swap.

*Slides:* TBD
*Project:* Implement Baseline(s) due tonight (11:59pm).

## Project update presentations
{: #update-presentations }

**Tue Oct 6 & Thu Oct 8.** Progress, formulation, baselines, and early results;
structured peer feedback.

*Project:* update presentation due in class (2:00pm).

## Fall Break
{: #fall-break .no_toc }

**Tue Oct 13 & Thu Oct 15.** No class.

---

# Module 2 · Beyond the Basic Model and Accuracy
{: #module-2 }

Additional topics beyond building an accuracy-focused model: the modern ML
systems you'll build (foundation models and agents) and how to evaluate them, as
well as considerations around ethics, causality, field evaluation, robustness,
uncertainty, interpretability, and fairness — applied to the project.

## ML ethics
{: #ethics }

**Tue Oct 20.** What ethical issues show up in the context of ML systems, across
the entire lifecycle? How do we embed these discussions throughout the lifecycle,
and what can we do at each stage that allows us to manage and reduce the
downstream risks?

*Required:* Loukides, Mason & Patil, *Ethics and Data Science*; Bender et al., *On the Dangers of Stochastic Parrots* (2021, excerpt).
*Slides:* TBD
*Project:* Initial ML Solution due tonight (11:59pm).

## Building systems with foundation models
{: #foundation-models }

**Thu Oct 22.** The foundation-model paradigm: build from scratch vs. use
off-the-shelf vs. fine-tune vs. prompt; retrieval and grounding (RAG).

*Required:* Lewis et al., *Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks* (2020); Yan et al., *What We Learned from a Year of Building with LLMs*, Part III (O'Reilly, 2024).
*Optional:* Huyen, *AI Engineering* (2025).
*Slides:* TBD

## Building systems with AI agents
{: #agents }

**Tue Oct 27.** When multi-step / agentic designs (tool use, planning) help, best
practices, tools, and the reliability of agentic systems.

*Required:* Schluntz & Zhang, [*Building Effective Agents*](https://www.anthropic.com/research/building-effective-agents) (Anthropic, 2024).
*Optional:* Yao et al., *ReAct: Synergizing Reasoning and Acting in Language Models* (2023).
*Slides:* TBD

## Evaluation in the field
{: #field-evaluation }

**Thu Oct 29.** Does the system actually improve outcomes? RCTs and
quasi-experimental designs.

> **GenAI in practice:** the offline→online gap — a system that looks good on an
> eval set can still fail on the real decision it supports.

*Required:* [*A Guide to Running Randomized Controlled Trials*](https://media.nesta.org.uk/documents/a_guide_to_rcts_-_igl_09aKzWa.pdf) (IGL).
*Recommended case:* Rodolfa, Salomon, … Ghani, *Breaking the Cycle of Incarceration with Targeted Mental Health Outreach* (2025).
*Slides:* TBD

## Evaluating GenAI systems
{: #evaluating-genai }

**Thu Nov 5.** Evaluating generative systems where there may be no ground truth
to compare against: task-specific eval sets, human evaluation, LLM-as-judge, etc.

*Required:* Zheng et al., *Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena* (2023); Husain, [*Your AI Product Needs Evals*](https://hamel.dev/blog/posts/evals/) (2024).
*Optional:* Shankar et al., *Who Validates the Validators?* (2024).
*Slides:* TBD
*Project:* Evaluation due tonight (11:59pm).

## Causality
{: #causality }

**Tue Nov 10.** The intersection between ML and causal inference. The tools of
causal inference and how to use them.

*Required:* Pearl, *The Seven Tools of Causal Inference* (CACM, 2019).
*Slides:* TBD

## Distribution shift and robustness
{: #distribution-shift }

**Thu Nov 12.** Why models degrade over time and off-distribution; detecting and
handling shift.

> **GenAI in practice:** prompt injection (incl. indirect), jailbreaks, and quiet
> drift as underlying models change.

*Required:* Greshake et al., *Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection* (2023).
*Slides:* TBD

## Uncertainty quantification
{: #uncertainty }

**Tue Nov 17.** Distinguishing types of uncertainty; estimating, interpreting,
and communicating them to decision-makers.

> **GenAI in practice:** calibration and abstention.

*Required:* Hüllermeier & Waegeman, [*Aleatoric and Epistemic Uncertainty in Machine Learning*](https://arxiv.org/pdf/1910.09457.pdf) (2019), §1–3.
*Slides:* TBD

## Interpretability
{: #interpretability }

**Thu Nov 19.** Global vs. local explanation; matching the explanation to the
user and use case.

> **GenAI in practice:** tracing and grounding an answer to its sources, rather
> than feature-importance-style explanation.

*Required:* Amarasinghe et al., *Explainable Machine Learning for Public Policy: Use Cases, Gaps, and Research Directions* (2020).
*Slides:* TBD
*Project:* Iteration 2 due Thu Nov 19 — add one component from Module 2.

## Fairness
{: #fairness }

**Tue Nov 24.** Definitions of fairness and their incompatibilities; where bias
enters the pipeline; equity auditing.

> **GenAI in practice:** bias evaluations for LLMs and how the generative case
> differs from the predictive one.

*Required:* Verma & Rubin, *Fairness Definitions Explained*; revisit Obermeyer et al. (2019).
*Slides:* TBD

## Project presentations
{: #final-presentations }

**Tue Dec 1 & Thu Dec 3.** The full arc: problem, approach, evaluation, honest
limitations, and recommendations.

*Project:* Project Presentation due Tue Dec 1; Project Writeup and Demo due Tue Dec 8.
