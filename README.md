# 10718: Machine Learning in Practice

**Previous Versions:** 
- **[Spring 2020](https://github.com/dssg/mlforpublicpolicylab/tree/Spring2020)**
- **[Fall 2020](https://github.com/dssg/MLinPractice/releases/tag/fall2020)**


### Fall 2021: Tues & Thurs, 4:40-6:00pm ([MM A14](https://goo.gl/maps/F84XABGawXvjms149)), Lab Section: Wednesday 4:40-6:00pm ([MM A14](https://goo.gl/maps/F84XABGawXvjms149))

### Important 
 - **All content will be on github in this repo including [schedule](README.md#schedule) and [tech setup instructions](techhelp/)**
 - **All assignments will be on and submitted through [canvas](https://canvas.cmu.edu/courses/25316)**
 - **Class communication and announcements will be primarily through Slack**

This is a project-based course designed to provide students training and experience in solving real-world problems using machine learning, exploring the interface between research and practice, with a particular focus on topics in fairness and explainability.

The goal of this course is to give students exposure to the nuance of applying machine learning to the real-world, where common assumptions (like iid and stationarity) break down, and the growing needs for (and limitations of) approaches to improve fairness and explainability of these applications. Through project assignments, lectures, discussions, and readings, students will learn about and experience building machine learning systems for real-world problems and data, as well as applying and evaluating the utility of proposed methods for enhancing the interpretability and fairness of machine learning models. Through the course, students will develop skills in problem formulation, working with messy data, making ML design choices appropriate for the problem at hand, model selection, model interpretability, understanding and mitigating algorithmic bias \& disparities, and evaluating the impact of deployed models.

**[DRAFT SYLLABUS](/syllabus.pdf)**

## People

### Instructors

| Rayid Ghani | Kit Rodolfa |
| --- | --- |
| <img src='http://www.datasciencepublicpolicy.org/wp-content/uploads/2018/05/RayidGhani-012-400x400.jpg' width='200' height='200' /> <br /> GHC 8023 <br /> Office Hours: <br />  TBD | <img src='/kit_rodolfa.png' /> <br /> GHC 8018 <br /> Office Hours: <br /> TBD |

### Teaching Assistants
| Riyaz Panjwani | Abhishek Parikh |
| --- | --- | 
| Photo <br /> Office Hours: <br /> TBD | Photo <br /> Office Hours: <br /> TBD |

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

| Week | Dates            | Topic                                                                         | Required Readings                                                                                                                                                                 | Assignments                                                                                                                           |
| ---- | ---------------- | ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Tu: Aug 31       | Class Intro and Overview                                                      |                                                                                                                                                                                   |                                                                                                                                       |
| 1    | Th: Sep 2        | ML Project Scoping                                                            | [ML Project Scoping Guide](http://www.datasciencepublicpolicy.org/home/resources/data-science-project-scoping-guide/)                                                             | Project Team Selection                                                                                                                |
| 2    | Tu: Sep 7        | Getting, Storing, and Linking Data                                            | [Optional readings on github](https://github.com/dssg/MLinPractice/blob/main/Readings/README.md#lecture-3---acquiring-storing-and-linkg-data-and-downstream-ethical-implications) |                                                                                                                                       |
| 2    | Th: Sep 9        | Analytical Formulation / Baselines                                            | [List on github](https://github.com/dssg/MLinPractice/blob/main/Readings/README.md#lecture-4---analytical-formulation-and-baselines)                                              |                                                                                                                                       |
| 3    | Tu: Sep 14       | Model Selection Methodology                                                   |                                                                                                                                                                                   | Project Assignment 1: Formulation and Baseline (due Monday)                                                                           |
| 3    | Th: Sep 16       | Performance Metrics                                                           |                                                                                                                                                                                   |                                                                                                                                       |
| 4    | Tu: Sep 21       | Feature Engineering and Imputation                                            |                                                                                                                                                                                   | Project Assignment 2:<br>Validation set up<br>Initial pipeline with train and validation set(s) and baseline implemented (due Monday) |
| 4    | Th: Sep 23       | Hands-on Session for ML Pipeline review                                       |                                                                                                                                                                                   |                                                                                                                                       |
| 5    | Tu: Sep 28       | Models/hyperparameters in practice                                            |                                                                                                                                                                                   | Project Assignment 3:<br>list of features and some subset implemented (due Monday)                                                    |
| 5    | Th: Sep 30       | Temporal Model Selection                                                      |                                                                                                                                                                                   |                                                                                                                                       |
| 6    | Tu: Oct 5        | Module 1 Review: Applied ML - End to End Pipelines                            |                                                                                                                                                                                   | Project Assignment 4:<br>modeling results (due Monday)                                                                                |
| 6    | Th: Oct 7        | Mid-term week - no class                                                      |                                                                                                                                                                                   | Mid-term exam due Friday                                                                                                              |
| 7    | Tu: Oct 12       | Interpretability: Intro and Overview, taxonomy                                |                                                                                                                                                                                   |                                                                                                                                       |
| 7    | Th: Oct 14       | No Class - Mid-semester break                                                 |                                                                                                                                                                                   |                                                                                                                                       |
| 8    | Tu: Oct 19       | Understanding the Models                                                      |                                                                                                                                                                                   |                                                                                                                                       |
| 8    | Th: Oct 21       | Interpretability Methods: Inherently Interpretable (GA2Ms, RiskSLIM, etc.)    |                                                                                                                                                                                   |                                                                                                                                       |
| 9    | Tu: Oct 26       | Interpretability Methods:: Post-Hoc Local/Feature-based (LIME, SHAP, MAPLE)   |                                                                                                                                                                                   |                                                                                                                                       |
| 9    | Th: Oct 28       | Interpretability Methods: Other methods (counterfactual, example-based, etc.) |                                                                                                                                                                                   |                                                                                                                                       |
| 10   | Tu: Nov 2        | Module 2 Review: ML Interpretability                                          |                                                                                                                                                                                   |                                                                                                                                       |
| 10   | Th: Nov 4        | ML Ethics Issues Overview                                                     |                                                                                                                                                                                   | Interpretability Writeup Due on Friday                                                                                                |
| 11   | Tu: Nov 9        | Fairness in ML Overview                                                       |                                                                                                                                                                                   |                                                                                                                                       |
| 11   | Th: Nov 11       | Fairness Methods: Pre-processing (removing sensitive attribute, sampling)     |                                                                                                                                                                                   |                                                                                                                                       |
| 12   | Tu: Nov 16       | Fairness Methods: In-processing (Zafar, Celis, fairlearn, etc.)               |                                                                                                                                                                                   |                                                                                                                                       |
| 12   | Th:Nov 18        | Post-Processing: Hardt, LA, etc                                               |                                                                                                                                                                                   |                                                                                                                                       |
| 13   | Tu: Nov 23       | Module 3 Review: ML Fairness                                                  |                                                                                                                                                                                   |                                                                                                                                       |
| 13   | Th: Thanksgiving | Thanksgiving holiday                                                          |                                                                                                                                                                                   |                                                                                                                                       |
| 14   | Tu: Nov 30       | Field Trials and Causality                                                    |                                                                                                                                                                                   | Bias Writeup Due                                                                                                                      |
| 14   | Th: Dec 2        | Wrap-Up                                                                       |                                                                                                                                                                                   |                                                                                                                                       |
| 15   | Tu: Dec 7        | No Class - Finals Week                                                        |                                                                                                                                                                                   |                                                                                                                                       |
| 15   | Th: Dec 9        | No Class - Finals Week                                                        |                                                                                                                                                                                   | Final Research Writeup Due                                                                                                            |


