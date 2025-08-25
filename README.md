# 10718: Machine Learning in Practice

**Previous Versions:** [Fall 2023](https://github.com/dssg/MLinPractice/releases/tag/fall2023) | [Fall 2022](https://github.com/dssg/MLinPractice/releases/tag/fall2022) |  [Fall 2021](https://github.com/dssg/MLinPractice/releases/tag/fall2021) | [Fall 2020](https://github.com/dssg/MLinPractice/releases/tag/fall2020) | [Spring 2020](https://github.com/dssg/mlforpublicpolicylab/tree/Spring2020)


### Fall 2025: Tues & Thurs, 2:00-3:20 ([POS 153](https://maps.app.goo.gl/FSHeY1jTBVzpsztA8))

### Important 
 - **All content will be on github in this repo including [schedule](README.md#schedule) and [detailed syllabus](README.md#structure)**
 - **All assignments will be on and submitted through [canvas](https://canvas.cmu.edu/courses/49132)**
 - **Class communication and announcements will be primarily through email and [piazza](https://piazza.com/cmu/fall2025/10718/home)**

### Class Description

This is a project-based course designed to provide students training and
experience in solving real-world problems using machine learning,
while exploring the interface between research and practice.

The goal of this course is to give students exposure to the nuance of
using machine learning in the real-world, where common assumptions
(like iid and stationarity) break down, and the growing needs for (and
limitations of) approaches that go beyond optimizing for simple model accuracy measures and explore notions of fairness, explainability, robustness, etc. Through project assignments, lectures, discussions,
and readings, students will learn about and experience building machine
learning systems for real-world problems and data, as well as applying
and evaluating the utility of proposed methods for enhancing the
interpretability and fairness of machine learning models. Through the
course, students will develop skills in problem formulation, working
with messy (aka real) data, making ML design choices appropriate for the problem at
hand, model selection, model interpretability, understanding and
mitigating bias & disparities, and evaluating the impact of
deployed models. 

### Course Learning Objectives
 - Design and evaluate novel combinations of learning algorithms.
 - Take real-world questions involving data and evaluate or develop appropriate methods to answer these questions.
 - Present technical material clearly, in spoken and written form.

## People

### Instructor

| Rayid Ghani | 
| --- | 
| <img src="img/rayidphoto.png" width="200" /><br /> GHC 8023 <br /> Office Hours: <br />   Tuesday 12:30-1:30pm Wednesday 3-4pm  | 

### Education Associate

|Daniel Bird | 
| --- | 
| <img src='img/Daniel Bird.jpeg' width="200" /> <br /> Office: GHC 8020   | 

### Teaching Assistants

|Chancharik Mitra | Namrata	Deka | Rohan Venkatesh Kashyap
| --- | --- | --- |
| <img src='img/Chancharik_Mitra.jpg' width="200" /> <br /> Office Hours: TBD   | <img src='img/Namrata Deka.jpg' width="200" /> <br /> Office Hours: TBD   | <img src='img/Rohan.jpg' width="200" /> <br /> Office Hours: TBD   | 

## Grading 

Project update assignments (25%)

Midterm take-home exam (20%)

Write-up on interpretability findings (10%)

Write-up on fairness findings (10%)

Group presentation (5%)

Final reflection write-up (10%)

Class attendance and participation in discussions (15%)

Submitting weekly check-in and feedback forms (5%)

## Schedule

See the **[detailed syllabus](README.md#structure)** below for much more detail as well, including **links to required readings** and information about group projects, grading, and helpful optional readings.

| Week | Dates       | Topic                                                                                                                                        | Assignments                                                                                                                           |
| ---- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Tu: Aug 26  | [Class Intro and Overview](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture1-ClassOverview.pptx)                               |                                                                                                                                       |
| 1    | Th: Aug 28  | Why can ML systems fail in practice                                                                                                          |                                                                                                                                       |
| 2    | Tu: Sep 2   | [Scoping ML Projects](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture2-Scoping.pptx)                                          | Individual Assignment: Getting to know the class project (due tuesday)                                                                |
| 2    | Th: Sep 4   | [Getting, Storing, and Linking Data](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture3-Data.pptx)                              | Project Team Selection                                                                                                                |
| 3    | Tu: Sep 9   | Data Exploration                                                                                                                             | Short Assignment on Data Exploration                                                                                                  |
| 3    | Th: Sep 11  | [Analytical Formulation / Baselines](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture4-Formulation.pptx)                       |                                                                                                                                       |
| 4    | Tu: Sep 16  | [Model Selection Methodology](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture5-ModelSelection.pptx)                           | Project Assignment 1: Formulation and Baseline (due Monday)                                                                           |
| 4    | Th: Sep 18  | [Performance Metrics](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture6-EvaluationMetrics.pptx)                                |                                                                                                                                       |
| 5    | Tu: Sep 23  | [Feature Engineering and Imputation](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture7-Features.pptx)                          | Project Assignment 2:<br>Validation set up<br>Initial pipeline with train and validation set(s) and baseline implemented (due Monday) |
| 5    | Th: Sep 25  | [ML Pipelines](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture8-Machine-Learning-Pipelines.pptx)                              |                                                                                                                                       |
| 6    | Tu: Sep 31  | [Models/hyperparameters in practice](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture9-PracticalModeling-Hyperparameters.pptx) | Project Assignment 3:<br>list of features and some subset implemented (due Monday)                                                    |
| 6    | Th: Oct 2   | [Temporal Model Selection](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture10-ModelSelection2.pptx)                            |                                                                                                                                       |
| 7    | Tu: Oct 7   | [Module 1 Review: Applied ML - End to End Pipelines](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture11-Module1Review.pptx)    | Project Assignment 4:<br>modeling results (due Monday)                                                                                |
| 7    | Th: Oct 9   | no class for midterm time                                                                                                                    | Take-Home Midterm Available                                                                                                           |
| 8    | Tu: Oct 14  | No Class - Mid-semester break                                                                                                                |                                                                                                                                       |
| 8    | Th: Oct 16  | No Class - Mid-semester break                                                                                                                |                                                                                                                                       |
| 9    | Tu: Oct 21  | Common ML Pitfalls                                                                                                                           | Add assignment: importances and cross tabs                                                                                            |
| 9    | Th: Oct 23  | [ML Ethics Issues Overview](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture12-EthicsOverview.pptx)                            | Updated model results assignment (+ model selection) Due Monday                                                                       |
| 10   | Tu: Oct 28  | [Understanding the Models](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture14-UnderstandingModels.pptx)                        | importances + cross tabs assignment due                                                                                               |
| 10   | Th: Oct 30  | [Interpretability](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture14-UnderstandingModels.pptx)                                |                                                                                                                                       |
| 11   | Tu: Nov 4   | No class - Election Day                                                                                                                      |                                                                                                                                       |
| 11   | Th: Nov 6   | [Fairness in ML](https://github.com/dssg/MLinPractice/blob/main/Lectures/Lecture19-FairnessOverview.pptx)                                    |                                                                                                                                       |
| 12   | Tu: Nov 11  | [Fairness in ML](https://github.com/dssg/MLinPractice/blob/main/Lectures/Lecture19-FairnessOverview.pptx)                                    |                                                                                                                                       |
| 12   | Th: Nov 13  | ML and Causal Inference                                                                                                                      |                                                                                                                                       |
| 13   | Tu: Nov 18  | Evaluating ML Systems in the Field                                                                                                           |                                                                                                                                       |
| 13   | Th: Nov 20  | ML Ops                                                                                                                                       |                                                                                                                                       |
| 14   | Tu: Nov 25  | Uncertainlty Quantificaion                                                                                                                   |                                                                                                                                       |
| 14   | Th: Nov 27  | Thanksgiving holiday                                                                                                                         |                                                                                                                                       |
| 15   | Tu: Dec 2   | TBD                                                                                                                                          | Writeup Due                                                                                                                           |
| 15   | Th: Dec 4   | [Wrap-Up](https://github.com/dssg/MLinPractice/blob/main/Lectures/Lecture21-Wrapup.pptx)                                                     |                                                                                                                                       |
|      | Finals Week |                                                                                                                                              | Final Reflection Writeup Due                                                                                                          |




## Projects and Deliverables
Broadly, the course will be divided into two modules: 1) applied
end-to-end machine learning pipelines, 2) Key considerations when building ML systems in practice such as interpretability,
fairness, uncertainty quantification, privacy, MLOps. Throughout the course, students will work
in groups of 4 on an applied project based on a real-world problem
to explore the ideas and methods covered in each module in detail.
During the project, students will be responsible for several key
deliverables:

  - Throughout the first module (covering applied ML pipelines), groups
    will submit short project update assignments on a weekly basis to
    get feedback on their approach and initial results.

  - At the end of the first module, there will be a take-home midterm
    exam focused on the concepts and skills emphasized in this portion
    of the course.

  - During the second half, each group will pick one topic (among a few choices) and implement that into their project and present their results (in person and a short writeup). 


## Grace Days
Project teams receive 3 total grace days for use on your project deliverables. You may not use more than 1 grace day on any single assignment. We will automatically keep a tally of these grace days for you; they will be applied greedily. 

## Participation and Missing Days
Attendance in class and participation in class discussions is a large part of 10-718. Throughout the semester your participation will be measured by your responses in class and via Slido. You are permitted to miss a maximum of 4 lectures in order to still be considered for full participation credit, more than this will begin to reduce your participation grade.

## Structure

Below is a preliminary schedule of the course, including the readings
that will be assigned for that week. Please be sure to have read and be
prepared to discuss the readings before the specified class session.
Most of these topics can be (and often are) the focus of entire courses
and generally, we’ll only scratch the surface, but hopefully inspire you
to delve deeper into areas that interest you (and you’ll find plenty of
open research questions in each). Optional readings are also listed for
most sessions which may be of interest to students who wish to delve
deeper into a given area as well as provide additional context for your
related project work.  
  
### MODULE 1: APPLYING ML TO PRACTICAL PROBLEMS**  

  - **Tuesday, August 29: Introduction**  
    During our initial meeting, we’ll provide an introduction to the
    class, its goals, and an overview of the applied project we will be
    using as a motivating example throughout the semester.

  - **Thursday, August 31: Project Scoping**  
    **DUE TODAY:** Project team selections  
      
    In this session, we’ll talk about scoping, problem definition, and
    understanding and balancing organizational goals. Well before the
    outset of technical work, a decision needs to be made about whether
    a given problem can and should be addressed with machine learning:
    is the problem significant, feasible to solve with a technical
    approach, and of sufficient importance to the organization that they
    will devote resources to implementing the solution? How will success
    be measured? How will (often competing) goals of efficiency,
    effectiveness, and equity be balanced? During this lecture, we’ll
    also touch on topics surrounding acquiring data and record linkage
    across systems.  
      
    Required Reading:
    
      - *Data Science Project Scoping Guide* [Available
        Online](http://www.datasciencepublicpolicy.org/home/resources/data-science-project-scoping-guide/)
    
    Optional Readings:
    
      - *Fine-grained dengue forecasting using telephone triage
        services* by Rehman, NA, et al. Sci. Adv. 2016. [Available
        Online](https://nyunetworks.github.io/Pubs/rehman-science16.pdf)
    
      - *Deconstructing Statistical Questions* by Hand, D.J. J. Royal
        Stat Soc. A 157(3) 1994. [Available
        Online](http://stat688.bio5.org/sites/default/files/fall2014/hand-deconstructin.pdf)
    
      - *Predictive Modeling for Public Health: Preventing Childhood
        Lead Poisoning* by Potash, E, et al. KDD 2015.

  - **DUE TUESDAY, SEPTEMBER 5:** Individual Assignment: Getting to know the class project data

  - **Tuesday, September 5: Obtaining, Storing, and Linking Data**  
    In this class, we will look at some of the nuances of obtaining and
    using data in real-world projects, including a discussion of the
    strengths and weaknesses of different options for data storage as
    well as the practical aspects of dealing with linkage of records
    from many different sources.  
      
    Optional Readings:
    
      - *Data Matching* by Christen, P. Springer (2012). Chapter 2: The
        Data Matching Process [Available
        Online](https://link.springer.com/book/10.1007%2F978-3-642-31164-2)
    
      - *Big Data and Social Science* edited by Foster, Ghani, et al.
        Chapter 4: Databases.
    
      - *Broken Promises of Privacy* by Ohm, P. UCLA Law Review. 2009.
        Introduction and Section 1. [Available
        Online](https://heinonline.org/HOL/Page?handle=hein.journals/uclalr57&div=48&g_sent=1&casa_token=&collection=journals)

  - **Thursday, September 7: Analytical Formulation and Baselines**  
    In this session, we’ll discuss the analytical formulation of applied
    projects. Distinct from the initial scoping, a true analytical
    formulation of your problem can only come after you have developed
    an understanding of the data at hand, which in turn will often
    result in a greater understanding of the problem itself. Here,
    you’ll ask how specifically your label (if relevant) is defined in
    the data, what types of information are available as features, and
    what baseline you’ll be measuring performance against. Very rarely
    is the appropriate baseline as simple as “random choice” or the
    population prevalence. Rather, it should reflect what would be
    expected to happen otherwise: perhaps a simple decision rule that an
    expert would come up with or even a pre-existing statistical model
    that the current effort is seeking to replace.  
      
    Required Readings:
    
      - *Dissecting Racial Bias in an Algorithm Used to Manage the
        Health of Populations* by Obermeyer, Z., Powers, B., et al.
        Science. 2019. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/ObermeyerBias.pdf)
    
      - *Problem Formulation and Fairness* by Passi and Barocas. FAT\*
        2019. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/PassiFormulation.pdf)
    
    Optional Readings:
    
      - *Always Start with a Stupid Model, No Exceptions* by Ameisen, E.
        Medium. [Available
        Online](https://blog.insightdatascience.com/always-start-with-a-stupid-model-no-exceptions-3a22314b9aaa)
    
      - *Create a Common-Sense Baseline First* by Ramakrishnan. Medium.
        [Available
        Online](https://towardsdatascience.com/first-create-a-common-sense-baseline-e66dbf8a8a47)
    
      - *Data Science for Business* by Provost and Fawcett. O’Reilly.
        2013. Chapter 2: Business Problems and Data Science [Available
        Online](https://learning.oreilly.com/library/view/data-science-for/9781449374273/ch02.html)

  - **DUE MONDAY, SEPTEMBER 11:** Project Update 1 (Formulation and
    Baselines)

  - **Tuesday, September 12: Model Selection Methodology**  
    During this session, we’ll begin a discussion of model evaluation
    with a focus on validation strategies. Introductory machine learning
    classes tend to focus on techniques such as k-fold cross-validation
    to guard against over-fitting, but is this always the best approach
    in practice? How does your choice of validation strategy relate to
    the manner in which you are hoping your model will generalize?  
      
    Required Reading:
    
      - *Cross-validation strategies for data with temporal, spatial,
        hierarchical, or phylogenetic structure* by Roberts, DR, Bahn,
        V, et al. Ecography 40:2017. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/RobertsCV.pdf)
    
    Optional Readings:
    
      - *Time Series Nested Cross-Validation* by Cochrane, C. Medium.
        [Available
        Online](https://towardsdatascience.com/time-series-nested-cross-validation-76adba623eb9)
    
      - *The Secrets of Machine Learning* by Rudin, C. and Carlson, D.
        arXiv preprint: 1906.01998. 2019. [Available
        Online](https://arxiv.org/abs/1906.01998)
    
      - *Big Data and Social Science (2nd edition)* edited by Foster,
        Ghani, et al. Section 7.7 of Chapter 7: Machine Learning. [Available
        Online](https://textbook.coleridgeinitiative.org/chap-ml.html)

  - **Thursday, September 14: Model Performance Metrics**  
    In this class, we’ll introduce topics around choosing performance
    metrics and evaluating classifiers. In most cases, a vast array of
    methods — each with a number of tunable hyperparameters — can be
    brought to bear on your modeling question. How do you decide which
    models are better than others and how can you be confident this
    decision will generalize into the future when the model is deployed?
    How should you balance considerations of performance,
    explainability, and fairness when making these decisions? Are models
    that are performing equally well all learning the same patterns and
    generating the same predictions? How should you select one to deploy
    if they are not? In this class, we’ll begin to answer these
    questions, focusing on the choice of performance metrics and how they
    relate to your project’s goals, scope, and formulation.  
      
    Required Reading:
    
      - *Transductive Optimization of Top k Precision* by Liu, LP,
        Dietterich, TG, et al. IJCAI 2016. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/LiuTransductiveTopK.pdf)

  - **DUE MONDAY, SEPTEMBER 18:** Project Update 2 (Validation set-up;
    initial pipeline with train and validation sets and baseline
    implemented)

  - **Tuesday, September 19: Feature Engineering and Imputation**  
    In many real-world contexts, expressing domain expertise through
    thoughtful feature engineering can dramatically improve model
    performance by understanding what underlying factors are likely to
    be predictive and helping the model find these relationships.
    Likewise, most data sets you’ll encounter in practice are littered
    with outliers, inconsistencies, and missingness. Handling these data
    issues in a smart way can be critical to a project’s success. This
    class will focus on these aspects of dealing with often messy and
    inconsistent data encountered in applied projects.  
      
    Optional Readings:
    
      - *Missing Data Conundrum* by Akinfaderin, W. Medium. [Available
        Online](https://medium.com/ibm-data-science-experience/missing-data-conundrum-exploration-and-imputation-techniques-9f40abe0fd87)
    
      - *Feature Engineering for Machine Learning* by Zhang, A. and
        Casari, A. O’Reilly. 2018. Chapter 2: Fancy Tricks with Simple
        Numbers [Available
        Online](https://learning.oreilly.com/library/view/feature-engineering-for/9781491953235/)
    
      - *Missing-data imputation* by Gelman, A. [Available
        Online](http://www.stat.columbia.edu/~gelman/arm/missing.pdf)

  - **Thursday, September 21:  ML Pipelines
    **  
    During this session, we’ll take some time to review the machine
    learning pipelines your teams have been building, providing feedback
    on structure, design decisions, and best practices.

  - **DUE MONDAY, SEPTEMBER 25:** Project Update 3 (List of implemented
    and planned features)

  - **Tuesday, September 26: ML Modeling in Practice**  
    This class will focus on some of the practical aspects of applying
    machine learning to real-world problems. In other classes, you have
    implemented and worked with a wide variety of machine learning
    methods, but where should you start when dealing with a real problem
    in practice? What is a “reasonable” hyperparameter grid to consider?
    What pitfalls might you encounter in these situations and how can
    you avoid them?  

  - **Thursday, September 28: Temporal Model Selection**  
    During this class, we’ll continue our discussion from the previous
    week, delving into the details of winnowing down a large number of
    model specifications to one or a handful that perform “best” for
    some definition of “best”. In particular, we’ll focus on the common
    case of machine learning problems with a strong temporal component
    and the desire to balance performance and stability in model
    selection.  
      
    Optional Reading:
    
      - *Evaluating and Comparing Classifiers* by Stapor, K. CORES 2017.
        [Available
        Online](https://link.springer.com/chapter/10.1007/978-3-319-59162-9_2)

  - **DUE MONDAY, OCTOBER 2:** Project Update 4 (Modeling Results)

  - **Tuesday, October 3: Reviewing Project Modeling Results**  
    In this class, we’ll take some time to look at the modeling results
    from the group projects, providing some feedback and advice for
    finalizing the models before applying interpretability methods to
    them.

   
  - **Thursday, October 5: Other ML Problem Templates**  
  

  - **DUE MONDAY, OCTOBER 9:** Project Update 5 (Updated Modeling
    Results and Model Selection)  

  - **Tuesday, October 10: Module I Review: Applied ML End-to-End
    Pipelines**  
    In this session, we’ll take some time to step back and review the
    concepts we have covered so far, with the goals of helping ensure
    all the projects are on track for the second and third modules,
    preparing for next week’s concept-focused midterm exam, and
    highlighting what we see as the most important takeaways from this
    section of the course.  
      
    Required Readings:
    
      - *Three Pitfalls to Avoid in Machine Learning* by Riley, P.
        Nature. 527. 2019 (Comment) [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/RileyPitfalls.pdf)
    
      - *Top 10 ways your Machine Learning models may have leakage* by
        Ghani, R. et al. DSSG Blog. [Available
        Online](http://www.dssgfellowship.org/2020/01/23/top-10-ways-your-machine-learning-models-may-have-leakage/)


  - **Thursday, October 12: No Class, Midterm Distributed**  
    We'll cancel class on this day to provide some extra time for working
    on the midterm and updating model results.

  - **Tuesday, October 17 and Thursday, October 19: NO CLASSES – Fall
    Break**  
      

### MODULE 2: UNDERSTANDING ML MODELS**  

  - **DUE TUESDAY, OCTOBER 24:** Take-home midterm exam  

  - **Tuesday, October 24: ML Ethics and Fairness Overview**  
    In this session, we’ll have a discussion about ethical issues in
    machine learning, focusing on the broader landscape of topics in
    this area, including questions around privacy, transparency, and
    accountability. Note that we’ll spend some time in class discussing
    the case study linked below, so please be sure to have read and
    thought about it before class.  
      
    Required Readings:
    
      - Princeton Ethics Case Study 6: Public Sector Data Analysis
        [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/Princeton-AI-Ethics-Case-Study-6.pdf)

    Optional Readings:
    
      - *Ethics and Data Science* by Loukides, M., Mason, H., and Patil,
        D.J. O’Reilly (2018). Entire Book (don’t worry – it’s short\!)
        [Available
        Online](https://www.oreilly.com/library/view/ethics-and-data/9781492043898/?ar)
        (When prompted to select institution, select ’Not listed? Click
        here’ and enter your CMU email address to access content)

  - **Thursday, October 26: Model Interpretability Overview**  
    Model interpretability can be thought of at two levels: global (how
    the model works in aggregate) and local (why an individual
    prediction came out as it did). In this class, we’ll focus on the
    bigger picture: discussing the landscape of model interpretability
    as well as different use cases and users.  
      
    Note that we’ll also post assignments for the Module II methods
    early this week so teams can begin implementing them for the deep
    dives beginning the following week.  
      
    Required Readings:
    
      - *Explainable Machine Learning for Public Policy: Use Cases,
        Gaps, and Research Directions* by Amarasinghe, K., et al. arXiv
        preprint: arxiv/2010.14374 [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/AmarasingheExplainable.pdf)
    
      - *Benchmarking and Survey of Explanation Methods for Black Box
        Models* by Bodria, F., et al. arXiv preprint: arxiv/2102.13076
        [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/BodriaExplainable.pdf)

  - **DUE TUESDAY, OCTOBER 30:**  Project Update 6 (Understanding Your Models)
  - 
  - **Tuesday, October 30: Practical Understanding of ML Models**   
    During this session, we'll be introducing some simple and practical analyses to
    perform after the modeling process and what it means to compare
    performance across model specifications. These methods can help
    provide a basic understanding of how your model is distinguishing
    between predicted classes and play an important role in detecting
    bugs such as leakage.

  - **Thursday, November 2: Inherently-Interpretable Methods**  
    In this class, we’ll start our deeper dives into specific methods by
    looking at inherently interpretable methods, including
    GA<sup>2</sup>M models and RiskSLIM. Groups will give a 15-minute
    presentation on each method and then we will spend the remainder of
    the class session comparing the methods and discussing the use cases
    in which they may be most appropriate.  
      
    Required Readings **to Skim**:
    
      - *Intelligible Models for HealthCare: Predicting Pneumonia Risk
        and Hospital 30-day Readmission* by Caruana, R, et al. KDD 2015.
        [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/CaruanaGAM.pdf)
    
      - *Optimized Scoring Systems: Toward Trust in Machine Learning for
        Healthcare and Criminal Justice* by Rudin, C, and Usutn, B.
        INFORMS Journal on Applied Analytics. 2018. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/UstunRudinINFORMS.pdf)
    
    Optional Readings:
    
      - *Interpretable Decision Sets: A Joint Framework for Description
        and Prediction* by Lakkaraju, H, et al. KDD 2016. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/LakkarajuDecisionSets.pdf)

  - **Tuesday, November 7: Post-Hoc Local Explanations**  
    In this class, we’ll continue our discussion model interpretability
    by looking at three methods that can provide local, feature-based
    explanations without relying on the details of the underlying model:
    LIME, SHAP, and MAPLE.  
      
    Required Readings **to Skim**:
    
      - *Why Should I Trust You? Explaining the Predictions of any
        Classifier* by Ribeiro, MT, Singh, S, and Guestrin, C. KDD 2016.
        [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/RibeiroLIME.pdf)
    
      - *A Unified Approach to Interpreting Model Predictions* by
        Lundberg, SM and Lee, S. NeuRIPS 2017. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/LundbergSHAP.pdf)
    
      - *Model Agnostic Supervised Local Explanations* by Plumb, G,
        Molitor, D, and Talwalkar, AS. NeuRIPS 2018. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/PlumbMAPLE.pdf)
    
    Optional Readings:
    
      - *Explainable machine-learning predictions for the prevention of
        hypoxaemia during surgery* by Lundberg, SM, Nair, B, et al.
        Nature Biomed. Eng. 2018. [Available
        Online](https://www.nature.com/articles/s41551-018-0304-0.pdf)
    
      - *Explainable AI for Trees* by Lundberg, SM, Erion, G, et al.
        arXiv preprint: arxiv/1905.04610. [Available
        Online](https://arxiv.org/pdf/1905.04610.pdf)

  - **Thursday, November 9: Other Interpretability Methods**  
    In this session, we’ll take a look at some of the other methods
    people have explored for model interpretability, such as
    counterfactual (e.g., DiCE) and example-based methods (e.g.,
    ProtoDash)  
      
    Required Readings **to Skim**:
    
      - *Explaining Machine Learning Classifiers through Diverse
        Counterfactual Explanations* by Mothilal, R, et al. FAT\* 2020.
        [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/MothilalCounterfactual.pdf)
    
      - *Efficient Data Representation by Selecting Prototypes with
        Importance Weights* by Gurumoorthy, K.S., et al. arXiv preprint:
        arxiv/1707.01212. [Available
        Online](https://arxiv.org/pdf/1707.01212)
    
    Optional Readings:
    
      - *Tree Space Prototypes: Another Look at Making Tree Ensembles
        Interpretable* by Tan, S., et al. FODS 2020. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/TanPrototypes.pdf)
    
      - *Understanding Black-box Predictions via Influence Functions* by
        Koh, P.W. and Liang, P. ICML 2017. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/KohInfluenceFunctions.pdf)

  - **DUE FRIDAY, NOVEMBER 10:** Extended Abstract on Interpretability  
      

### MODULE 3: FAIRNESS IN ML**  

  - **Tuesday, November 14: Intro to Fairness**  
    In this class, we’ll introduce topics in ML fairness, where we will
    focus our methods deep dives for the remainder of the semester: Just
    as important as assessing whether your model is making accurate
    predictions is determining whether it is doing so in a fair manner.
    But, what do we mean by fairness? How can you measure it and what
    can you do to mitigate any disparities you might find? Where in your
    pipeline can bias be introduced? (spoiler: everywhere). This class
    will provide a very brief introduction to the expansive field of
    algorithmic fairness.  
      
    Note that we’ll also post assignments for the Module III methods for
    early this week so teams can begin implementing them for the deep
    dives beginning the following week.  
      
    Required Readings:
    
      - *Fairness Definitions Explained* by Verma, S and Rubin, J.
        [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/VermaFairnessDefn.pdf)
    
      - *A Theory of Justice* by Rawls, J. 1971. Chapter 1: Justice as
        Fairness, pp. 1-19. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/RawlsJustice.pdf)
    
      - *Racial Equity in Algorithmic Criminal Justice* by Huq, A. Duke
        Law Journal. 2018. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/HuqRacialEquity.pdf)
        \[Focus on sections: I.B.2, all of section II, III introduction,
        III.B, and III.D.3\]
    
    Optional Readings:
    
      - *Is Algorithmic Affirmative Action Legal?* by Bent, JR.
        Georgetown Law Journal. 2019. [Available
        Online](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3372690)
    
      - *Does Mitigating ML’s Impact Disparity Require Treatment
        Disparity?* by Lipton, Z, McAuley, J, and Chouldechova, A. NeuRIPS
        2018. [Available
        Online](http://papers.nips.cc/paper/8035-does-mitigating-mls-impact-disparity-require-treatment-disparity)
    
      - *Equality of Opportunity* by Roemer, JE and Trannoy, A. 2013.
        [Available
        Online](http://cowles.yale.edu/sites/default/files/files/pub/d19/d1921.pdf)

  - **Thursday, November 16: Field Trials and Causality**  
    In this session, we’ll briefly discuss field trials and issues of
    causality, critical for understanding how your model actually
    generalizes to real-world applications. Even with careful planning
    and handling of the data, the only way to truly understand how well
    your model works is by testing it in the field. Generally, you’re
    concerned not only with its predictiveness, but the actual ability
    of the model to help the program achieve its policy goals, such as
    improving outcomes among the population it serves. Typically, this
    involves working closely with policymakers to develop a field trial
    using either randomization or non-experimental methods depending on
    the constraints of the setting.  
      
    Required Readings:
    
      - *The seven tools of causal inference, with reflections on
        machine learning* by Pearl, J. Comm ACM. 2019 [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/PearlCausality.pdf)
    
    Optional Readings:
    
      - *Elements of Causal Inference* by Peters et al. MIT Press.
        Chapters 1 and 2. [Available Online (Open Access
        Link)](https://mitpress.mit.edu/books/elements-causal-inference)

  - **Tuesday, November 21: Pre-Processing FairML Methods**  
    During this class, we’ll start exploring fairness-enhancing methods
    by specifically looking at pre-processing methods that work upstream
    of the machine learning models themselves in hopes of reducing
    downstream biases in the pipeline. In particular, we will focus on
    two strategies: removing sensitive attributes (and correlated
    features) and re-sampling the training data. Note for this week that
    the presenting groups should focus on these strategies generally,
    rather than one specific implementation in the readings here (which
    are provided as examples of these approaches).  
      
    Required Readings **to Skim**:
    
      - *Interventional Fairness: Causal Database Repair for Algorithmic
        Fairness* by Salimi, B., et al. SIGMOD 2019. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/SalimiDatabaseRepair.pdf)
    
      - *Data preprocessing techniques for classification without
        discrimination* by Kamiran, F. and Calders, T. Knowledge
        Information Systems (2012). [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/KamiranPreprocessing.pdf)
    
      - *Tuning Fairness by Balancing Target Labels* by Kehrenberg, T.,
        et al. Frontiers in Artificial Intelligence (2020). [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/KehrenbergBalancingLabels.pdf)
    
    Optional Readings:
    
      - *Fairness Through Awareness* by Dwork, C, Hardt, M, et al. ITCS
        2012. [Available
        Online](https://dl.acm.org/citation.cfm?id=2090255)

  - **Thursday, November 23: NO CLASSES – Thanksgiving**

  - **Tuesday, November 28: In-Processing FairML Methods**  
    In this session, we’ll look at in-processing methods for improving
    fairness by adding constraints (or regularization terms) to the
    optimization performed during model training, focusing on methods
    proposed by Zafar, Celis, and Microsoft Research.  
      
    Required Readings **to Skim**:
    
      - *Fairness Constraints: Mechanisms for Fair Classification*
        Zafar, M, Valera I, et al. PMLR 2017. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/ZafarConstraints.pdf)
    
      - *Classification with fairness constraints: A meta-algorithm with
        provable guarantees* by Celis, E, Huang, L, et al. FAT\* 2019.
        [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/CelisFairConstraint.pdf)
    
      - *Fairlearn: A toolkit for assessing and improving fairness in
        AI* by Bird, S., et al. Microsoft Research Whitepaper (2020).
        [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/FairLearn.pdf)
    
    Optional Readings:
    
      - *Fairness Beyond Disparate Treatment & Disparate Impact:
        Learning Classification without Disparate Mistreatment* by
        Zafar, M., et al. WWW 2017. [Available
        Online](https://dl.acm.org/doi/pdf/10.1145/3038912.3052660?casa_token=QuGrvlIf8bcAAAAA:9dUP_TCcEQFAXQc8BXmjlUtWQGzKehUolZBIvveQX1-Sj2KDeSdtZpzQG98TKi4BN6NTeizZKXtDaVI)

  - **Thursday, November 31: Post-Process FairML Methods**  
    This class, we’ll turn to post-processing methods, including
    fairness-aware model selection, decoupled models, and post-hoc score
    adjustments.  
      
    Required Readings **to Skim**:
    
      - *Promoting Fairness through Hyperparameter Optimization* by
        Cruz, A.F., et al. arXiv preprint: arxiv/2103.12715 [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/CruzHyperparameter.pdf)
    
      - *Decoupled Classifiers for Group-Fair and Efficient Machine
        Learning* by Dwork, C, et al. PMLR 2018. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/DworkDecoupled.pdf)
    
      - *Equality of Opportunity in Supervised Learning* by Hardt, M.
        and Price, E. NeurIPS 2016. [Available
        Online](https://github.com/dssg/MLinPractice/blob/main/Readings/PDF/HardtEqualityOpportunity.pdf)
    
    Optional Readings:
    
      - *Case study: predictive fairness to reduce misdemeanor
        recidivism through social service interventions* by Rodolfa,
        K.T., et al. FAT\* 2020. [Available
        Online](https://arxiv.org/pdf/2001.09233)

  - **Tuesday, December 5: Module III Review**  
    In this session, we’ll wrap up our discussion of ML interpretability
    with a brief review of the methods we’ve covered (and what we
    haven’t had time to discuss)  

  - **Thursday, December 7: Wrap-Up**  
    For this meeting, we’ll wrap up the course with a review of the
    topics we’ve covered throughout the semester and some comments on
    the important take-home messages we hope will be useful in your
    future research and work.  

  - **DUE FRIDAY, DECEMBER 8:** Extended Abstract on Fairness

  - **DUE DATE TBD (Finals Week): Final Reflection Write-Up**  
    As a final assignment, we’re asking each student to write up a brief
    (1-2 page) reflection on the course. A more detailed assignment and
    prompt will be posted to canvas.  

## More Resources
You may find a number of books useful as general background reading on
specific topics covered in class, but these are by no means required
texts for the course:

  - *Big Data and Social Science* edited by Foster, Ghani, et al.
    [Available Online](https://textbook.coleridgeinitiative.org/)

  - *Practical Fairness: Achieving Fair and Secure Data Models* by
    Nielsen

  - *Fairness and Machine Learning* by Barocas, Hardt, and Narayana

  - *Weapons of Math Destruction* by O’Neil

  - *Exploratory Data Analysis* by Tukey

  - *Data Science for Business* by Provost and Fawcett  

Additionally, the Global Communication Center (GCC) can provide
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
Should anything come up will require you to miss a class (illness,
conferences, etc), please let one of the course staff know in advance.  

**Academic Integrity:** Violations of class and university academic
integrity policies will not be tolerated. Any instances of copying,
cheating, plagiarism, or other academic integrity violations will be
reported to your advisor and the dean of students in addition to
resulting in an immediate failure of the course.  

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
