---
layout: post
title: "Deep Bayesian Active Learning for Natural Language Processing: Results of a Large-Scale Empirical Study"
date: 2018-08-16 22:46:40
categories: arXiv_CL
tags: arXiv_CL Deep_Learning
author: Aditya Siddhant, Zachary C. Lipton
mathjax: true
---

* content
{:toc}

##### Abstract
Several recent papers investigate Active Learning (AL) for mitigating the data dependence of deep learning for natural language processing. However, the applicability of AL to real-world problems remains an open question. While in supervised learning, practitioners can try many different methods, evaluating each against a validation set before selecting a model, AL affords no such luxury. Over the course of one AL run, an agent annotates its dataset exhausting its labeling budget. Thus, given a new task, an active learner has no opportunity to compare models and acquisition functions. This paper provides a large scale empirical study of deep active learning, addressing multiple tasks and, for each, multiple datasets, multiple models, and a full suite of acquisition functions. We find that across all settings, Bayesian active learning by disagreement, using uncertainty estimates provided either by Dropout or Bayes-by Backprop significantly improves over i.i.d. baselines and usually outperforms classic uncertainty sampling.

##### Abstract (translated by Google)
最近的几篇论文研究了主动学习（AL），以减轻深度学习对自然语言处理的数据依赖性。然而，AL对现实问题的适用性仍然是一个悬而未决的问题。在监督学习中，从业者可以尝试许多不同的方法，在选择模型之前根据验证集评估每个方法，AL不提供这样的奢侈。在一次AL运行过程中，代理会对其数据集进行注释，从而耗尽其标签预算。因此，在给定新任务的情况下，主动学习者没有机会比较模型和采集功能。本文提供了深度主动学习的大规模实证研究，解决了多个任务，并针对每个任务，多个数据集，多个模型和一整套采集功能。我们发现，在所有设置中，通过分歧进行贝叶斯主动学习，使用由Dropout或Bayes-by Backprop提供的不确定性估计，显着提高了i.i.d.基线并且通常优于经典的不确定性抽样。

##### URL
[http://arxiv.org/abs/1808.05697](http://arxiv.org/abs/1808.05697)

##### PDF
[http://arxiv.org/pdf/1808.05697](http://arxiv.org/pdf/1808.05697)

