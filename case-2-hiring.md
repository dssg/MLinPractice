---
title: "Case 2 · Screening job applicants"
parent: "Case studies: why ML systems fail"
permalink: /cases/failure/case-2-hiring/
---

# Case 2 · Screening job applicants

**The goal.** Automate the top of the hiring funnel: given a résumé, identify
the strongest candidates for technical roles.

**The system.** From 2014, a model scored applicants **one to five stars**,
"much like shoppers rate products." It was trained on **ten years of résumés
submitted to the company**. Gender was not an input.

**What surfaced.** By 2015 the team found the model was not rating candidates in
a gender-neutral way. It **penalized résumés containing the word "women's"** (as
in "women's chess club captain"), **downgraded graduates of two all-women's
colleges**, and favoured verbs more common in men's résumés such as "executed"
and "captured."

**The response.** Engineers edited the model to be neutral to those specific
terms. The team was disbanded around 2017. The tool was never rolled out
broadly.

## Your task
{: .no_toc }

1. Gender was never an input. How did the model learn it anyway?
2. They removed the flagged terms. Why wasn't that enough?
3. What was this model actually trained to predict? Is that the same as "good candidate"?
4. This was caught before reaching applicants at scale. What made that possible?

---

*Sources are on the [main case studies page]({{ '/cases/failure/#sources' | relative_url }}) — read them after the session.*
