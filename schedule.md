---
title: Schedule
nav_order: 2
nav_exclude: false
permalink: /schedule/
---

# Schedule
{: .no_toc }

Fall 2026 · Tuesday & Thursday, 2:00–3:20 pm · [POS 153](https://maps.app.goo.gl/FSHeY1jTBVzpsztA8).
Assignments are submitted on [Canvas](https://canvas.cmu.edu/courses/56403).

This page is the source for session descriptions, readings, and slides.
Click any topic in the table to jump to its details.

## At a glance
{: .no_toc }

| Week | Date | Topic | Project milestone |
| :--: | --- | --- | --- |
| 1 | Tue Aug 25 | [Class overview](#class-overview) | |
| 1 | Thu Aug 27 | [Why ML systems can fail in practice](#why-ml-systems-can-fail) | Team creation (Aug 28) |
| 2 | Tue Sep 1 | [Scoping ML systems](#scoping) | Project idea (Aug 31) |
| 2 | Thu Sep 3 | [ML systems in practice](#systems-in-practice) | |
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

**Tue Aug 25.** Overview of the course

*[Slides](https://docs.google.com/presentation/d/1I-B7Eq08vEy4HnokjMTz9fzSl2C1Ndeo/edit?slide=id.p1#slide=id.p1):* 

## Why ML systems can fail in practice
{: #why-ml-systems-can-fail }

**Thu Aug 27.** We'll discuss real-world failure modes of ML systems, moving beyond model accuracy to system-level issues including data, deployment, governance, incentives, etc. The goal here is to encourage critical thinking about preventing failures and to motivate the topics to be covered during the rest of the semester.

> **GenAI in practice:** Are there LLM-specific failure modes?

*Slides:* posted after class discussion

*Case Studies for Breakout Groups:* [Case Studies](case-studies-failure.md)

*Project:* team creation due Aug 28.

## Scoping ML systems
{: #scoping }

**Tue Sep 1.** We’ll discuss scoping, problem definition, and understanding and balancing organizational goals. Before we start doing technical ML work, a decision needs to be made about whether a given problem can and should be addressed with machine learning. What outcomes is the system supposed to achieve? How is success measured? What actions and decisions does the system enable? What ethical discussions need to happen?

> **GenAI in practice:** Does scoping change for GenAI systems?

*Slides:* TBD
*Required:* [Data Science Project Scoping Guide](https://datasciencepublicpolicy.org/our-work/tools-guides/data-science-project-scoping-guide/)
*Optional:* [Fine-grained dengue forecasting using telephone triage services](https://nyunetworks.github.io/Pubs/rehman-science16.pdf) (Rehman et al., Sci. Adv. 2016); [Deconstructing Statistical Questions](http://stat688.bio5.org/sites/default/files/fall2014/hand-deconstructin.pdf) (Hand, J. Royal Stat. Soc. A, 1994); 

*Project:* submit project ideas (to get feedback) due Aug 31.

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

*Slides:* TBD
*Required:* [Dissecting Racial Bias in an Algorithm Used to Manage the Health of Populations](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/ObermeyerBias.pdf) (Obermeyer et al., Science 2019); [Problem Formulation and Fairness](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/PassiFormulation.pdf) (Passi & Barocas, FAT\* 2019).
*Optional:* [Always Start with a Stupid Model, No Exceptions](https://blog.insightdatascience.com/always-start-with-a-stupid-model-no-exceptions-3a22314b9aaa) (Ameisen); [Create a Common-Sense Baseline First](https://towardsdatascience.com/first-create-a-common-sense-baseline-e66dbf8a8a47) (Ramakrishnan); [Data Science for Business](https://learning.oreilly.com/library/view/data-science-for/9781449374273/ch02.html) (Provost & Fawcett, ch. 2).

## Data exploration
{: #data-exploration }

**Thu Sep 10.** Data exploration in the context of ML systems. How does data
exploration support making modeling decisions? What phases of an ML project
require doing data exploration?

> **GenAI in practice:** LLMs for wrangling, parsing, and extracting structure
> from messy/unstructured data.

*Slides:* TBD
*Optional:* [Can Foundation Models Wrangle Your Data?](https://www.vldb.org/pvldb/vol16/p738-narayan.pdf) (Narayan et al., VLDB 2023).
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

*Slides:* TBD
*Required:* [Cross-validation strategies for data with temporal, spatial, hierarchical, or phylogenetic structure](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/RobertsCV.pdf) (Roberts et al., Ecography 2017).
*Optional:* [Amazing Things Come From Having Many Good Models](https://arxiv.org/pdf/2407.04846); [Time Series Nested Cross-Validation](https://medium.com/data-science/time-series-nested-cross-validation-76adba623eb9) (Cochrane); [The Secrets of Machine Learning](https://arxiv.org/abs/1906.01998) (Rudin & Carlson, 2019); [Big Data and Social Science](https://textbook.coleridgeinitiative.org/chap-ml.html) (Foster, Ghani et al., §7.7); [Evaluating and Comparing Classifiers](https://link.springer.com/chapter/10.1007/978-3-319-59162-9_2) (Stapor, CORES 2017).

## Model performance metrics
{: #metrics }

**Tue Sep 22.** How do we back into the metric we care about? Metrics that match
the decision and the deployment setting: precision@k / top-k under capacity
constraints, calibration, and why we may need multiple metrics.

> **GenAI in practice:** What metrics do we need for GenAI systems?

*Slides:* TBD
*Required:* [The Misuse of AUC: What High-Impact Risk Assessment Gets Wrong](https://arxiv.org/abs/2305.18159) (2023).
*Optional:* [Transductive Optimization of Top-k Precision](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/LiuTransductiveTopK.pdf) (Liu et al., IJCAI 2016).

## Feature engineering
{: #feature-engineering }

**Thu Sep 24.** Tabular data still requires serious feature engineering to
express domain knowledge through features. How do we create such features? What
are common templates? How do we handle outliers and missingness without leaking?

> **GenAI in practice:** LLMs for feature extraction, labeling / weak
> supervision, and embeddings.

*Slides:* TBD
*Optional:* [Missing Data Conundrum](https://medium.com/ibm-data-science-experience/missing-data-conundrum-exploration-and-imputation-techniques-9f40abe0fd87) (Akinfaderin); [Feature Engineering for Machine Learning](https://learning.oreilly.com/library/view/feature-engineering-for/9781491953235/) (Zhang & Casari, ch. 2); [Missing-data imputation](http://www.stat.columbia.edu/~gelman/arm/missing.pdf) (Gelman).
*Optional (data infrastructure):* [Netflix's Trillions Scale Real-time Data Infrastructure](https://zhenzhongxu.com/the-four-innovation-phases-of-netflixs-trillions-scale-real-time-data-infrastructure-2370938d7f01); [Real-time Data Infrastructure at Uber](https://arxiv.org/abs/2104.00087).

## ML modeling in practice & hyperparameter tuning
{: #modeling }

**Tue Sep 29.** Where to start on a real problem: what models to explore, what is
a reasonable hyperparameter grid, why optuna is not always the right answer,
common pitfalls, and how to avoid them.

*Slides:* TBD
*Required:* [Three Pitfalls to Avoid in Machine Learning](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/RileyPitfalls.pdf) (Riley, Nature 2019); [Top 10 ways your Machine Learning models may have leakage](http://www.dssgfellowship.org/2020/01/23/top-10-ways-your-machine-learning-models-may-have-leakage/) (Ghani et al., DSSG blog).

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

*Slides:* TBD
*Required:* [Ethics and Data Science](https://www.oreilly.com/library/view/ethics-and-data/9781492043898/?ar) (Loukides, Mason & Patil, O'Reilly 2018 — short)
*Optional:* [Princeton AI Ethics Case Study 6: Public Sector Data Analysis](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/Princeton-AI-Ethics-Case-Study-6.pdf).
*Project:* Initial ML Solution due tonight (11:59pm).

## Building systems with foundation models
{: #foundation-models }

**Thu Oct 22.** The foundation-model paradigm: build from scratch vs. use
off-the-shelf vs. fine-tune vs. prompt; retrieval and grounding (RAG).

*Slides:* TBD

## Building systems with AI agents
{: #agents }

**Tue Oct 27.** When multi-step / agentic designs (tool use, planning) help, best
practices, tools, and the reliability of agentic systems.

*Slides:* TBD


## Evaluation in the field
{: #field-evaluation }

**Thu Oct 29.** Does the system actually improve outcomes? RCTs and
quasi-experimental designs.

> **GenAI in practice:** the offline→online gap — a system that looks good on an
> eval set can still fail on the real decision it supports.

*Slides:* TBD
*Required:* [*A Guide to Running Randomized Controlled Trials*](https://media.nesta.org.uk/documents/a_guide_to_rcts_-_igl_09aKzWa.pdf) (IGL).
*Recommended case:* [Breaking the Cycle of Incarceration With Targeted Mental Health Outreach](https://arxiv.org/abs/2509.14129) (Rodolfa, Salomon, … Ghani, 2025).
*Optional:* [The Econometrics of Randomized Experiments](https://www.sciencedirect.com/science/chapter/handbook/abs/pii/S2214658X16300174) (Athey & Imbens).

## Evaluating GenAI systems
{: #evaluating-genai }

**Thu Nov 5.** Evaluating generative systems where there may be no ground truth
to compare against: task-specific eval sets, human evaluation, LLM-as-judge, etc.

*Slides:* TBD


## Causality
{: #causality }

**Tue Nov 10.** The intersection between ML and causal inference. The tools of
causal inference and how to use them.

*Slides:* TBD
*Required:* [The Seven Tools of Causal Inference, with Reflections on Machine Learning](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/PearlCausality.pdf) (Pearl, CACM 2019).
*Optional:* [Elements of Causal Inference](https://mitpress.mit.edu/books/elements-causal-inference) (Peters et al., MIT Press — ch. 1–2).

## Distribution shift and robustness
{: #distribution-shift }

**Thu Nov 12.** Why models degrade over time and off-distribution; detecting and
handling shift.

> **GenAI in practice:** prompt injection (incl. indirect), jailbreaks, and quiet
> drift as underlying models change.

*Slides:* TBD


## Uncertainty quantification
{: #uncertainty }

**Tue Nov 17.** Distinguishing types of uncertainty; estimating, interpreting,
and communicating them to decision-makers.

> **GenAI in practice:** calibration and abstention.

*Slides:* TBD


## Interpretability
{: #interpretability }

**Thu Nov 19.** Global vs. local explanation; matching the explanation to the
user and use case.

> **GenAI in practice:** tracing and grounding an answer to its sources, rather
> than feature-importance-style explanation.

*Slides:* TBD
*Required:* [Explainable Machine Learning for Public Policy: Use Cases, Gaps, and Research Directions](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/AmarasingheExplainable.pdf) (Amarasinghe et al., 2020); [Benchmarking and Survey of Explanation Methods for Black Box Models](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/BodriaExplainable.pdf) (Bodria et al., 2021).
*Project:* Iteration 2 due Thu Nov 19 — add one component from Module 2.

## Fairness
{: #fairness }

**Tue Nov 24.** Definitions of fairness and their incompatibilities; where bias
enters the pipeline; equity auditing.

> **GenAI in practice:** bias evaluations for LLMs and how the generative case
> differs from the predictive one.

*Slides:* TBD
*Required:* [Fairness Definitions Explained](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/VermaFairnessDefn.pdf) (Verma & Rubin); revisit Obermeyer et al. (2019).
*Optional:* [A Theory of Justice](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/RawlsJustice.pdf) (Rawls, 1971 — ch. 1, pp. 1–19); [Racial Equity in Algorithmic Criminal Justice](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/HuqRacialEquity.pdf) (Huq, Duke Law Journal 2018); [Is Algorithmic Affirmative Action Legal?](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3372690) (Bent, Georgetown Law Journal 2019); [Does Mitigating ML's Impact Disparity Require Treatment Disparity?](http://papers.nips.cc/paper/8035-does-mitigating-mls-impact-disparity-require-treatment-disparity) (Lipton et al., NeurIPS 2018); [Equality of Opportunity](http://cowles.yale.edu/sites/default/files/files/pub/d19/d1921.pdf) (Roemer & Trannoy, 2013).

## Project presentations
{: #final-presentations }

**Tue Dec 1 & Thu Dec 3.** The full arc: problem, approach, evaluation, honest
limitations, and recommendations.

*Project:* Project Presentation due Tue Dec 1; Project Writeup and Demo due Tue Dec 8.
