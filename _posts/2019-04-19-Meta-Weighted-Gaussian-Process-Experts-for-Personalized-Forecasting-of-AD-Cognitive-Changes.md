---
layout: post
title: "Meta-Weighted Gaussian Process Experts for Personalized Forecasting of AD Cognitive Changes"
date: 2019-04-19 23:28:11
categories: arXiv_AI
tags: arXiv_AI
author: Ognjen Rudovic, Yuria Utsumi, Ricardo Guerrero, Kelly Peterson, Daniel Rueckert, Rosalind W. Picard
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel personalized Gaussian Process Experts (pGPE) model for predicting per-subject ADAS-Cog13 cognitive scores -- a significant predictor of Alzheimer's Disease (AD) in the cognitive domain -- over the future 6, 12, 18, and 24 months. We start by training a population-level model using multi-modal data from previously seen subjects using a base Gaussian Process (GP) regression. Then, we personalize this model by adapting the base GP sequentially over time to a new (target) subject using domain adaptive GPs, and also by training subject-specific GP. While we show that these models achieve improved performance when selectively applied to the forecasting task (one performs better than the other on different subjects/visits), the average performance per model is suboptimal. To this end, we used the notion of meta learning in the proposed pGPE to design a regression-based weighting of these expert models, where the expert weights are optimized for each subject and his/her future visit. The results on a cohort of subjects from the ADNI dataset show that this newly introduced personalized weighting of the expert models leads to large improvements in accurately forecasting future ADAS-Cog13 scores and their fine-grained changes associated with the AD progression. This approach has potential to help identify at-risk patients early and improve the construction of clinical trials for AD.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09370](http://arxiv.org/abs/1904.09370)

##### PDF
[http://arxiv.org/pdf/1904.09370](http://arxiv.org/pdf/1904.09370)

