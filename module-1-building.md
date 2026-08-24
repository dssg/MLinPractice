---
title: "Module 1 · Building ML Systems"
parent: Syllabus
nav_order: 1
permalink: /syllabus/module-1/
---

# Module 1 · Building ML Systems
{: .no_toc }

Building end-to-end ML systems for real problems — scoping, formulation,
validation, metrics, features, and pipelines. A **GenAI in practice** note marks
where generative models change how a step is done. (Weeks 1–6; the project runs
alongside — see the [schedule]({{ '/schedule/' | relative_url }}).)

<details open markdown="block">
  <summary>Sessions</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## Class overview
The class, its goals, and the applied project we use as a motivating example.
[Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture1-ClassOverview.pptx)

## Why ML systems can fail in practice
Failure modes beyond model accuracy: data, deployment, incentives, governance.
{: .note }
> **GenAI in practice:** LLM-specific failure modes — hallucination, silent
> drift, eval gaming, prompt brittleness.

## Scoping ML systems
Can and should this be solved with ML? How is success measured, and how are
efficiency, effectiveness, and equity balanced?
{: .note }
> **GenAI in practice:** build vs. buy vs. fine-tune vs. prompt is now a scoping
> decision — and when *not* to use an LLM.

**Required:** [Data Science Project Scoping Guide](https://datasciencepublicpolicy.org/our-work/tools-guides/data-science-project-scoping-guide/)

## ML systems in practice — student presentations
Students present and critique real deployed ML/AI systems across domains and
problem types.

## Analytical formulation and baselines
Defining the label, the available features, and the baseline you must beat —
which should reflect the status quo, rarely "random."
{: .note }
> **GenAI in practice:** an LLM zero/few-shot prompt is often the baseline you
> now have to beat (or beat *with*). Every team implements one.

**Required:** Obermeyer et al., *Dissecting Racial Bias…* (Science, 2019); Passi & Barocas, *Problem Formulation and Fairness* (FAT\*, 2019).

## Data exploration
Exploration in service of modeling decisions — much of the session is team work.
{: .note }
> **GenAI in practice:** LLMs for wrangling, parsing, and extracting structure
> from messy/unstructured data.

## Model selection (evaluation)
Validation strategy: how it relates to how you hope the model will generalize,
and why k-fold often lies in practice.
{: .note }
> **GenAI in practice:** first look at evaluation *without ground truth* — the
> problem that dominates generative systems.

**Required:** Roberts et al., *Cross-validation strategies for data with temporal, spatial, hierarchical, or phylogenetic structure* (Ecography, 2017).

## Model performance metrics
Metrics that match the decision: precision@k / top-k under capacity constraints,
calibration, and why one headline number misleads.
{: .note }
> **GenAI in practice:** faithfulness and groundedness for generative outputs.

**Required:** *The Misuse of AUC: What High-Impact Risk Assessment Gets Wrong* (2023).

## Feature engineering
Expressing domain knowledge through features; handling outliers and missingness
without leaking.
{: .note }
> **GenAI in practice:** LLMs for feature extraction, labeling / weak
> supervision, embeddings, and synthetic data — validated against human labels.

## ML modeling in practice & hyperparameter tuning
Where to start on a real problem: a sensible hyperparameter grid, common
pitfalls, and how to avoid them.

**Required:** Riley, *Three Pitfalls to Avoid in Machine Learning* (Nature, 2019); Ghani et al., *Top 10 ways your ML models may have leakage* (DSSG blog).

## ML pipelines
Modular, config-driven pipelines vs. monolithic notebooks.
{: .note }
> **GenAI in practice:** RAG and agent systems *are* pipelines — prompts,
> retrieval, and tools are components you can test and swap. (Built out in
> [Module 2]({{ '/syllabus/module-2/' | relative_url }}).)

**Required:** [ML pipelines slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture8-Machine-Learning-Pipelines.pptx)
