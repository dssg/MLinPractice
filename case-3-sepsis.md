---
title: "Case 3 · Predicting sepsis"
parent: "Case studies: why ML systems fail"
permalink: /cases/failure/case-3-sepsis/
---

# Case 3 · Predicting sepsis in hospitalized patients

**The goal.** Alert clinicians early when a hospitalized patient may be
developing sepsis.

**The system.** A proprietary model built into a widely used electronic health
record and deployed at **hundreds of US hospitals**. It rescored patients every
15 minutes and fired an interruptive alert above a vendor-recommended threshold.
**One of its inputs was whether a clinician had ordered antibiotics.**

**Vendor-reported performance.** AUC 0.76–0.83.

**Independent validation.** 38,455 hospitalizations at one academic medical
center; 7% developed sepsis.

| Metric | Result |
| --- | --- |
| AUC | 0.63 |
| Sensitivity | 33% |
| PPV | 12% |

- Generated alerts on **18% of all hospitalized patients**
- **Missed 67%** of patients who developed sepsis
- Of 2,552 septic patients, identified **183 (7%)** whose sepsis was not already
  being treated in time

## Your task
{: .no_toc }

1. Vendor 0.76–0.83, independent 0.63. How does that gap happen?
2. What does an alert on 1 in 5 patients do to the people receiving alerts?
3. What is the effect of using "clinician ordered antibiotics" as an input?
4. It added value for 7% of septic patients beyond usual care. What does that say
   about the right baseline?

---

*Sources are on the [main case studies page]({{ '/cases/failure/#sources' | relative_url }}) — read them after the session.*
