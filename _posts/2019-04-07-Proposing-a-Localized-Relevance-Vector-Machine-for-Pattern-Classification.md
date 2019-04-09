---
layout: post
title: "Proposing a Localized Relevance Vector Machine for Pattern Classification"
date: 2019-04-07 17:00:42
categories: arXiv_AI
tags: arXiv_AI Sparse Classification Prediction
author: Farhood Rismanchian, Karim Rahimian
mathjax: true
---

* content
{:toc}

##### Abstract
Relevance vector machine (RVM) can be seen as a probabilistic version of support vector machines which is able to produce sparse solutions by linearly weighting a small number of basis functions instead using all of them. Regardless of a few merits of RVM such as giving probabilistic predictions and relax of parameter tuning, it has poor prediction for test instances that are far away from the relevance vectors. As a solution, we propose a new combination of RVM and k-nearest neighbor (k-NN) rule which resolves this issue with regionally dealing with every test instance. In our settings, we obtain the relevance vectors for each test instance in the local area given by k-NN rule. In this way, relevance vectors are closer and more relevant to the test instance which results in a more accurate model. This can be seen as a piece-wise learner which locally classifies test instances. The model is hence called localized relevance vector machine (LRVM). The LRVM is examined on several datasets of the University of California, Irvine (UCI) repository. Results supported by statistical tests indicate that the performance of LRVM is competitive as compared with a few state-of-the-art classifiers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03688](http://arxiv.org/abs/1904.03688)

##### PDF
[http://arxiv.org/pdf/1904.03688](http://arxiv.org/pdf/1904.03688)

