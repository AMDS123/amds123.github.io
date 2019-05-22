---
layout: post
title: "OBOE: Collaborative Filtering for AutoML Model Selection"
date: 2019-05-20 19:55:26
categories: arXiv_AI
tags: arXiv_AI
author: Chengrun Yang, Yuji Akimoto, Dae Won Kim, Madeleine Udell
mathjax: true
---

* content
{:toc}

##### Abstract
Algorithm selection and hyperparameter tuning remain two of the most challenging tasks in machine learning. Automated machine learning (AutoML) seeks to automate these tasks to enable widespread use of machine learning by non-experts. This paper introduces OBOE, a collaborative filtering method for time-constrained model selection and hyperparameter tuning. OBOE forms a matrix of the cross-validated errors of a large number of supervised learning models (algorithms together with hyperparameters) on a large number of datasets, and fits a low rank model to learn the low-dimensional feature vectors for the models and datasets that best predict the cross-validated errors. To find promising models for a new dataset, OBOE runs a set of fast but informative algorithms on the new dataset and uses their cross-validated errors to infer the feature vector for the new dataset. OBOE can find good models under constraints on the number of models fit or the total time budget. To this end, this paper develops a new heuristic for active learning in time-constrained matrix completion based on optimal experiment design. Our experiments demonstrate that OBOE delivers state-of-the-art performance faster than competing approaches on a test bed of supervised learning problems. Moreover, the success of the bilinear model used by OBOE suggests that AutoML may be simpler than was previously understood.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.03233](http://arxiv.org/abs/1808.03233)

##### PDF
[http://arxiv.org/pdf/1808.03233](http://arxiv.org/pdf/1808.03233)

