1. Will this new course affect a current program? **No**

2. Teaching Department: **Neurology and Neurosurgery** 

3 Administering Faculty/Unit: **Faculty of Medicine**

4. Campus: **Downtown**

5. Effective term of implementation: 202005 

6. Responsible instructor: **Jean-Baptiste Poline**

7. Course title: **Fundamentals for neuro data sciences**

8. Course numbers: **1**

9. Course Title to Appear in the eCalendar (optional): **Fundamental tools and methods for neuro data sciences**

10. Credit weight: **3**

11. Rationale for the course:

Students in neuroscience, life sciences or medicine are facing research
projects that require them to acquire computational skills and data science
methodologies, both at conceptual and practical levels, to best visualize,
analyze and interpret an increasing number of open and large datasets within
data-set specific ethical and legal constraints. Many projects are built on
previous work or are by nature collaborative, but students often lack the
technical tools to facilitate reproducible and collaborative work. In addition,
being able to communicate reproducible analyses still remain a challenge for
many. We propose a "bootcamp" course to jointly teach the fundamentals of key
computational tools (bash, git, github, python ecosystem including jupyter,
docker, visualization) and examples of analysis methods (hypothesis testing, machine
learning) at the conceptual and at the practical levels using neuroscience
datasets.

12. Course description (100 words)

This course will teach participants how to analyse data in a reproducible and
collaborative manner using the Python software stack.  The fundamentals of both
tools (bash, git, github, jupyter, docker, visualization) and analysis methods
(hypothesis testing, machine learning) will be taught at the conceptual and
practical levels using example datasets from neuroscience and neuroimaging.
This will be an intense "hands on" bootcamp to give students a complete toolbox
for reproducible and collaborative neuro data science. Students will be
expected to have basic programming skills and to bring a laptop. 

15. Projected Enrolment: **30**


17. Prerequisite(s) (Courses or Tests) **None**
Specify course number(s) or name(s) of test(s):


19. Restriction(s): **The course will require students to have a laptop and some notions of programming**




Course outline


Title : Fundamentals in Neuro Data Science - full schedule
============================================================

# Full Schedule
---

## Monday

### 9:00 - Course Introduction

**Learning Objectives:**
    - Become familiar with the objectives and logistics of Neuro-Data-Science school.

### 10:00 - Epistemology and lessons from the past 

An in-depth exploration of the facets and challenges of neuroscience that
created the need for initiatives like BrainHack School. This will included an
overview of some classical epistemological contexts, and topics related to
reproducibility, falsifiability, and statistics.

**Learning Objectives:** Understand the greater context that created the need for
the tools you will learn to use in the neuro-data-science course.

| Content       | Time allotted | Instructor  |
| ------------- |:--------------:|-------------|
| Summary of current reproducibility problems     | 1 hour |  |
| Popper and Kuhn     | 1 hour |  |


### 12:00 - Lunch

### 13:00 - Installation time and troubleshooting: 1 hour

### 14:00 - Git and GitHub 

Interactive session where students will become familiar with the shell,
followed by a deep dive into the Git model for distributed version-control and
collaboration. The aim of this workshop will be not only to understand the
basics of Git, but also understand how to never lose any work, and how to
successfully collaborate with oneself.

**Learning Objectives:** 1) Transition to using the shell regularly and comfortably,
2) an understanding of how Git works,
and 3) how to use Git and Github for version-control.

| Content       | Time allotted | Instructor  |
| ------------- |:--------------:|-------------|
| Introduction to the shell     | 1 hour |  |
| Introduction to git for version control    | 1 hour |  |
| Introduction to github for collaboration    | 1 hour |  |

---

## Tuesday

### 09:00 - Python for data analysis

A presentation on why to use Python for data analysis, followed by an
interactive workshop. The workshop will cover key data structures,
automation basics, and the concept of functional programming. Students will
also be introduced to the most common packages used for Python data analysis,
including Numpy, Scipy, Matplotlib, Pandas and Nibabel. Finally, students will
learn how to convert neuroimages to analyzable data.

**Learning Objectives:** 1) Use a python interpreter and text editor to write and
execute python scripts.
2) Use python to convert neuroimages and spreadsheets to data to analyze and visualize.

| Content       | Time allotted | Instructor  |
| ------------- |:--------------:|-------------|
| Variables, types, and comparisons     | 20 minutes |  |
| Logic, looping, and functions    | 20 minutes |  |
| Debugging, scripts, and file I/O    | 20 minutes |  |
| File parsing in standard python     | 1 hour |  |
| Libraries and the scientific python ecosystem    | 20 minutes |  |
| Better data management    | 10 minutes |  |
| Stepwise neuroimaging workflow in python  | 30 minutes |  |

### 12:00 - Lunch: 1 hour

### 13:00 - Containers 

A large challenge to reproducibility lies in the fact that scientists use
different versions of different tools across different platforms and operating
systems, all of which are in constant flux. Virtual machines and containers
help to create static environments tailored to one’s analyses, which can be
easily shared. This lesson will include an overview (and interactive workshop?)
of popular containers in neuroscience, including Docker, Singularity and
Neurodocker.

