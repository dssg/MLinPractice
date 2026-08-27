---
title: "Case studies: why ML systems fail"
has_children: true
permalink: /cases/failure/
---

# Case studies
{: .no_toc }

Breakout material for [Why ML systems can fail in practice]({{ '/schedule/#why-ml-systems-can-fail' | relative_url }})
(Thu Aug 27).

Each group picks one case. 

{: .note }
> For each case: the system worked in some meaningful sense. Your job is to
> work out what failed anyway, and where in the lifecycle that failure lives.

- TOC
{:toc}

---

## Case 1 · Reducing hospital readmissions (Camden, NJ)
{: #case-1 }

**The goal.** Reduce hospital readmissions among "super-utilizers" — patients
with very high healthcare use.

**The system.** Identify the highest-risk, highest-cost patients from hospital
data. For each one, a team of nurses, social workers, and community health
workers visits after discharge to coordinate outpatient care and connect them
to social services.

**The reception.** Nationally celebrated. Profiled in the *New Yorker*. Expanded
to cities across the country. Before-and-after numbers looked strong.

**The result.** A randomized controlled trial of ~800 patients (NEJM, 2020)
found **no difference in 180-day readmissions** between the program group and
usual care — about 62% in both.

### Your task
{: .no_toc }

1. The model identified high-risk patients accurately. So what failed?
2. Why did the before-and-after numbers look good?
3. Was the highest-risk patient the one whose readmission was most *preventable*?
4. What would you change — in the model, the intervention, or the evaluation?

---

## Case 2 · Screening job applicants
{: #case-2 }

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

### Your task
{: .no_toc }

1. Gender was never an input. How did the model learn it anyway?
2. They removed the flagged terms. Why wasn't that enough?
3. What was this model actually trained to predict? Is that the same as "good candidate"?
4. This was caught before reaching applicants at scale. What made that possible?

---

## Case 3 · Predicting sepsis in hospitalized patients (EPIC)
{: #case-3 }

**The goal.** Alert clinicians early when a hospitalized patient may be
developing sepsis to prevent sepsis.

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
| Recall | 33% |
| Precision | 12% |

- Generated alerts on **18% of all hospitalized patients**
- Of 2,552 septic patients, identified **183 (7%)** whose sepsis was not already
  being treated in time

### Your task
{: .no_toc }

1. Vendor 0.76–0.83, independent 0.63. How does that gap happen?
2. What does an alert on 1 in 5 patients do to the people receiving alerts?
3. What is the effect of using "clinician ordered antibiotics" as an input?
4. It added value for 7% of septic patients beyond usual care. What does that say
   about the right baseline?

---

## Case 4 · Buying homes with an automated valuation
{: #case-4 }

**The goal.** Buy homes directly from sellers, make light repairs, resell at a
margin (to make money)

**The system.** An established home-valuation model — mature, widely used, and
reasonably accurate as an *estimate* — was used to decide which homes to buy and
at what price. Purchases were made at scale.

**What happened.** Between April 2018 and November 2021, Zillow's iBuying program purchased approximately 27,000 homes across 25 US cities. In Q3 2021 the company bought 9,680 homes and sold 3,032 Total program losses in 2021 reached $881 million. In November 2021 it shut the unit down, took a write-down of more than $500M, and cut about 25% of its workforce (~2,000 people).

### Your task
{: .no_toc }

1. The valuation model was reasonably accurate. So what failed?
2. What changes when an estimate stops informing a browsing customer and starts
   triggering a purchase?
3. They were buying at volume in the markets they were forecasting. What does
   that do?
4. Would a more accurate valuation model have prevented this?

---

## Sources
{: #sources }

*Read these after the session*

**Case 1 —** Finkelstein et al., *Health Care Hotspotting — A Randomized,
Controlled Trial*, [NEJM 2020](https://www.nejm.org/doi/full/10.1056/NEJMsa1906848)
([free version](https://pmc.ncbi.nlm.nih.gov/articles/PMC7046127/)) ·
[Camden Coalition's page on the trial](https://camdenhealth.org/resources/healthcare-hotspotting-a-randomized-controlled-trial/)

**Case 2 —** Reuters via
[CNBC](https://www.cnbc.com/2018/10/10/amazon-scraps-a-secret-ai-recruiting-tool-that-showed-bias-against-women.html) ·
[MIT Technology Review](https://www.technologyreview.com/2018/10/10/139858/amazon-ditched-ai-recruitment-software-because-it-was-biased-against-women/) ·
[ACLU on why it was predictable](https://www.aclu.org/news/womens-rights/why-amazons-automated-hiring-tool-discriminated-against)

**Case 3 —** Wong et al., *External Validation of a Widely Implemented
Proprietary Sepsis Prediction Model*,
[JAMA Internal Medicine 2021](https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/2781307) ·
[2024 replication, JAMIA Open](https://academic.oup.com/jamiaopen/article/7/4/ooae133/7900014) ·
[UT Austin case study](https://ethicsunwrapped.utexas.edu/case-study/a-i-transparency-an-epic-deception)


