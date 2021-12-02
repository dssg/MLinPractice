# 10718: Machine Learning in Practice

**Previous Versions:** 
- **[Spring 2020](https://github.com/dssg/mlforpublicpolicylab/tree/Spring2020)**
- **[Fall 2020](https://github.com/dssg/MLinPractice/releases/tag/fall2020)**


### Fall 2021: Tues & Thurs, 4:40-6:00pm ([MM A14](https://goo.gl/maps/F84XABGawXvjms149)), Lab Section: Wednesday 4:40-6:00pm ([MM A14](https://goo.gl/maps/F84XABGawXvjms149))

### Important 
 - **All content will be on github in this repo including [schedule](README.md#schedule) and [tech setup instructions](techhelp/)**
 - **All assignments will be on and submitted through [canvas](https://canvas.cmu.edu/courses/25316)**
 - **Class communication and announcements will be primarily through Slack**

### Module II & III Presentation/Discussant Assignments

**MODULE 2 –– INTERPRETABILITY**

| date                         | method/approach | presenting group | discussant group |
| ---------------------------- | --------------- | ---------------- | ---------------- |
| Thu, Oct 28                  | GAMs | effective\_analytics | team\_16 |
| Thu, Oct 28                  | RiskSLIM | team\_15 | team\_6 |
| Tue, Nov 2                  | LIME | team\_14 | lucky\_13 |
| Tue, Nov 2                  | SHAP | team\_12 | quack |
| Tue, Nov 2                  | MAPLE | wuhu | team\_4 |
| Thu, Nov 4                   | DiCE | team\_5 | taaab |
| Thu, Nov 4                   | ProtoDash | k\_means\_girls | hmm |

**MODULE 3 –– FAIRNESS**

| date                         | method/approach | presenting group | discussant group |
| ---------------------------- | --------------- | ---------------- | ---------------- |
| Tue, Nov 16                  | Zafar In-Processing | team\_rocket | team\_14 |
| Tue, Nov 16                  | Celis In-Processing | lucky\_13 | team\_12 |
| Tue, Nov 16                  | FairLearn In-Processing | team\_6 | team\_15 |
| Thu, Nov 18                  | Model Selection | hmm | k\_means\_girls |
| Thu, Nov 18                  | Decoupled Classifiers | taaab | team\_5 |
| Thu, Nov 18                  | Score Adjustments | team\_4 | team\_rocket |
| Tue, Nov 23                  | Removing Sensitive Features | team\_16 | effective\_analytics |
| Tue, Nov 23                  | Resampling - Under and Over | quack | wuhu |

### Class Description

This is a project-based course designed to provide students training and experience in solving real-world problems using machine learning, exploring the interface between research and practice, with a particular focus on topics in fairness and explainability.

The goal of this course is to give students exposure to and experience the nuance of applying machine learning to real-world problems, where common assumptions (like iid and stationarity) break down, and the growing needs for (and limitations of) approaches to improve fairness and explainability of these applications. Through project assignments, lectures, discussions, and readings, students will learn about and experience building machine learning systems for real-world problems, as well as applying and evaluating the utility of proposed methods for enhancing the interpretability and fairness of machine learning models. Through the course, students will develop skills in problem scoping and formulation, getting, storing, linking, and working with messy data, making ML pipeline design choices appropriate for the problem at hand, exploring approaches for model selection, model interpretability, as well as understanding and mitigating algorithmic bias \& disparities, and evaluating the impact of deployed models.

**[DRAFT SYLLABUS](/syllabus.pdf)**

## People

### Instructors

| Rayid Ghani | Kit Rodolfa |
| --- | --- |
| <img src='http://www.datasciencepublicpolicy.org/wp-content/uploads/2018/05/RayidGhani-012-400x400.jpg' width='200' height='200' /> <br /> GHC 8023 <br /> Office Hours: <br />  Tue 12-1, Wed 2-3 | <img src='/kit_rodolfa.png' /> <br /> GHC 8018 <br /> Office Hours: <br /> Wed 11-12, Thu 1:30-2:30 |

### Infrastructure Assistants
Infrastructure Assistants are responsible for managing the compute infrastructure and help with logging in, scaling infrastructure, and connection issues.

| Riyaz Panjwani | Abhishek Parikh |
| --- | --- | 
| <img src='/riyaz_panjwani.jpeg' /> <br /> Office Hours: <br /> Mon 12-1, Fri 12-1 <br /> by GHC 8th Fl. Printer | <img src='abhishek-parikh_400x400.jpeg' width='200' height='200' /> <br /> Office Hours: <br /> Mon 11-12, Fri 2-3 <br /> by GHC 8th Fl. Printer |

## Grading 

Note that this course is being offered pass/fail. Each time you ask how each action you take will affect your grade will result in lowering of the grade.

Weekly project update assignments (10%)

Midterm take-home exam (20%)

Write-up on interpretability findings (15%)

Write-up on fairness findings (15%)

Group presentation (5%)

Future research or project proposal (15%)

Quizzes on readings and concepts (5%)

Class attendance and participation (10%)

Submitting weekly check-in and feedback forms (5%)

## Schedule

See the **[syllabus](/syllabus.pdf)** for much more detail as well, including information about group projects, grading, and helpful optional readings.
| Week | Dates            | Topic                                                                                                                                                                       | Required Readings                                                                                                                                                                 | Assignments                                                                                                                           |
| ---- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Tu: Aug 31       | [Class Intro and Overview](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture1-ClassOverview.pptx)                                                              |                                                                                                                                                                                   |                                                                                                                                       |
| 1    | Th: Sep 2        | [ML Project Scoping](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture2-Scoping.pptx)                                                                          | [ML Project Scoping Guide](http://www.datasciencepublicpolicy.org/home/resources/data-science-project-scoping-guide/)                                                             | Project Team Selection                                                                                                                |
| 2    | Tu: Sep 7        | [Getting, Storing, and Linking Data](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture3-Data.pptx)                                                             | [Optional readings on github](https://github.com/dssg/MLinPractice/blob/main/Readings/README.md#lecture-3---acquiring-storing-and-linkg-data-and-downstream-ethical-implications) |                                                                                                                                       |
| 2    | Th: Sep 9        | [Analytical Formulation / Baselines](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture4-Formulation.pptx)                                                      | [List on github](https://github.com/dssg/MLinPractice/blob/main/Readings/README.md#lecture-4---analytical-formulation-and-baselines)                                              |                                                                                                                                       |
| 3    | Tu: Sep 14       | [Model Selection Methodology](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture5-ModelSelection.pptx)                                                          | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-5---model-selection-methodologies)                                                           | Project Assignment 1: Formulation and Baseline (due Monday)                                                                           |
| 3    | Th: Sep 16       | [Performance Metrics](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture6-EvaluationMetrics.pptx)                                                               | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-6---evaluationperformance-metrics)                                                           |                                                                                                                                       |
| 4    | Tu: Sep 21       | [Feature Engineering and Imputation](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture7-Features.pptx)                                                         | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-7---feature-engineering-and-imputation)                                                      | Project Assignment 2:<br>Validation set up<br>Initial pipeline with train and validation set(s) and baseline implemented (due Monday) |
| 4    | Th: Sep 23       | [Hands-on Session for ML Pipeline review](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture8-Machine-Learning-Pipelines.pptx)                                  |                                                                                                                                                                                   |                                                                                                                                       |
| 5    | Tu: Sep 28       | [Models/hyperparameters in practice](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture9-PracticalModeling-Hyperparameters.pptx)                                |                                                                                                                                                                                   | Project Assignment 3:<br>list of features and some subset implemented (due Monday)                                                    |
| 5    | Th: Sep 30       | [Temporal Model Selection](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture10-ModelSelection2.pptx)                                                           | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-10---model-validation-continued)                                                             |                                                                                                                                       |
| 6    | Tu: Oct 5        | [Module 1 Review: Applied ML - End to End Pipelines](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture11-Module1Review.pptx)                                   |                                                                                                                                                                                   | Project Assignment 4:<br>modeling results (due Monday)                                                                                |
| 6    | Th: Oct 7        | Mid-term - no class                                                                                                                                                         |                                                                                                                                                                                   |                                                                                                                                       |
| 7    | Tu: Oct 12       | [ML Ethics Issues Overview](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture12-EthicsOverview.pptx)                                                           | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-12---ml-ethics-and-fairness-overview)                                                        |                                                                                                                                       |
| 7    | Th: Oct 14       | No Class - Mid-semester break                                                                                                                                               |                                                                                                                                                                                   |                                                                                                                                       |
| 8    | Tu: Oct 19       | Review of modeling results                                                                                                                                                  |                                                                                                                                                                                   | Updated model results assignment (+ model selection) Due Monday                                                                       |
| 8    | Th: Oct 21       | Working session: model debugging and updates                                                                                                                                |                                                                                                                                                                                   |                                                                                                                                       |
| 9    | Tu: Oct 26       | [Interpretability: Intro and Overview, taxonomy<br><br>Understanding the Models](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture14-UnderstandingModels.pptx) | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-13---model-interpretability-overview)                                                        | Due Monday: Revisions to update 5 results                                                                                             |
| 9    | Th: Oct 28       | Interpretability Methods: Inherently Interpretable (GA2Ms, RiskSLIM, etc.)                                                                                                  | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-15---inherently-interpretable-methods)                                                       |                                                                                                                                       |
| 10   | Tu: Nov 2        | Interpretability Methods:: Post-Hoc Local/Feature-based (LIME, SHAP, MAPLE)                                                                                                 | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-16---post-hoc-local-explanations)                                                            |                                                                                                                                       |
| 10   | Th: Nov 4        | Interpretability Methods: Other methods (counterfactual, example-based, etc.)                                                                                               | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-17---other-interpretability-methods)                                                         | Interpretability Writeup Due on Friday                                                                                                |
| 11   | Tu: Nov 9        | [Fairness in ML Overview](Lectures/Lecture19-FairnessOverview.pptx)                                                                                                                                                    | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-19---intro-to-fairness)                                                                      |                                                                                                                                       |
| 11   | Th: Nov 11       | Fairness Methods: Pre-processing (removing sensitive attribute, sampling)                                                                                                   | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-20---pre-processing-fairml-methods)                                                          |                                                                                                                                       |
| 12   | Tu: Nov 16       | Fairness Methods: In-processing (Zafar, Celis, fairlearn, etc.)                                                                                                             | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-21---in-processing-fairml-methods)                                                           |                                                                                                                                       |
| 12   | Th:Nov 18        | Post-Processing: Hardt, LA, etc                                                                                                                                             | [Readings on github](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-22---post-process-fairml-methods)                                                            |                                                                                                                                       |
| 13   | Tu: Nov 23       | Module 3 Review: ML Fairness                                                                                                                                                | Readings on github                                                                                                                                                                |                                                                                                                                       |
| 13   | Th: Thanksgiving | Thanksgiving holiday                                                                                                                                                        |                                                                                                                                                                                   |                                                                                                                                       |
| 14   | Tu: Nov 30       | [Field Trials and Causality](https://github.com/dssg/MLinPractice/tree/main/Readings#lecture-24---field-trials-and-causality)                                               | Readings on github                                                                                                                                                                | Bias Writeup Due                                                                                                                      |
| 14   | Th: Dec 2        | Wrap-Up                                                                                                                                                                     |                                                                                                                                                                                   |                                                                                                                                       |
| 15   | Tu: Dec 7        | No Class - Finals Week                                                                                                                                                      |                                                                                                                                                                                   |                                                                                                                                       |
| 15   | Th: Dec 9        | No Class - Finals Week                                                                                                                                                      |                                                                                                                                                                                   | Final Research Writeup Due                                                                                                            |
