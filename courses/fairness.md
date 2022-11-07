# HDR001 Fairness in healthcare modelling

## Basic Information

| Course Item | Detail |
| :---- | :------ |
| Code | HDR001 |
| Title | Fairness in healthcare modelling |
| Leader | [Ioanna Manolopoulou](https://ioannamanolopoulou.github.io/) |
| Duration | 3 days |
| Dates | 9-11 November 2022|

## Description

### Overview 

The aim of this training is to cover the basic principles of fairness in healthcare modelling and highlight aspects of fairness that Health Data Scientists need to be aware of in their own research.

### Intended Learning Outcomes

- Participants will understand how bias can manifest itself in the different stages of predictive modelling in healthcare.
- Participants will understand the implications of biased samples, especially in the context of health data science such as genetic data or underreported medical conditions.
- Participants will have a broad understanding of how to evaluate algorithmic fairness within a given predictive model. 

### Teaching methods

The first part of the training will be largely based around discussions, but participants are expected to have read 4-5 of the key papers in this area (at least one from set) that are listed below. In the second part, participants will be split into groups and work on a task. 

## Pre-requisites

Students will also need access to the [Nightingale](https://app.nightingalescience.org/projects) data. Nightingale is an open platform for health data but requires registration in advance and approval can take several days, so early registration is required. The platform contains lots of information on existing projects. Students are also advised to complete the MRC [“Research, GDPR and confidentiality”](https://byglearning.com/mrcrsc-lms/course/index.php?categoryid=1) e-learning module (or another equivalent training). 

For those who may be interested in finding out more about fairness in healthcare modelling, the MIT course [“Ethical Machine Learning in Human Deployments”](https://canvas.mit.edu/courses/14219) by Dr. Marzyeh Ghassemi is excellent. You may also be interested in [Data Science for Health Equity (DSxHE)](https://www.datascienceforhealthequity.com/), an independent community that brings together experts, enthusiasts and hobbyists working at the intersection of data science and health inequalities to ensure that the latest research and innovations improve health equity. There is also a [Turing Interest Group on "Health Equity"](https://www.turing.ac.uk/research/interest-groups/health-equity) which you might be interested in. 

All the group-work programming will be carried out in Python, so knowledge of Python would be preferred but not necessary. 

**To do:**

1. Register for access to the [Nightingale](https://app.nightingalescience.org/projects) data.
2. Complete the MRC [“Research, GDPR and confidentiality”](https://byglearning.com/mrcrsc-lms/course/index.php?categoryid=1) e-learning module.

## Timetable

### Day 1: Introduction

**9.30-10.15 What is bias in healthcare modelling?**

*Reading papers:*

1. Ninareh Mehrabi, Fred Morstatter, Nripsuta Saxena, Kristina Lerman, and Aram Galstyan, (2022). *A Survey on Bias and Fairness in Machine Learning*. ACM Comput. Surv. 54, 6, Article 115.

2. Sahil Verma and Julia Rubin (2018). *Fairness definitions explained*. In Proceedings of the International Workshop on Software Fairness (FairWare '18). 

3. Irene Y. Chen, Emma Pierson, Sherri Rose, Shalmali Joshi, Kadija Ferryman, Marzyeh Ghassemi (2021). *Ethical Machine Learning in Healthcare*. Annual Review of Biomedical Data Science, 4:1, 123-144 

4. Harini Suresh and John Guttag (2021). *Understanding Potential Sources of Harm throughout the Machine Learning Life Cycle*. MIT Case Studies in Social and Ethical Responsibilities of Computing,

**10:30-11:00 Bias in data**

- How does bias in data arise? 
- What is selection bias? 
- What are common sources of bias in healthcare data? 

| Time | Task|
|------|------|
|10.30-11.00 | Bias in data|

*Reading papers:*

5. Laliberté V, Giguère CE, Potvin S, Lesage A; Signature Consortium (2020). *Berkson's bias in biobank sampling in a specialised mental health care setting: a comparative cross-sectional study.* BMJ Open.

6. Röösli, E., Bozkurt, S. & Hernandez-Boussard, T. Peeking into a black box, the fairness and generalizability of a MIMIC-III benchmarking model. Sci Data 9, 24 (2022).

7. Rory Collins (2012) *What makes UK Biobank special?*  The Lancet, Volume 379, Issue 9822. Including comment by James M. Swanson.

8. Huang, Jonathan Yinhao (2021) *Representativeness Is Not Representative: Addressing Major Inferential Threats in the UK Biobank and Other Big Data Repositories.* Epidemiology: Volume 32 - Issue 2.

9. B.C.L. Lehmann, M. Mackintosh, G. McVean, C.C. Holmes (2021). *Optimal strategies for learning multi-ancestry polygenic scores vary across traits.* BioRxiv 2021.01.15.426781.

**11:00-16:00 Algorithmic approaches to evaluation and/or correction of bias**

- How can we systematically evaluate bias in our methods? 
- Is there a way to correct bias?
- What happens if the bias is severe? 

| Time | Task|
|------|------|
|11.00-12.30 | Evaluation and algorithmic correction methods of bias|
|12.30 - 14.00| Lunch break |
|14.00-15.00 | Seminar by Claire Coffey, "Algorithmic fairness in cardiovascular disease risk prediction models."|
|15.00-16.00 | Discussion and introduction to Day 2 task|

*Reading papers:*

10. Mitchell, S., Potash, E., Barocas, S., D'Amour, A., and Lum, K., (2018) *Prediction-Based Decisions and Fairness: A Catalogue of Choices, Assumptions, and Definitions*, arXiv.

11. Solon Barocas, Anhong Guo, Ece Kamar, Jacquelyn Krones, Meredith Ringel Morris, Jennifer Wortman Vaughan, W. Duncan Wadsworth, and Hanna Wallach (2021). *Designing Disaggregated Evaluations of AI Systems: Choices, Considerations, and Tradeoffs.* In Proceedings of the 2021 AAAI/ACM Conference on AI, Ethics, and Society (AIES '21). 

12. Abigail Z. Jacobs and Hanna Wallach, (2021). *Measurement and Fairness.* In Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency (FAccT '21).

13. Grote, T., & Keeling, G. (2022). *On Algorithmic Fairness in Medical Practice*. Cambridge Quarterly of Healthcare Ethics, 31(1), 83-94. 

14.  Margrét Vilborg Bjarnadóttir and David Anderson (2020). *Machine Learning in Healthcare: Fairness, Issues, and Challenges.* Pushing the Boundaries: Frontiers in Impactful OR/OM Research. 64-83.

15. Wu, H., Sylolypavan, A., Wang, M. and Wild, S. (2022). *Quantifying Health Inequalities Induced by Data and AI Models.*  Proceedings of the Thirty-First International Joint Conference on               Artificial Intelligence (AI for Good). 

### Day 2: Group work

The second day will be mostly spent working on the task with the help of instructors. 

| Time | Task |
| ---- | ---- |
| 9.30-10.15 | Exploratory data analysis |
| 10.30-11.30 | Work on task |
| 11.30-12.30 | Seminar by Dr Brieuc Lehmann, "Generalisability and transportability in clinical trials"|
| 14.00-14.30 | Check-in with instructor |
| 14.30-16.00 | Work on task |
| 16.00-17.00 | Webinar by [Emma Pearson](https://www.cs.cornell.edu/~emmapierson/) through DSxHE, [please RSVP](https://www.datascienceforhealthequity.com/event-details/the-november-dsxhe-download)|

We don't expect participants to continue working on the task past 4pm. 

### Day 3: Evaluation

Task evaluation and presentations.

| Time | Task |
| ---- | ---- |
| 9.30-10.00 | Submit results and evaluate outcomes |
| 10.00-12.00 | Short presentations by each group |
| 12.00-12.30 | Summary and closing remarks |
