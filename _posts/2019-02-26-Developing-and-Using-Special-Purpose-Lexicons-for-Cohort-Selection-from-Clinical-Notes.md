---
layout: post
title: "Developing and Using Special-Purpose Lexicons for Cohort Selection from Clinical Notes"
date: 2019-02-26 00:45:56
categories: arXiv_CL
tags: arXiv_CL Review Knowledge Classification
author: Samarth Rawal, Ashok Prakash, Soumya Adhya, Sidharth Kulkarni, Saadat Anwar, Chitta Baral, Murthy Devarakonda
mathjax: true
---

* content
{:toc}

##### Abstract
Background and Significance: Selecting cohorts for a clinical trial typically requires costly and time-consuming manual chart reviews resulting in poor participation. To help automate the process, National NLP Clinical Challenges (N2C2) conducted a shared challenge by defining 13 criteria for clinical trial cohort selection and by providing training and test datasets. This research was motivated by the N2C2 challenge. 
 Methods: We broke down the task into 13 independent subtasks corresponding to each criterion and implemented subtasks using rules or a supervised machine learning model. Each task critically depended on knowledge resources in the form of task-specific lexicons, for which we developed a novel model-driven approach. The approach allowed us to first expand the lexicon from a seed set and then remove noise from the list, thus improving the accuracy. 
 Results: Our system achieved an overall F measure of 0.9003 at the challenge, and was statistically tied for the first place out of 45 participants. The model-driven lexicon development and further debugging the rules/code on the training set improved overall F measure to 0.9140, overtaking the best numerical result at the challenge. 
 Discussion: Cohort selection, like phenotype extraction and classification, is amenable to rule-based or simple machine learning methods, however, the lexicons involved, such as medication names or medical terms referring to a medical problem, critically determine the overall accuracy. Automated lexicon development has the potential for scalability and accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09674](http://arxiv.org/abs/1902.09674)

##### PDF
[http://arxiv.org/pdf/1902.09674](http://arxiv.org/pdf/1902.09674)

