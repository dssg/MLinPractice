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
- Learn how to design end-to-end ML systems that tackle real-world problems
- Evaluate the impact of various design choices across the machine learning workflow in the context of real-world problems.
- Take real-world questions involving data and evaluate or develop appropriate methods to answer these questions.
- Present technical material clearly, in spoken and written form, to various audiences

## People

### Instructor

| Rayid Ghani | 
| --- | 
| <img src="img/rayidphoto.png" width="200" /><br /> GHC 8023 <br /> **Office Hours:** <br />   Tuesday 12:30-1:30pm  <br /> Wednesday 3-4pm  <br /> Email me if you want to meet outside these hours | 

### Education Associate

|Daniel Bird | 
| --- | 
| <img src='img/Daniel Bird.jpeg' width="200" /> <br /> Office: GHC 8120   | 

### Teaching Assistants

|Chancharik Mitra | Namrata	Deka | Rohan Venkatesh Kashyap
| --- | --- | --- |
| <img src='img/Chancharik_Mitra.jpg' width="200" /> <br /> Office Hours: Tues 5pm and Thurs 11am GHC 8228   | <img src='img/Namrata Deka.jpg' width="200" /> <br /> Office Hours: Mon 4pm and Fri 10am GHC 8228   | <img src='img/Rohan.jpg' width="200" /> <br /> Office Hours: Tues 12:30pm and Wed 11am GHC 8228   | 

## Grading 

Project update assignments (30%)

Midterm take-home exam (20%)

Write-up on module 2 findings (10%)

Group presentation (10%)

Final reflection write-up (10%)

Class attendance and participation in discussions (15%)

Submitting weekly check-in and feedback forms (5%)

## Schedule

