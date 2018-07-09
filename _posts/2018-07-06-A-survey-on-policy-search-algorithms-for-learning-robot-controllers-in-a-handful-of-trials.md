---
layout: post
title: "A survey on policy search algorithms for learning robot controllers in a handful of trials"
date: 2018-07-06 08:14:27
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning Survey Optimization
author: Konstantinos Chatzilygeroudis, Vassilis Vassiliades, Freek Stulp, Sylvain Calinon, Jean-Baptiste Mouret
mathjax: true
---

* content
{:toc}

##### Abstract
Most policy search algorithms require thousands of training episodes to find an effective policy, which is often infeasible with a physical robot. This survey article focuses on the extreme other end of the spectrum: how can a robot adapt with only a handful of trials (a dozen) and a few minutes? By analogy with the word "big-data", we refer to this challenge as "micro-data reinforcement learning". We show that a first strategy is to leverage prior knowledge on the policy structure (e.g., dynamic movement primitives), on the policy parameters (e.g., demonstrations), or on the dynamics (e.g., simulators). A second strategy is to create data-driven surrogate models of the expected reward (e.g., Bayesian optimization) or the dynamical model (e.g., model-based policy search), so that the policy optimizer queries the model instead of the real system. Overall, all successful micro-data algorithms combine these two strategies by varying the kind of model and prior knowledge. The current scientific challenges essentially revolve around scaling up to complex robots (e.g., humanoids), designing generic priors, and optimizing the computing time.

##### Abstract (translated by Google)
大多数策略搜索算法需要数千个训练集才能找到有效的策略，这对于物理机器人来说通常是不可行的。这篇调查文章侧重于极端的另一端：机器人如何才能适应少数试验（一打）和几分钟？通过类比“大数据”这个词，我们将这一挑战称为“微观数据强化学习”。我们表明，第一种策略是利用关于策略结构的先验知识（例如，动态移动原语），关于策略参数（例如，演示）或动态（例如，模拟器）。第二种策略是创建预期奖励（例如，贝叶斯优化）或动态模型（例如，基于模型的策略搜索）的数据驱动的替代模型，以便策略优化器查询模型而不是真实系统。总的来说，所有成功的微观数据算法都通过改变模型的类型和先验知识来结合这两种策略。当前的科学挑战主要围绕扩展到复杂机器人（例如，人形机器人），设计通用先验，以及优化计算时间。

##### URL
[http://arxiv.org/abs/1807.02303](http://arxiv.org/abs/1807.02303)

##### PDF
[http://arxiv.org/pdf/1807.02303](http://arxiv.org/pdf/1807.02303)

