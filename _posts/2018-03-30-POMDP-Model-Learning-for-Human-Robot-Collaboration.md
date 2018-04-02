---
layout: post
title: "POMDP Model Learning for Human Robot Collaboration"
date: 2018-03-30 01:09:30
categories: arXiv_RO
tags: arXiv_RO Face
author: Wei Zheng, Bo Wu, Hai Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have seen human robot collaboration (HRC) quickly emerged as a hot research area at the intersection of control, robotics, and psychology. While most of the existing work in HRC focused on either low-level human-aware motion planning or HRC interface design, we are particularly interested in a formal design of HRC with respect to high-level complex missions, where it is of critical importance to obtain an accurate and meanwhile tractable human model. Instead of assuming the human model is given, we ask whether it is reasonable to learn human models from observed perception data, such as the gesture, eye movements, head motions of the human in concern. As our initial step, we adopt a partially observable Markov decision process (POMDP) model in this work as mounting evidences have suggested Markovian properties of human behaviors from psychology studies. In addition, POMDP provides a general modeling framework for sequential decision making where states are hidden and actions have stochastic outcomes. Distinct from the majority of POMDP model learning literature, we do not assume that the state, the transition structure or the bound of the number of states in POMDP model is given. Instead, we use a Bayesian non-parametric learning approach to decide the potential human states from data. Then we adopt an approach inspired by probably approximately correct (PAC) learning to obtain not only an estimation of the transition probability but also a confidence interval associated to the estimation. Then, the performance of applying the control policy derived from the estimated model is guaranteed to be sufficiently close to the true model. Finally, data collected from a driver-assistance test-bed are used to train the model, which illustrates the effectiveness of the proposed learning method.

##### Abstract (translated by Google)
近年来，人类机器人协作（HRC）迅速成为控制，机器人和心理学交叉领域的热门研究领域。尽管HRC现有的大部分工作都集中在低级别的人类意识运动计划或HRC界面设计上，但我们对高级别复杂任务的正式HRC设计特别感兴趣，因为它对于高级别复杂任务至关重要获得准确和同时易处理的人体模型。我们不是假设给出了人体模型，而是询问从观察到的感知数据（例如手势，眼球运动，所关心的人的头部运动）中学习人体模型是否合理。作为我们的第一步，我们在这项工作中采用了部分可观察的马尔可夫决策过程（POMDP）模型，因为越来越多的证据表明马尔可夫的心理学研究中的人类行为属性。另外，POMDP提供了一个通用的建模框架，用于顺序决策，其中状态是隐藏的，动作具有随机结果。与大多数POMDP模型学习文献不同的是，我们不假设POMDP模型中的状态数目，过渡结构或状态数目的界限。相反，我们使用贝叶斯非参数学习方法从数据中确定潜在的人类状态。然后，我们采用一种可能近似正确（PAC）学习的方法来获得不仅对转移概率的估计，而且还获得与估计相关联的置信区间。然后，应用从估计模型导出的控制策略的性能保证足够接近真实模型。最后，从驾驶员辅助测试台收集的数据被用来训练模型，其说明了所提出的学习方法的有效性。

##### URL
[http://arxiv.org/abs/1803.11300](http://arxiv.org/abs/1803.11300)

##### PDF
[http://arxiv.org/pdf/1803.11300](http://arxiv.org/pdf/1803.11300)

