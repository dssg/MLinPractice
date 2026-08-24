---
title: Syllabus
nav_order: 2
has_children: true
nav_exclude: false
permalink: /syllabus/
---

# Syllabus
{: .no_toc }

<details open markdown="block">
  <summary>On this page</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

## Course description

A project-based course that gives students training and experience solving
real-world problems with machine learning, exploring the interface and gaps
between research and practice. The goal is exposure to the nuance of using ML in
the real world, where common assumptions (like i.i.d. and stationarity) break
down, and where there is a growing need for approaches that go beyond optimizing
accuracy: fairness, explainability, robustness, uncertainty quantification, and
real-world impact. Through lectures, discussions, readings, and a semester-long
team project, students build ML systems for real problems with real data.
Generative AI runs throughout — woven into the core build sessions, taught
directly (foundation models, agents, and generative-system evaluation), and
required in the project.

## Learning objectives

1. **Scope & formulate.** Translate a messy real-world problem into a well-posed
   ML task (predictive or generative), decide whether ML is even the right tool,
   and define success in terms of decisions and outcomes rather than offline
   metrics.
2. **Build end-to-end systems.** Design and implement modular, config-driven ML
   pipelines and foundation-model systems on real, messy data.
3. **Validate honestly.** Choose validation strategies that match how the system
   must generalize, and detect the ways both predictive and generative systems
   silently fail.
4. **Reason beyond accuracy.** Apply and critically evaluate methods for
   fairness, interpretability, uncertainty, robustness, and causality across
   both paradigms.
5. **Evaluate impact.** Move from offline metrics to field evaluation of whether
   a system actually improves real-world outcomes.
6. **Communicate.** Present technical work clearly to technical and
   non-technical audiences, in writing and in person.

## How the course is organized

Two teaching modules, with a single team project as the spine that runs
throughout.

| Module | Weeks | Focus |
| --- | --- | --- |
| [**1 · Building ML Systems**]({{ '/syllabus/module-1/' | relative_url }}) | 1–6 | Scoping, formulation, data, validation, metrics, features, pipelines |
| [**2 · Beyond the Basic Model**]({{ '/syllabus/module-2/' | relative_url }}) | 9–14 | Building with foundation models & agents; evaluating generative systems; ethics, causality, field evaluation, robustness, uncertainty, interpretability, fairness |

**GenAI runs as a thread, not a bolt-on.** It enters as a woven *"GenAI in
practice"* beat inside core sessions, as three dedicated Module 2 sessions
(foundation models, agents, evaluating generative systems), and as a project
requirement — every team implements an LLM zero/few-shot baseline and reflects
on where the tools helped or misled them.

See the [schedule]({{ '/schedule/' | relative_url }}) for the week-by-week plan
with readings, and the [project]({{ '/project/' | relative_url }}) page for the
milestone timeline.

## Background & optional readings

*Predictive practice:* Provost & Fawcett, *Data Science for Business* (ch. 2);
Foster, Ghani et al., *Big Data and Social Science*; Ameisen, *Always Start with
a Stupid Model*; Liu et al., *Transductive Optimization of Top-k Precision*
(IJCAI 2016).

*Fairness & ethics:* Verma & Rubin, *Fairness Definitions Explained*; Lipton et
al., *Does Mitigating ML's Impact Disparity Require Treatment Disparity?*;
Princeton AI Ethics Case Study 6.

*GenAI systems & eval:* Yan et al., *What We Learned from a Year of Building with
LLMs* (2024); Huyen, *AI Engineering* (2025); Liang et al., *HELM*; Bai et al.,
*Constitutional AI*.

*Deployment & causality:* Huyen, *Designing Machine Learning Systems* (2022);
Sculley et al., *Hidden Technical Debt in Machine Learning Systems* (2015);
Peters et al., *Elements of Causal Inference* (ch. 1–2).