See the **[detailed syllabus](README.md#structure)** below for much more detail as well, including **links to required readings** and information about group projects, grading, and helpful optional readings.
| Week | Dates       | Topic                                                                                                                                        | Assignments                                                                                                                           |
| ---- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Tu: Aug 26  | [Class Intro and Overview](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture1-ClassOverview.pptx)                               |                                                                                                                                       |
| 1    | Th: Aug 28  | Why ML systems can fail in practice                                                                                                          |                                                                                                                                       |
| 2    | Tu: Sep 2   | [Scoping and Defining ML Projects](#ml-project-definition-and-scoping)                             | Individual Assignment: Getting to know the class project (due tuesday)<br>Project Team Selection                                      |
| 2    | Th: Sep 4   | [Getting, Storing, and Linking Data](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture3-Data.pptx)                              |                                                                                                                                       |
| 3    | Tu: Sep 9   | Data Exploration                                                                                                                             | Short Assignment on Data Exploration                                                                                                  |
| 3    | Th: Sep 11  | [Analytical Formulation / Baselines](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture4-Formulation.pptx)                       |                                                                                                                                       |
| 4    | Tu: Sep 16  | [Model Selection Methodology](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture5-ModelSelection.pptx)                           | Project Assignment 1: Formulation and Baseline (due Monday)                                                                           |
| 4    | Th: Sep 18  | [Performance Metrics](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture6-EvaluationMetrics.pptx)                                |                                                                                                                                       |
| 5    | Tu: Sep 23  | [Feature Engineering and Imputation](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture7-Features.pptx)                          | Project Assignment 2:<br>Validation set up<br>Initial pipeline with train and validation set(s) and baseline implemented (due Monday) |
| 5    | Th: Sep 25  | [ML Pipelines](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture8-Machine-Learning-Pipelines.pptx)                              |                                                                                                                                       |
| 6    | Tu: Sep 30  | [Models/hyperparameters in practice](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture9-PracticalModeling-Hyperparameters.pptx) | Project Assignment 3:<br>list of features and some subset implemented (due Monday)                                                    |
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
end-to-end machine learning pipelines, 2) Key considerations when building ML systems in practice, such as interpretability,
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

  - During the second half, each group will pick one topic (among a few choices) and implement that into their project and present their results (through a short writeup and a team presentation).

### More details about the class project

Public schools in the United States face large disparities in funding, often resulting in teachers and staff members filling these gaps by purchasing classroom supplies out of their own pockets. DonorsChoose is an online crowdfunding platform that tries to help alleviate this financial burden on teachers by allowing them to seek funding for projects and resources from the community (projects can include classroom basics like books and markers, larger items like lab equipment or musical instruments, specific experiences like field trips or guest speakers).

Projects on DonorsChoose expire after 4 months, and if the target funding level isn't reached, the project receives no funding. Since its launch in 2000, the platform has helped fund over 2 million projects at schools across the US, but about 1/3 of the projects that are posted nevertheless fail to meet their goal and go unfunded.

#### The Modeling Problem
For the purposes of the class project, \\DonorsChoose has hired a digital content expert who will review projects and help teachers improve their postings and increase their chances of reaching their funding threshold. Because this individualized review is a labor-intensive process, the digital content expert has ** time to review and support only 10% of the projects posted to the platform on a given day**.

You are working with DonorsChoose, and your task is to help this content expert focus their limited resources on projects that most need the help. As such, you want to build a model to identify projects that are least likely to be fully funded before they expire and pass them off to the digital content expert for review.

## Data
[Download links and data set description](datadescription.md)


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

- **Tuesday, August 26: Introduction**  
    During our initial meeting, we’ll provide an introduction to the
    class, its goals, and an overview of the applied project we will be
    using as a motivating example throughout the semester.


- **Thursday, August 28: Why ML Systems can Fail in Practice**  
    In this session, we'll discuss real-world failure modes of ML systems, moving beyond model accuracy to system-level issues including data, deployment, governance, incentives, etc. The goal here is to encourage critical thinking about preventing failures and to motivate the topics to be covered during the rest of the semester.
  
- **Tuesday, September 2:**
  #### ML Project Definition and Scoping
   In this session, we’ll talk about scoping, problem definition, and
   understanding and balancing organizational goals. Well before we start doing technical ML work, a decision needs to be made about whether
   a given problem can and should be addressed with machine learning:
   is the problem significant, feasible to solve with ML, and of sufficient importance to the organization that they
   will devote resources to implementing the solution? How will success
   be measured? How will (often competing) goals of efficiency,
   effectiveness, and equity be balanced?
   **[Lecture Slides](https://github.com/dssg/MLinPractice/raw/main/Lectures/Lecture2-Scoping.pptx)**
   **Required Reading:**
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

- **Thursday, September 4: Obtaining, Storing, and Linking Data**  
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

    **Due Today:**
     - Individual Assignment: Getting to know the class project data
     - Project team selections


- **Tuesday, September 9: Data Exploration**
   You're all familiar with the concept and practice of data exploration. In this session,
   we'll 1) learn about the use of data exploration in ML projects and 2) apply those ideas to the class project.
   


- **Thursday, September 11: Analytical Formulation and Baselines**  
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

- **DUE MONDAY, SEPTEMBER 15:** Project Update 1 (Formulation and
   Baselines)
   
- **Tuesday, September 16: Model Selection Methodology**  
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

- **Thursday, September 18: Model Performance Metrics**  
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

- **DUE MONDAY, SEPTEMBER 22:** Project Update 2 (Validation set-up;
   initial pipeline with train and validation sets and baseline
   implemented)

- **Tuesday, September 23: Feature Engineering and Imputation**  
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

- **Thursday, September 25:  ML Pipelines**  
  During this session, we’ll take some time to review the machine
  learning pipelines your teams have been building, providing feedback
  on structure, design decisions, and best practices.

- **DUE MONDAY, SEPTEMBER 29:** Project Update 3 (List of implemented
  and planned features)

- **Tuesday, September 30: ML Modeling in Practice**  
  This class will focus on some of the practical aspects of applying
  machine learning to real-world problems. In other classes, you have
  implemented and worked with a wide variety of machine learning
  methods, but where should you start when dealing with a real problem
  in practice? What is a “reasonable” hyperparameter grid to consider?
  What pitfalls might you encounter in these situations and how can
  you avoid them?  

- **Thursday, Oct 2: Temporal Model Selection**  
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

- **DUE MONDAY, OCTOBER 6:** Project Update 4 (Modeling Results)

- **Tuesday, October 7: Module 1 Review: Applied ML End-to-End
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


- **Thursday, October 9: No Class, Midterm Distributed**  
  We'll cancel class on this day to provide some extra time for working
  on the midterm and updating model results.

- **Tuesday, October 14 and Thursday, October 16: NO CLASSES – Fall
  Break**  
    
- **DUE TUESDAY, OCTOBER 21:** Take-home midterm exam  
- **DUE MONDAY, OCTOBER 21:** Project Update 5 (Updated Modeling
  Results and Model Selection)  

### MODULE 2: Key Considerations Beyond Model Accuracy**
 This module will focus on topics such as ethics, interpretability, fairness, robustness, privacy, causality, field trials, uncertainty quantification, and supporting decision-makers. The topics to be covered will be chosen as we go through the semester collaboratively.

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
