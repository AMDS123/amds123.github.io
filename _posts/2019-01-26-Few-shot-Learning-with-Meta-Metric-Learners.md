---
layout: post
title: "Few-shot Learning with Meta Metric Learners"
date: 2019-01-26 01:55:33
categories: arXiv_AI
tags: arXiv_AI
author: Yu Cheng, Mo Yu, Xiaoxiao Guo, Bowen Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Few-shot Learning aims to learn classifiers for new classes with only a few training examples per class. Existing meta-learning or metric-learning based few-shot learning approaches are limited in handling diverse domains with various number of labels. The meta-learning approaches train a meta learner to predict weights of homogeneous-structured task-specific networks, requiring a uniform number of classes across tasks. The metric-learning approaches learn one task-invariant metric for all the tasks, and they fail if the tasks diverge. We propose to deal with these limitations with meta metric learning. Our meta metric learning approach consists of task-specific learners, that exploit metric learning to handle flexible labels, and a meta learner, that discovers good parameters and gradient decent to specify the metrics in task-specific learners. Thus the proposed model is able to handle unbalanced classes as well as to generate task-specific metrics. We test our approach in the `$k$-shot $N$-way' few-shot learning setting used in previous work and new realistic few-shot setting with diverse multi-domain tasks and flexible label numbers. Experiments show that our approach attains superior performances in both settings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09890](http://arxiv.org/abs/1901.09890)

##### PDF
[http://arxiv.org/pdf/1901.09890](http://arxiv.org/pdf/1901.09890)