**Learning objectives:** 1) Understand the difference between Virtual Machines (VMs) and containers.
2) Learn why, when and how to containerize your code, tool or analyses.

| Content       | Time allotted | Instructor  |
| ------------- |:--------------:|-------------|
| What is a computer     | 20 minutes |  |
| Reproducibility / re-executability    | 10 minutes |  |
| Introduction to Virtualenv, Conda, Containers    | 1.5 hours |  |
| Boutiques / Zenodo for effective data sharing    | 10 minutes |  |
| Package python environment from morning session    | 50 minutes |  |

### 16:30: Assessment 1

---

## Wednesday 

### 9:00 Standards for data project organization and management

Neuroscience is rapidly moving from isolated analysis in the void to
collaboration, translation and data sharing/hosting. New challenges have thus
arisen relating to project organization, sharing of tools and data and
standardization of protocols across labs and environments. We will review tools
for general project organization (e.g. Project TIER and DRESS protocol) and
standardization (BIDS), and cover the basics of creating a sharable package or
toolset.

**Learning Objectives:** 1) Understand the challenges and responsibilities of
effectively sharing data and tools. 2)

| Content       | Time allotted | Instructor  |
| ------------- |:--------------:|-------------|
| BIDS, Project Tier, and SciCrunch     | 1 hour |  |
| Project Jupyter    | 1 hour |  |
| pyBIDS, BIDS App practical    | 1 hours |  |

### 12:00 - Lunch

### 13:00 - Guest Lecture: Binder 

### 14:00 - Advanced Research Computing 

A presentation on what is Compute Canada and advanced research computing
(ARC) intertwined with an interactive workshop. The workshop will focus on
connecting to a computing cluster with SSH, accessing the scientific
softwares and interacting with the job scheduler Slurm.

**Learning Objectives:** 1) Understand what is Compute Canada and ARC
2) Learn how to connect to an ARC cluster
and 3) Learn how to write and submit jobs to Slurm

| Content       | Time allotted | Instructor  |
| ------------- |:--------------:|-------------|
| Introduction to Compute Canada     | 45 min |  |
| Connection and file transfer with SSH  | 30 min |  |
| Loading scientific software with Lmod    | 30 min |  |
| Creation and submission of jobs with Slurm    | 1 hour |  |
| Introduction to data transfer with Globus    | 15 min |  |
---

## Thursday 

###  09:00 Some statistical tools ()

Life science and medicine researchers often rely on a series of classical tools for data analysis and the null hypothesis testing framework.
In this session, we will present some of the classical tools often used by this community, particularly linear regression and GLM.
We will show how to use them in an appropriate manner and point to alternatives in a non parametric context.
Examples of models and results will be demonstrated in a hands on session.

**Learning Objectives:** 1) Use python to visualize variables.
2) Run a basic linear statistical model using python (statsmodels).
3) Introduce the general linear model (GLM).
4) Introduce non-parametric inference.

| Content       | Time allotted | Instructor  |
| ------------- |:--------------:|-------------|
| Visualizations to understand your data | 30 minutes |  |
| Basic statistcal testing in python | 30 minutes |  |
| Intro to multiple testing and data reduction | 20 minutes |  |
| Stretch break / extra time | 10 minutes |  |

### 10:30 - Guest Lecture: Statistical decomposition 

### 12:00 - Lunch

### 13:00 - Guest Lecture: Estimation of connectivity 

Abstract TBA

### 14:00 - Introduction to machine learning 

Machine learning has rapidly become a popular approach in Neuroscience. We will
overview what machine learning actually is, when it is useful and when it is
not, important themes and best practices, and some of the most common
algorithms. An interactive workshop will involve using Python to perform model
comparison, feature selection, prediction using classification and regression
algorithms, feature interpretation, and other topics
like bagging/consensus.

**Learning Objectives:** 1) Understand how and when to include machine learning in
your study design; 2) Learn to avoid the many mistakes commonly made in machine
learning studies; 3) Use python to perform a machine learning pipeline from
end to end.

| Content       | Time allotted | Instructor  |
| ------------- |:--------------:|-------------|
| Key concepts in machine learning | 1.25 hours |  |
| Caffiene break | 15 minutes |  |
| Nilearn for machine learning with neuroimaging data | 1.5 hours |  |

---

## Friday

### 09:00 Introduction to Deep Learning 

Deep learning and AI are gaining extreme popularity within all strata of
science, and even in popular culture. This lecture will cover what deep
learning actually is, when it is and is not appropriate for data analysis,
some basic examples of common and highly successful algorithms, and a review of
best practices. (An interactive workshop will demonstrate how to use Python to
construct an execute a deep learning model.

**Learning Objectives:** 1) Understand when deep learning is an appropriate tool
for analysis. 2) Run a basic deep learning model.

### 12:00 Lunch

### 13:00 Multivariate statistics and matrix factorizations ()

**Learning Objectives:** 1) Introduce common decompositions such such as PCA, NMF.
2) Demonstrate how to perform decompositions in Python.
3) Discuss why and how decompositions can be integrated into a machine learning framework.

