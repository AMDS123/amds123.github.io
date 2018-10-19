---
layout: post
title: "Dynamic Ensemble Active Learning: A Non-Stationary Bandit with Expert Advice"
date: 2018-09-29 14:29:02
categories: arXiv_AI
tags: arXiv_AI
author: Kunkun Pang, Mingzhi Dong, Yang Wu, Timothy M. Hospedales
mathjax: true
---

* content
{:toc}

##### Abstract
Active learning aims to reduce annotation cost by predicting which samples are useful for a human teacher to label. However it has become clear there is no best active learning algorithm. Inspired by various philosophies about what constitutes a good criteria, different algorithms perform well on different datasets. This has motivated research into ensembles of active learners that learn what constitutes a good criteria in a given scenario, typically via multi-armed bandit algorithms. Though algorithm ensembles can lead to better results, they overlook the fact that not only does algorithm efficacy vary across datasets, but also during a single active learning session. That is, the best criteria is non-stationary. This breaks existing algorithms' guarantees and hampers their performance in practice. In this paper, we propose dynamic ensemble active learning as a more general and promising research direction. We develop a dynamic ensemble active learner based on a non-stationary multi-armed bandit with expert advice algorithm. Our dynamic ensemble selects the right criteria at each step of active learning. It has theoretical guarantees, and shows encouraging results on $13$ popular datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.07778](https://arxiv.org/abs/1810.07778)

##### PDF
[https://arxiv.org/pdf/1810.07778](https://arxiv.org/pdf/1810.07778)

