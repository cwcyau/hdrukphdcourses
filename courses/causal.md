# HDR002 Structural Causal Models and Inference

## Basic Information

| Course Item | Detail |
| :---- | :------ |
| Code | HDR002 |
| Title | Structural causal modelling and inference |
| Leader | [Max Little](http://www.maxlittle.net/home/index.php) |
| Duration | 3 days |

## Description

### Overview 

Most health data researchers appreciate that "association is not causation", but in practice make heavy use of classical statistical techniques and machine learning methods without considering that these are blind to causal effects. This has serious implications in practice: for instance, a predictive algorithm which attempts to rank patients by their risk of being diagnosed with some disease in the future, is misleading if it merely picks up strong but spurious cause-effect signals relating the specific way in which blood tests are ordered by hospital staff, to eventual diagnosis. Therefore, causal modelling and inference are critical to the design and implementation of effective and reliable predictive modelling.

### Intended Learning Outcomes

This workshop aims to give the participants a thorough and rigorous *advanced* introduction to the key modern theory of causality, structural causal modelling, and causal inference. By the end of the course, participants should be able to have confidence in applying the concepts of causal modelling and inference, and be able to use and/or implement causal inference algorithms, for their own health data science applications.

### Teaching methods

The training will consist of technical lectures, directed reading group discussions, practical group tasks and enrichment such as guest lectures.

## Pre-requisites

**THIS COURSE IS NOT AN INTRODUCTORY COURSE** 

Participants are expected to have sufficient mathematical and computational as outlined below. Participants will be required to have undertaken the pre-course reading. If you are interested in a non-technical introduction to this area, you may wish to consider alternative providers such as the [Leeds Causal Inference Training Course](https://www.causalinsights.com/training/).

1. In order to take part in the group tasks, students will be expected to have access to a laptop with the Python language installed. Familiarity with Python is an advantage, but experience in programming in any imperative language (e.g. R, C++, Java) will likely suffice for the course.

2. Knowledge of mathematical probability and graphs is expected. Participants should have (or will have acquired) familiarity with the following: 
  - Topics covered as part of Chapters 1-4 (https://www.utstat.toronto.edu/mikevans/jeffrosenthal/book.pdf)
  - Topics covered in Section 2.2. (http://mcb111.org/w06/KollerFriedman.pdf)

3. Participants will be expected to be familiar with the concepts introduced in the [The Book of Why: The New Science of Cause and Effect](https://en.wikipedia.org/wiki/The_Book_of_Why) by Judea Pearl, an accessible introduction to structural causal modelling and inference, before attending the workshop.  
  - Free excerpts are available [here](http://bayes.cs.ucla.edu/WHY/). 
  - Video lectures from Judea Pearl can be found on popular media platforms: 
    - [Judea Pearl - The New Science of Cause and Effect](https://www.youtube.com/watch?v=ZaPV1OSEpHw&ab_channel=PyData)
    - https://www.youtube.com/watch?v=bcRl7sXR1hE&ab_channel=MicrosoftResearch

## Timetable

**Day 1: Concepts and tools**

| Time | Description | 
| ---- | ----------- |
| 9.30-10.20 | Lecture 1: Structural causal models and the Pearl hierarchy |
| 10.30-11.20 | Directed reading group 1: Bareinboim et al., 2022 |
| 11.30-12.30 | Lecture 2: Interventional distributions and the identifiability problem |
| 12.30-13.50 | Lunch |
| 14.00-14.50 | Directed reading group 2: Shpitser, 2020 |
| 15.00-15.50 | Lecture 3: GRAPL: A computational Python library for nonparametric structural causal modelling, analysis and inference |
| 16.00-17.00 | Group task descriptions and discussion |

**Day 2: Group tasks and guest lectures**

| Time | Description | 
| ---- | ----------- |
| 9.30-10.50 | Group work | 
| 11.00-11.50 | External Seminar [tbc] | 
| 12.00-13.20 | Lunch | 
| 13.30-14.50 | Group work | 
| 15.00-15.30 | External Seminar [Dhurim Caqiki] | 
| 15.30-17.00 | Group work | 

*Task A:* Application: modelling and structural inference problem

*Task B:* Algorithm implementation: Identification of conditional interventional distributions (IDC algorithm, Shpitser et al.)

*Task C:* Algorithm implementation: Recovering an interventional distribution when only biased data is available (RC algorithm, Correa et al.)

**Day 3: Task presentation and wrap-up**

| Time | Description | 
| ---- | ----------- |
| 9.30-10.00 | Submit work | 
| 10.00-12.00 | Presentations on results from each group | 
| 12.00-12.30 | Summary | 

# References

1. Judea Pearl (2018). The Book of Why: The New Science of Cause and Effect, Penguin
2. Elias Bareinboim, Juan D. Correa, Duligur Ibeling, Thomas Icard (2022). [On Pearl's Hierarchy and the Foundations of Causal Inference, Probabilistic and Causal Inference: The Works of Judea Pearl](https://causalai.net/r60.pdf), February 2022, 507–556, https://doi.org/10.1145/3501714.3501743
3. Ilya Shpitser (2020). [Identification in Causal Models With Hidden Variables](https://pubmed.ncbi.nlm.nih.gov/33240555/), J Soc Fr Statistique, 2020, 161(1):91–119
4. Jin Tian, Judea Pearl (2002). [A general identification condition for causal effects](https://www.aaai.org/Library/AAAI/2002/aaai02-085.php). In Eighteenth National Conference on Artificial Intelligence, pp. 567–573.
5. Thomas S. Richardson, Robin J. Evans, James M. Robins and Ilya Shpitser (2022), [Nested Markov Properties for Acyclic Directed Mixed Graphs](https://arxiv.org/abs/1701.06686), https://arxiv.org/abs/1701.06686
6. Juan D. Correa, Jin Tian, Elias Bareinboim (2019). Identification of Causal Effects in the Presence of Selection Bias, AAAI-19
7. Ilya Shpitser, Judea Pearl (2006). Identification of Conditional Interventional Distributions, UAI-2006


