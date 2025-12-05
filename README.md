# 10718: Machine Learning in Practice

**Previous Versions:** [Fall 2023](https://github.com/dssg/MLinPractice/releases/tag/fall2023) | [Fall 2022](https://github.com/dssg/MLinPractice/releases/tag/fall2022) |  [Fall 2021](https://github.com/dssg/MLinPractice/releases/tag/fall2021) | [Fall 2020](https://github.com/dssg/MLinPractice/releases/tag/fall2020) | [Spring 2020](https://github.com/dssg/mlforpublicpolicylab/tree/Spring2020)

## Fall 2025: Tues & Thurs, 2:00-3:20 ([POS 153](https://maps.app.goo.gl/FSHeY1jTBVzpsztA8))

## Important 
 - **All content will be on github in this repo including [schedule](README.md#schedule) and [detailed syllabus](README.md#structure)**
 - **All assignments will be on, and submitted through [canvas](https://canvas.cmu.edu/courses/49132)**
 - **Class communication and announcements will be primarily through email and [piazza](https://piazza.com/cmu/fall2025/10718/home)**

## Class Description

This is a project-based course designed to provide students training and experience in solving real-world problems using machine learning, while exploring the interface, translation, and gaps between research and practice.

The goal of this course is to give students exposure to the nuance of using machine learning in the real-world, where common assumptions (like iid and stationarity) break down, and the growing needs for (and
limitations of) approaches that go beyond optimizing for simple model accuracy measures such as fairness, explainability, robustness, uncetainty quantification, etc. Through project assignments, lectures, discussions,
and readings, students will learn about and experience building machine learning systems for real-world problems (suing real-world data_, as well as applying and evaluating the utility of proposed methods for enhancing the
interpretability, uncertainty quantification, causal inference capabilities, robustness, and fairness of machine learning models. Students will develop skills in problem formulation, working with messy (aka real) data, making ML design choices appropriate for the problem at hand, model selection, model interpretability, understanding and
mitigating bias & disparities, and evaluating the impact of deployed models in the real-world. 

## Course Learning Objectives
- Design and Development: Learn how to design and develop end-to-end ML systems that tackle real-world problems
- Understand and Evaluate: the impact of various design choices across the machine learning workflow in the context of real-world problems.
- Take real-world questions involving data and evaluate or develop appropriate methods to answer these questions.
- Communications: Present technical material clearly, in spoken and written form, to various audiences

## People

### Instructor

| Rayid Ghani | 
| --- | 
| <img src="img/rayidphoto.png" width="200" /><br /> GHC 8023 <br /> **Office Hours:** <br />   Tuesday 12:30-1:30pm  <br /> Wednesday 4-5pm  <br /> Email me if you want to meet outside these hours | 

### Education Associate

|Daniel Bird | 
| --- | 
| <img src='img/Daniel Bird.jpeg' width="200" /> <br /> Office: GHC 8120   | 

### Teaching Assistants

|Chancharik Mitra | Namrata	Deka | Rohan Venkatesh Kashyap
| --- | --- | --- |
| <img src='img/Chancharik_Mitra.jpg' width="200" /> <br /> Office Hours: Tues 5pm and Thurs 11am GHC 8228   | <img src='img/Namrata Deka.jpg' width="200" /> <br /> Office Hours: Mon 4pm and Fri 10am GHC 8228   | <img src='img/Rohan.jpg' width="200" /> <br /> Office Hours: Tues 12:30pm and Wed 11am GHC 8228   | 

## Grading 
Project-related assignments
- Project update assignments (30%)
- Write-up on module 2 findings (15%)
- Group presentations (mid-semester and end of semester) (10%)

Midterm take-home exam (20%)

Final reflection write-up (5%)

Class attendance and participation in discussions (15%)

Weekly check-in and feedback forms (5%)

## Schedule

See the **[detailed syllabus](README.md#structure)** below for more details, including **links to required readings** and information about group projects, grading, and helpful optional readings.

| Week | Dates       | Topic                                                                                                                                        | Assignments                                                                                                                           | Readings                                                                                                                                                                                                                                                                                                    |
| ---- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Tu: Aug 26  | [Class Intro and Overview](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture1-ClassOverview.pptx)                               |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 1    | Th: Aug 28  | Why ML systems can fail in practice [post-class discussion recap slides]                                                                     |                                                                                                                                       | individual research: website,s blogs, papers, videos, news articles                                                                                                                                                                                                                                         |
| 2    | Tu: Sep 2   | [Scoping and Defining ML Projects](#ml-project-definition-and-scoping)                                                                       | Individual Assignment: Getting to know the class project (due tuesday)<br>Project Team Selection                                      | Required: [ML Project Scoping Guide<br>](https://datasciencepublicpolicy.org/our-work/tools-guides/data-science-project-scoping-guide/)Optional:Listed below                                                                                                                                                |
| 2    | Th: Sep 4   | [Getting, Storing, and Linking Data](#obtaining-storing-and-linking-data)                                                                    |                                                                                                                                       | Optional: Listed below                                                                                                                                                                                                                                                                                      |
| 3    | Tu: Sep 9   | Data Exploration                                                                                                                             | Assignment on Data Exploration (Due) and Team Pesentations on Data Exploration                                                        |                                                                                                                                                                                                                                                                                                             |
| 3    | Th: Sep 11  | [Analytical Formulation / Baselines](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture4-Formulation.pptx)                       |                                                                                                                                       | Required: [Dissecting Racial Bias in an Algorithm Used to Manage the Health of Populations](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/ObermeyerBias.pdf)<br>[<br>Problemn Formulation and Fairness](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/PassiFormulation.pdf)<br> |
| 4    | Tu: Sep 16  | [Model Selection Methodology](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture5-ModelSelection.pptx)                           | Project Assignment 1: Formulation and Baseline (due Monday)                                                                           | Required: [Cross-validation strategies for data with temporal, spatial, hierarchical, or phylogenetic structure<br>](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/RobertsCV.pdf)Optional: [See below](http://readme.md/#model-selection-methodology)                                         |
| 4    | Th: Sep 18  | [Performance Metrics](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture6-EvaluationMetrics.pptx)                                |                                                                                                                                       | Required: T[he Misuse of AUC: What High Impact Risk Assessment Gets Wrong](https://arxiv.org/abs/2305.18159)                                                                                                                                                                                                |
| 5    | Tu: Sep 23  | [Feature Engineering and Imputation](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture7-Features.pptx)                          | Project Assignment 2:<br>Validation set up<br>Initial pipeline with train and validation set(s) and baseline implemented (due Monday) |                                                                                                                                                                                                                                                                                                             |
| 5    | Th: Sep 25  | [ML Pipelines](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture8-Machine-Learning-Pipelines.pptx) (cancelled)                  |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 6    | Tu: Sep 31  | [Models/hyperparameters in practice](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture9-PracticalModeling-Hyperparameters.pptx) | Project Assignment 3:<br>list of features and some subset implemented (due Monday)                                                    |                                                                                                                                                                                                                                                                                                             |
| 6    | Th: Oct 2   | Team Presentations and Reviewing Modeling Results                                                                                            |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 7    | Tu: Oct 7   | Team Presentations                                                                                                                           | Project Assignment 4:<br>modeling results (due Monday)                                                                                |                                                                                                                                                                                                                                                                                                             |
| 7    | Th: Oct 9   | no class for midterm time                                                                                                                    | Take-Home Midterm Available                                                                                                           |                                                                                                                                                                                                                                                                                                             |
| 8    | Tu: Oct 14  | No Class - Mid-semester break                                                                                                                |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 8    | Th: Oct 16  | No Class - Mid-semester break                                                                                                                |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 9    | Tu: Oct 21  | [Team Presentations and Temporal Model Selection](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture10-ModelSelection2.pptx)     | Updated model results assignment (+ model selection) Due Tuesday                                                                      |                                                                                                                                                                                                                                                                                                             |
| 9    | Th: Oct 23  | [ML Ethics Issues Overview](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture12-EthicsOverview.pptx)                            |                                                                                                                                       | [Required: Princeton Ethics Case Study 6: Public Sector Data Analysis](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/Princeton-AI-Ethics-Case-Study-6.pdf)                                                                                                                                    |
| 10   | Tu: Oct 28  | [Understanding the Models](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture14-UnderstandingModels.pptx)                        |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 10   | Th: Oct 30  | [Fairness in ML](https://github.com/dssg/MLinPractice/blob/main/Lectures/Lecture19-FairnessOverview.pptx)                                    |                                                                                                                                       | Required: Listed below[<br>](https://datasciencepublicpolicy.org/our-work/tools-guides/data-science-project-scoping-guide/)Optional:Listed below                                                                                                                                                            |
| 11   | Tu: Nov 4   | No class - Election Day                                                                                                                      |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 11   | Th: Nov 6   | [Evaluating ML Systems in the Field](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture20-FieldValidation.pptx)                  |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 12   | Tu: Nov 11  | ML and Causal Inference                                                                                                                      |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 12   | Th: Nov 13  | [Interpretability](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture14-UnderstandingModels.pptx)                                | importances + cross tabs assignment due                                                                                               |                                                                                                                                                                                                                                                                                                             |
| 13   | Tu: Nov 18  | [Uncertainty Quantificaion](#uncertainty-quantification)                                                                                     |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 13   | Th: Nov 20  | [Domain Shift / Temporal Drift](#domain-shift-and-temporal-drift)                                                                            |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 14   | Tu: Nov 25  | [ML Ops](#ml-ops-and-deploying-ml-systems)                                                                                                   |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 14   | Th: Nov 27  | Thanksgiving holiday                                                                                                                         |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
| 15   | Tu: Dec 2   | Team Presentations                                                                                                                           | Module 2 Writeup Due                                                                                                                  |                                                                                                                                                                                                                                                                                                             |
| 15   | Th: Dec 4   | [Wrap-Up](https://github.com/dssg/MLinPractice/blob/main/Lectures/Lecture21-Wrapup.pptx). (and team presentations                            |                                                                                                                                       |                                                                                                                                                                                                                                                                                                             |
|      | Finals Week |                                                                                                                                              | Final Reflection Writeup Due                                                                                                          |                                                                                                                                                                                                                                                                                                             |


                                                                                                                  |



## Projects and Deliverables

Broadly, the course will be divided into two modules: 1) applied
end-to-end machine learning pipelines, 2) Key considerations when building ML systems in practice, such as interpretability, fairness, uncertainty quantification, privacy, MLOps. Throughout the course, students will work
in groups of 4 on an applied project based on a real-world problem to explore the ideas and methods covered in each module in detail. During the project, students will be responsible for several key deliverables:

  - Throughout the first module (covering applied ML pipelines), groups will submit short project update assignments weekly, anbd iterate based on feedback from the instructors.

  - At the end of the first module, there will be a take-home midterm exam focused on the concepts and skills emphasized in this portion of the course.

  - During the second half, each group will pick one topic (among a few choices listed below and chosen collaboeratively with the class), implement that into their project, and present their results (through a short write-up and a team presentation).

### More details about the class project

Public schools in the United States face large disparities in funding, often resulting in teachers and staff members filling these gaps by purchasing classroom supplies out of their own pockets. DonorsChoose is an online crowdfunding platform that tries to help alleviate this financial burden on teachers by allowing them to seek funding for projects and resources from the community (projects can include classroom basics like books and markers, larger items like lab equipment or musical instruments, specific experiences like field trips or guest speakers).

Projects on DonorsChoose expire after 4 months, and if the target funding level isn't reached, the project receives no funding. Since its launch in 2000, the platform has helped fund over 2 million projects at schools across the US, but about 1/3 of the projects that are posted nevertheless fail to meet their goal and go unfunded.

#### The Modeling Problem

For the purposes of the class project, \\DonorsChoose has hired a digital content expert who will review projects and help teachers improve their postings and increase their chances of reaching their funding threshold. Because this individualized review is a labor-intensive process, the digital content expert has ** time to review and support only 10% of the projects posted to the platform on a given day**.

You are working with DonorsChoose, and your task is to help this content expert focus their limited resources on projects that most need the help. As such, you want to build a model to identify projects that are least likely to be fully funded before they expire and pass them off to the digital content expert for review.

#### Data
[Download links and data set description](datadescription.md)

### More details about Module 2 

Module 2 will involve selecting one (or more) topic that you want to go deeper into once you've built an initial ML pipeline and a set of reasonable (correct and well-performing) models. This will involve exploring key considerations that are critical in real-world ML problems, including interpretablity, fairness, uncertainty quantification, robustness, causality, and drift. The assignment in Module 2 will start from the models you've already built and will involve two deliverables:

1. short write-up (under 4 pages) based on applying your selected topic to your class project.
- The need for this topic in your project (who will be the user and who will be impacted, and why it's important)
- What question are you trying to answer 
- Which methods within this topic did you choose to try, and why
- How was your implementation experience (easy to use package? difficulties in implementation?)
- Results - What did you find? Do you know if it worked? Will it help the downstream DonorsChoose team, teachers, or students?
- Your recommendations for DonorsChoose based on your work

2. Short 10-minute team presentation during the last week of class on yur findings


## Grace Days

Project teams receive 3 total grace days for use on their project deliverables. You may not use more than 1 grace day on any single assignment. We will automatically keep a tally of these grace days for you; they will be applied greedily. 

## Participation and Missing Days

Attendance in class and participation in class discussions is a large part of 10-718. Throughout the semester, your participation will be measured by your responses in class and via Slido. You are permitted to miss a maximum of 4 lectures in order to still be considered for full participation credit; more than this will begin to reduce your participation grade.

## Structure

Below is a preliminary schedule of the course, including the readings
that will be assigned for that week. Please be sure to have read and be
prepared to discuss the readings before the specified class session.
Most of these topics can be (and often are) the focus of entire courses
and generally, we’ll only scratch the surface, but hopefully inspire you
to delve deeper into areas that interest you (and you’ll find plenty of
open research questions in each). Optional readings are also listed for
most sessions, which may be of interest to students who wish to delve
deeper into a given area, as well as provide additional context for your
related project work.  
  
## MODULE 1: APPLYING ML TO PRACTICAL PROBLEMS**  

:calendar:	**Tuesday, August 26:**
### Introduction

  We’ll provide an introduction to the class, its goals, and an overview of the applied project we will be using as a motivating example throughout the semester.

:calendar:	**Thursday, August 28:**
### Why ML Systems Can Fail in Practice  

  We'll discuss real-world failure modes of ML systems, moving beyond model accuracy to system-level issues including data, deployment, governance, incentives, etc. The goal here is to encourage critical thinking about preventing failures and to motivate the topics to be covered during the rest of the semester.
  
:calendar:	**Tuesday, September 2:**
### ML Project Definition and Scoping

  In this session, we’ll talk about scoping, problem definition, and understanding and balancing organizational goals. Before we start doing technical ML work, a decision needs to be made about whether a given problem can and should be addressed with machine learning: is the problem significant, feasible to solve with ML, and of sufficient importance to the organization that they will devote resources to implementing the solution? How will success be measured? How will (often competing) goals of efficiency, effectiveness, and equity be balanced?
  
#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture2-Scoping.pptx)
  
#### Due Today: :warning:
1. Individual Assignment: Getting to know the class project data
2. Project team selections
       
#### Required Reading:

  [Data Science Project Scoping Guide](https://datasciencepublicpolicy.org/our-work/tools-guides/data-science-project-scoping-guide)
   
#### Optional Readings:

  [Fine-grained dengue forecasting using telephone triage services](https://nyunetworks.github.io/Pubs/rehman-science16.pdf) by Rehman, NA, et al. Sci. Adv. 2016.
  
  [Deconstructing Statistical Questions](http://stat688.bio5.org/sites/default/files/fall2014/hand-deconstructin.pdf)  by Hand, D.J. J. Royal Stat Soc. A 157(3) 1994. 

  Predictive Modeling for Public Health: Preventing Childhood Lead Poisoning* by Potash, E, et al. KDD 2015.

:calendar:	**Thursday, September 4**
### Obtaining, Storing, and Linking Data

  In this class, we will look at some of the nuances of obtaining and using data in real-world projects, including a discussion of the strengths and weaknesses of different options for data storage as well as the practical aspects of dealing with the linkage of records from many different sources.
  
#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture3-Data.pptx)**
   
####   Optional Readings:

  [Netflix’s Trillions Scale Real-time Data Infrastructure](https://zhenzhongxu.com/the-four-innovation-phases-of-netflixs-trillions-scale-real-time-data-infrastructure-2370938d7f01)

  [Real-time Data Infrastructure at Uber](https://arxiv.org/abs/2104.00087)
    
  [Data Matching](https://link.springer.com/book/10.1007%2F978-3-642-31164-2) by Christen, P. Springer (2012). Chapter 2: The Data Matching Process
  
  Big Data and Social Science* edited by Foster, Ghani, et al. [Chapter 4: Databases](https://textbook.coleridgeinitiative.org/chap-db.html)
  
  [Broken Promises of Privacy](https://heinonline.org/HOL/Page?handle=hein.journals/uclalr57&div=48&g_sent=1&casa_token=&collection=journals) by Ohm, P. UCLA Law Review. 2009. Introduction and Section 1.

:calendar:	**Tuesday, September 9**
### Data Exploration

  You're all familiar with the general concept and practice of data exploration. In this session, we'll learn about the use of data exploration, specifically in ML projects, and apply those ideas to our class project. Most of this session will be focused on team presentations on the data exploration assignment (see canvas).
  
#### Optional Readings:
  [Can Foundation Models Wrangle your Data](https://www.vldb.org/pvldb/vol16/p738-narayan.pdf)

:calendar:	**Thursday, September 11**
### Analytical Formulation and Baselines

  In this session, we’ll discuss the analytical formulation of applied
  projects. Distinct from the initial scoping, a true analytical
  formulation of your problem can only come after you have developed
  an understanding of the data at hand, which in turn will often
  result in a greater understanding of the problem itself. Here,
  you’ll ask how specifically your label (if relevant) is defined in
  the data, what types of information are available as features, and
  what baseline you’ll be measuring performance against. Very rarely
  is the appropriate baseline as simple as “random” or the
  population prevalence. Rather, it should reflect what would be
  expected to happen otherwise: perhaps a simple decision rule that an
  expert would come up with or even a pre-existing statistical model
  that the current effort is seeking to replace.  

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture4-Formulation.pptx)

**DUE MONDAY, SEPTEMBER 15:** Project Update 1 (Formulation and Baselines) :warning:

#### Required Readings:
   
  [Dissecting Racial Bias in an Algorithm Used to Manage the Health of Populations](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/ObermeyerBias.pdf) by Obermeyer, Z., Powers, B., et al. Science. 2019.
   
  [Problem Formulation and Fairness](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/PassiFormulation.pdf) by Passi and Barocas. FAT \* 2019.
   
#### Optional Readings:
  
  Always Start with a Stupid Model, No Exceptions* by Ameisen, E. Medium. [Available Online](https://blog.insightdatascience.com/always-start-with-a-stupid-model-no-exceptions-3a22314b9aaa)
   
  Create a Common-Sense Baseline First* by Ramakrishnan. Medium. [Available Online](https://towardsdatascience.com/first-create-a-common-sense-baseline-e66dbf8a8a47)
   
  Data Science for Business* by Provost and Fawcett. O’Reilly. 2013. Chapter 2: Business Problems and Data Science [Available Online](https://learning.oreilly.com/library/view/data-science-for/9781449374273/ch02.html)
   
:calendar:	**Tuesday, September 16**
### Model Selection Methodology 

  During this session, we’ll begin a discussion of model evaluation
  with a focus on validation strategies. Introductory machine learning
  classes tend to focus on techniques such as k-fold cross-validation
  to guard against over-fitting, but is this always the best approach
  in practice? How does your choice of validation strategy relate to
  the manner in which you are hoping your model will generalize?

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture5-ModelSelection.pptx)**
     
#### Required Reading:
  Cross-validation strategies for data with temporal, spatial, hierarchical, or phylogenetic structure* by Roberts, DR, Bahn,V, et al. Ecography 40:2017. [Available Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/RobertsCV.pdf)
   
#### Optional Readings:
   
  [Amazing Things Come From Having Many Good Models](https://arxiv.org/pdf/2407.04846)
       
  Time Series Nested Cross-Validation* by Cochrane, C. Medium.[Available Online] (https://medium.com/data-science/time-series-nested-cross-validation-76adba623eb9)
   
  The Secrets of Machine Learning* by Rudin, C. and Carlson, D. arXiv preprint: 1906.01998. 2019. [Available Online](https://arxiv.org/abs/1906.01998)
   
  Big Data and Social Science (2nd edition)* edited by Foster, Ghani, et al. Section 7.7 of Chapter 7: Machine Learning. [Available Online](https://textbook.coleridgeinitiative.org/chap-ml.html)

:calendar:	**Thursday, September 18**
### Model (Selection) Performance Metrics  

  In this class, we’ll introduce topics around choosing performance
  metrics and evaluating classifiers. In most cases, a vast array of
  methods — each with several tunable hyperparameters — can be
  used for your modeling question. How do you decide which
  models are better than others and how can you be confident this
  decision will generalize into the future when the model is deployed?
  How should you balance performance,
  explainability, and fairness when making these decisions? Are models
  that are performing equally well all learning the same patterns and
  generating the same predictions? How should you select one to deploy
  if they are not? In this class, we’ll begin to answer these
  questions, focusing on the choice of performance metrics and how they
  relate to your project’s goals, scope, and formulation.

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture6-EvaluationMetrics.pptx)**

####   Required Reading:
  [The Misuse of AUC, What High Impact Risk Assessment Gets Wrong](https://arxiv.org/abs/2305.18159)
  
#### Optional Reading:
   
  Transductive Optimization of Top k Precision* by Liu, LP, Dietterich, TG, et al. IJCAI 2016. [Available Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/LiuTransductiveTopK.pdf)

  **DUE MONDAY, SEPTEMBER 22:** Project Update 2 (Validation set-up; initial pipeline with train and validation sets and baseline implemented) :warning:

:calendar:	**Tuesday, September 23:**
### Feature Engineering and Imputation 

  In many real-world contexts (especially involving tabular data), expressing domain expertise through
  thoughtful feature engineering can dramatically improve model
  performance by understanding what underlying factors are likely to
  be predictive and helping the model find these relationships.
  Likewise, most data sets you’ll encounter in practice are littered
  with outliers, inconsistencies, and missingness. Handling these data
  issues in a smart way can be critical to a project’s success. This
  session will focus on these aspects of dealing with often messy and
  inconsistent data encountered in applied projects.

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture7-Features.pptx)**
  
####  Optional Readings:
   
  Missing Data Conundrum* by Akinfaderin, W. Medium. [Available Online](https://medium.com/ibm-data-science-experience/missing-data-conundrum-exploration-and-imputation-techniques-9f40abe0fd87)
   
  Feature Engineering for Machine Learning* by Zhang, A. and Casari, A. O’Reilly. 2018. Chapter 2: Fancy Tricks with Simple Numbers [Available Online](https://learning.oreilly.com/library/view/feature-engineering-for/9781491953235/)
   
  Missing-data imputation* by Gelman, A. [Available Online](http://www.stat.columbia.edu/~gelman/arm/missing.pdf)

:calendar:	**Thursday, September 25:**
### ML Pipelines  

  During this session, we’ll take some time to review the machine
  learning pipelines your teams have been building, providing feedback
  on structure, design decisions, and best practices.

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture8-Machine-Learning-Pipelines.pptx)**

**DUE MONDAY, SEPTEMBER 29:** Project Update 3 (List of implemented and planned features) :warning:

:calendar:	**Tuesday, September 30:**
### ML Modeling in Practice 

  This class will focus on some of the practical aspects of applying
  machine learning to real-world problems. In other classes, you have
  implemented and worked with a wide variety of machine learning
  methods, but where should you start when dealing with a real problem
  in practice? What is a “reasonable” hyperparameter grid to consider?
  What pitfalls might you encounter in these situations and how can
  you avoid them?

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture9-PracticalModeling-Hyperparameters.pptx)** 
  
:calendar:	**Thursday, Oct 2: Team Presentations and Feedback on Modeling Results**
**DUE MONDAY, OCTOBER 6:** Project Update 4 (Modeling Results) :warning:

:calendar:	**Tuesday, October 7:**
### Module 1 Review: Applied ML End-to-End Pipelines 

  In this session, we’ll take some time to step back and review the
  concepts we have covered so far, with the goals of helping ensure
  all the projects are on track for the second and third modules,
  preparing for next week’s concept-focused midterm exam, and
  highlighting what we see as the most important takeaways from this
  section of the course.

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture11-Module1Review.pptx)** 
    
####   Required Readings:
  Three Pitfalls to Avoid in Machine Learning* by Riley, P.  Nature. 527. 2019 (Comment) [Available Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/RileyPitfalls.pdf)
  
  Top 10 ways your Machine Learning models may have leakage* by Ghani, R. et al. DSSG Blog. [Available Online](http://www.dssgfellowship.org/2020/01/23/top-10-ways-your-machine-learning-models-may-have-leakage/)

:calendar:	**Thursday, October 9: No Class, Midterm Distributed**  
  We'll cancel class on this day to provide some extra time for working
  on the midterm and updating model results.

:calendar:	**Tuesday, October 14 and Thursday, October 16: NO CLASSES – Fall Break**  
    
  **DUE TUESDAY, OCTOBER 21:** Take-home midterm exam  :warning:
  **DUE TUESDAY, OCTOBER 21:** Project Update 5 (Updated Modeling Results and Model Selection)  :warning:

:calendar:	**Tuesday, October 21**
### Team Presentations and Temporal Model Selection**  
  During this class, we’ll continue our discussion from the previous
  week, delving into the details of winnowing down a large number of
  model specifications to one or a handful that perform “best” for
  some definition of “best”. In particular, we’ll focus on the common
  case of machine learning problems with a strong temporal component
  and the desire to balance performance and stability in model
  selection.

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture10-ModelSelection2.pptx)**  
  
### Optional Reading:

  Evaluating and Comparing Classifiers* by Stapor, K. CORES 2017. [Available Online](https://link.springer.com/chapter/10.1007/978-3-319-59162-9_2)

## MODULE 2: Key Considerations Beyond Model Accuracy

This module will focus on topics such as ethics, interpretability, fairness, robustness, privacy, causality, field trials, uncertainty quantification, and supporting decision-makers. The topics to be covered will be selected collaboratively as we progress through the semester.

:calendar:	**Thursday, October 23:**
### ML Ethics Overview  

  In this session, we’ll discuss ethical issues in
  machine learning, focusing on the broader landscape of topics in
  this area, including questions around privacy, transparency, and
  accountability. Note that we’ll spend some time in class discussing
  the case study linked below, so please be sure to have read and
  thought about it before class. We will have a surprise (hopefully, fun) activity in class instead of a lecture session.
  
#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture12-EthicsOverview.pptx)**  

####  Required Readings:
    
  [Princeton Ethics Case Study 6: Public Sector Data Analysis](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/Princeton-AI-Ethics-Case-Study-6.pdf)

####   Optional Readings:
    
  Ethics and Data Science* by Loukides, M., Mason, H., and Patil,  D.J. O’Reilly (2018). Entire Book (don’t worry, it’s short\!) [Available Online](https://www.oreilly.com/library/view/ethics-and-data/9781492043898/?ar)
        (When prompted to select institution, select ’Not listed? Click
        here’ and enter your CMU email address to access content)

:calendar:	**Tuesday, October 28:**
### Practical Understanding of ML Models: What did my model learn? 

  During this session, we'll be introducing some simple and practical analyses to
  perform after the modeling process, and what it means to compare
  performance across model specifications. These methods can help
  provide a basic understanding of how your model is distinguishing
  between predicted classes and play an important role in detecting
  bugs such as leakage.

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture14-UnderstandingModels.pptx)  

:calendar:	**Thursday, October 30:**
### Introduction to ML and Fairness

  In this class, we’ll introduce topics in ML fairness, where we will
  focus our methods deep dives for the remainder of the semester: Just
  as important as assessing whether your model is making accurate
  predictions is determining whether it is doing so in a fair manner.
  But what do we mean by fairness? How can you measure it, and what
  can you do to mitigate any disparities you might find? Where in your
  pipeline can bias be introduced? (spoiler: everywhere). This class
  will provide a very brief introduction to the expansive field of
  FairML.

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture19-FairnessOverview.pptx)** 
      
####  Required Readings:
    
  Fairness Definitions Explained* by Verma, S and Rubin, J. [Available  Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/VermaFairnessDefn.pdf)
    
  A Theory of Justice* by Rawls, J. 1971. Chapter 1: Justice as Fairness, pp. 1-19. [Available Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/RawlsJustice.pdf)
        
####  Optional Readings:

  Racial Equity in Algorithmic Criminal Justice* by Huq, A. Duke Law Journal. 2018. [Available Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/HuqRacialEquity.pdf). Focus on sections: I.B.2, all of section II, III introduction, III.B, and III.D.3

  Is Algorithmic Affirmative Action Legal?* by Bent, JR. Georgetown Law Journal. 2019. [Available Online](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3372690)
    
  Does Mitigating ML’s Impact Disparity Require Treatment Disparity?* by Lipton, Z, McAuley, J, and Chouldechova, A. NeuRIPS 2018. [Available Online](http://papers.nips.cc/paper/8035-does-mitigating-mls-impact-disparity-require-treatment-disparity)
    
  Equality of Opportunity* by Roemer, JE and Trannoy, A. 2013. [Available Online](http://cowles.yale.edu/sites/default/files/files/pub/d19/d1921.pdf)

:calendar:	**Thursday and Tuesday November 6, 11:**
### Field Trials and Causality  
  In this session, we’ll briefly discuss field trials and issues of
  causality, critical for understanding how your model actually
  generalizes to real-world applications. Even with careful planning
  and handling of the data, the only way to truly understand how well
  your model works is by testing it in the field. Generally, you’re
  concerned not only with its predictiveness but the actual ability
  of the model to help the program achieve its goals, such as
  improving outcomes among the population it serves. Typically, this
  involves working closely with business owners to develop a field trial
  using either randomization or non-experimental methods depending on
  the constraints of the setting.

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture20-FieldValidation.pptx)** 
    
####  Required Readings:
    
  The seven tools of causal inference, with reflections on machine learning* by Pearl, J. Comm ACM. 2019 [Available Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/PearlCausality.pdf)

  [Running Randomized Controlled Trials](https://media.nesta.org.uk/documents/a_guide_to_rcts_-_igl_09aKzWa.pdf)
            
####  Optional Readings:
  
  Elements of Causal Inference* by Peters et al. MIT Press. Chapters 1 and 2. [Available Online (Open Access Link)](https://mitpress.mit.edu/books/elements-causal-inference)

  [The Econometrics of Randomized Experiments](https://www.sciencedirect.com/science/chapter/handbook/abs/pii/S2214658X16300174). Susan Athey and Guido Imbens
   
  [Breaking the Cycle of Incarceration With Targeted Mental Health Outreach: A Case Study in Machine Learning for Public Policy](https://arxiv.org/abs/2509.14129). Kit T Rodolfa, Erika Salomon, Jin Yao, Steve Yoder, Robert Sullivan, Kevin McGuire, Allie Dickinson, Rob MacDougall, Brian Seidler, Christina Sung, Claire Herdeman, Rayid Ghani
        
:calendar:	**Thursday November 13**
### Model Interpretability  
  Model interpretability can be thought of at two levels: global (how
  the model works in aggregate) and local (why an individual
  prediction came out as it did). In this class, we’ll focus on the
  bigger picture: discussing the landscape of model interpretability
  as well as different use cases and users.  
  
#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture13-InterpretabilityOverview.pptx)
      
####  Required Readings:
    
  Explainable Machine Learning for Public Policy: Use Cases, Gaps, and Research Directions* by Amarasinghe, K., et al. arXiv preprint: arxiv/2010.14374 [Available Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/AmarasingheExplainable.pdf)
    
  Benchmarking and Survey of Explanation Methods for Black Box Models* by Bodria, F., et al. arXiv preprint: arxiv/2102.13076 [Available Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/BodriaExplainable.pdf)

 
:calendar:	**Thursday November 18:**
### Uncertainty Quantification
  We will focus on understanding what kinds of uncertainty matter, how to estimate them, and how to act on them when deploying or governing ML systems. This will involve:
  1. Distinguishing between different types of uncertainty (aleatoric, epistemic, systemic, social).
  2. Implementing and interpreting basic techniques for quantifying model uncertainty.
  3. Communicating uncertainty effectively to decision-makers.
  4. Evaluating whether an ML system is robust and trustworthy in the face of uncertainty.

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/UncertaintyQuantification.pptx)

####  Required Reading:

  Aleatoric and Epistemic Uncertainty in Machine Learning: An Introduction to Concepts and Methods, Sections 1-3, by Hüllermeier and Waegeman. [Available Online](https://arxiv.org/pdf/1910.09457.pdf)
    
:calendar:	**Tuesday November 23:**
### Domain Shift and Temporal Drift
 
#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/temporal%20drift%20and%20domain%20shift.pptx)

#### Readings:

  Temporal quality degradation in AI models[Available Online](https://www.nature.com/articles/s41598-022-15245-z)
  
  Reliable and Trustworthy Machine Learning for Health Using Dataset Shift Detection [Available Online](https://proceedings.neurips.cc/paper_files/paper/2021/file/17e23e50bedc63b4095e3d8204ce063b-Paper.pdf)
  
  In Search of Lost Domain Generalization[Available Online](https://openreview.net/pdf?id=lQdXeXDoWtI)
      
:calendar:	**Thursday November 25:**
### ML Ops and Deploying ML Systems

#### [Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/mlops.pptx)

  Readings (in slides)
    
:calendar:	**Tuesday December 2 and Thursday December 4:**
### Wrap-up and Team Presentations
 

## More Resources
The Global Communication Center (GCC) can provide
assistance with the written or oral communication assignments in this
class. The GCC is a free service, open to all students, and located in
Hunt Library. You can learn more on the GCC website:
[cmu.edu/gcc](http://www.cmu.edu/gcc).  

## Your Responsibilities

**Attendance:** Because much of this course is focused on discussion
with your classmates, attending each session is important to both your
ability to learn from the course and to contribute to what others get
out of it as well. As such, you’ll be expected to attend every session
and your participation will factor into your grade as described above.
Should anything come up that will require you to miss a class (illness,
conferences, etc), please let one of the course staff know in advance.  

**Academic Integrity:** Violations of class and university academic
integrity policies will not be tolerated. Any instances of copying,
cheating, plagiarism, or other academic integrity violations will be
reported to your advisor and the dean of students in addition to
resulting in an immediate failure of the course.  

**AI Use Policy:**  We want this class to reflect what solving problems with ML in the real world looks like, which means different policies depending on 1) where you're working 2) the data you’re using, and 3) the privacy and confidentiality requirements. For the data we are using in this class, as long as you don't share or upload any confidential information to any AI tool (on the web), you can use any tool you want. You're accountable for the output and the work you submit. Know that a lot of these models are trained on pretty bad ML code and practices :)

We also want this class to help you understand what the AI tools are good for, where they fall short, and how to best use them to solve real-world problems. So use them, but be skeptical, review and test the output, and be ready to share what you find with others in the class.

**tl;dr**
- You can use anything you want, but you're accountable and responsible for what you submit
- Be prepared to disclose and share what you used and how you used it so others can learn

## Resources

**Students with Disabilities:** We value inclusion and will work to
ensure that all students have the resources they need to fully
participate in our course. Please use the Office of Disability
Resource’s online system to notify us of any necessary accommodations
as early in the semester as possible. If you suspect that you have a
disability but are not yet registered with the Office of Disability
Resources, you can contact them at <access@andrew.cmu.edu>  

**Health and Wellness:** As a student, you may experience a range of
challenges that can interfere with learning, such as strained
relationships, increased anxiety, substance use, feeling down,
difficulty concentrating and/or lack of motivation. These mental health
concerns or stressful events may diminish your academic performance
and/or reduce your ability to participate in daily activities. CMU
services are available, and treatment does work.  
All of us benefit from support during times of struggle. There are many
helpful resources available on campus and an important part of the
college experience is learning how to ask for help. Asking for support
sooner rather than later is almost always helpful.  

If you or anyone you know experiences any academic stress, difficult
life events, or feelings like anxiety or depression, we strongly
encourage you to seek support. Counseling and Psychological Services
(CaPS) is here to help: call 412-268-2922 and visit their website at
[cmu.edu/counseling/](http://www.cmu.edu/counseling/). Consider reaching
out to a friend, faculty or family member you trust for help getting
connected to the support that can help.  

If you or someone you know is feeling suicidal or in danger of
self-harm, call someone immediately, day or night:  
CaPS: 412-268-2922  
Re:solve Crisis Network: 888-796-8226  

If the situation is life threatening, call the police  
On campus: CMU Police: 412-268-2323  
Off campus: 911  

**Discrimination and Harassment:** Everyone has a right to feel safe and
respected on campus. If you or someone you know has been impacted by
sexual harassment, assault, or discrimination, resources are available
to help. You can make a report by contacting the University’s Office of
Title IX Initiatives by email (<tix@andrew.cmu.edu>) or phone
(412-268-7125).  

Confidential reporting services are available through the [Counseling
and Psychological Services](http://www.cmu.edu/counseling/) and
[University Health
Center](http://www.cmu.edu/health-services/index.html), as well as the
Ethics Reporting Hotline at 877-700-7050 or
[www.reportit.net](http://www.reportit.net/) (user name: tartans;
password: plaid).  
You can learn more about these options, policies, and resources by
visiting the University’s Title IX Office webpage at
<https://www.cmu.edu/title-ix/index.html>  
In case of an emergency, contact University Police 412-268-2323 on
campus or call 911 off campus.  

**[Student Academic Success Center
(SASC)](https://www.cmu.edu/student-success/)**

SASC focuses on creating spaces for students to engage in their
coursework and approach learning through a variety of group and
individual tutoring options. They offer many opportunities for students
to deepen their understanding of who they are as learners,
communicators, and scholars. Their
[workshops](https://www.cmu.edu/student-success/programs/workshops/index.html)
are free to the CMU community and meet the needs of all disciplines and
levels of study. SASC programs to support student learning include the
following (program titles link to webpages):

  - [Academic
    Coaching](https://www.cmu.edu/student-success/programs/coaching.html)
    – This program provides holistic, one-on-one peer support and group
    workshops to help undergraduate and graduate students implement
    habits for success. Academic Coaching assists students with time
    management, productive learning and study habits, organization,
    stress management, and other skills. Request an initial consultation
    [here](https://docs.google.com/forms/d/e/1FAIpQLSfMAnCWkyPdXRb0zOsMar7nzpUau8hqN_gIFm3OISY5QMWwyw/viewform).

  - [Peer
    Tutoring](https://www.cmu.edu/student-success/programs/tutoring.html)
    – Peer Tutoring is offered in two formats for students seeking
    support related to their coursework. Drop-In tutoring targets our
    highest demand courses through regularly scheduled open tutoring
    sessions during the fall and spring semesters. Tutoring by
    appointment consists of ongoing individualized and small group
    sessions.You can utilize tutoring to discuss course related content,
    clarify and ask questions, and work through practice problems. Visit
    the
    [webpage](https://www.cmu.edu/student-success/programs/tutoring.html)
    to see courses currently being supported by Peer Tutoring.

  - [Communication
    Support](https://www.cmu.edu/student-success/programs/communication-support/index.html)
    – Communication Support offers free one-on-one communication
    consulting as well as group workshops to support strong written,
    oral, and visual communication in texts including IMRaD and
    thesis-driven essays, data-driven reports, oral presentations,
    posters and visual design, advanced research, application materials,
    grant proposals, business and public policy documents, data
    visualisation, and team projects. Appointments are available to
    undergraduate and graduate students from any discipline at CMU.
    Schedule an
    [appointment](https://www.cmu.edu/student-success/programs/communication-support/make-an-appointment.html)
    on their website (in-person, zoom synchronous, or recorded video),
    attend a
    [workshop](https://www.cmu.edu/student-success/calendar.html), or
    consult [handouts or
    videos](https://www.cmu.edu/student-success/other-resources/index.html)
    to strengthen communication skills.

  - [Language and Cross-Cultural
    Support](https://www.cmu.edu/student-success/programs/language-support/index.html)
    – This program supports students seeking help with language and
    cross-cultural skills for academic and professional success through
    individual and group sessions. Students can get assistance with
    writing academic emails, learning expectations and strategies for
    clear academic writing, pronunciation, grammar, fluency, and more.
    Make an
    [appointment](https://docs.google.com/forms/d/e/1FAIpQLSfMAnCWkyPdXRb0zOsMar7nzpUau8hqN_gIFm3OISY5QMWwyw/viewform)
    with a Language Development Specialist to get individualized
    coaching.

  - [Supplemental Instruction
    (SI)](https://www.cmu.edu/student-success/programs/supp-inst.html) –
    This program offers a non-remedial approach to learning in
    historically difficult courses at CMU. It utilizes a peer-led
    collaborative group study approach to help students succeed and is
    facilitated by an SI leader, a CMU student who has successfully
    completed the course. SI offers a way to connect with other students
    studying the same course, a guaranteed weekly study time that
    reinforces learning and retention of information, as well as a place
    to learn and integrate study tools and exam techniques specific to a
    course. Visit the website to see courses with SI available
    [here](https://www.cmu.edu/student-success/programs/supp-inst.html).
