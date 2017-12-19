---
layout: post
title: "Toward `verifying' a Water Treatment System"
date: 2017-12-12 07:54:12
categories: arXiv_AI
tags: arXiv_AI
author: Jingyi Wang, Jun Sun, Yifan Jia
mathjax: true
---

* content
{:toc}

##### Abstract
Modeling and verifying real-world cyber-physical systems are challenging, especially so for complex systems where manually modeling is infeasible. In this work, we report our experience on combining model learning and abstraction refinement to analyze a challenging system, i.e., a real-world Secure Water Treatment (SWaT) system. Given a set of safety requirements, the objective is to either show that the system is safe with a high probability (so that a system shutdown is rarely triggered due to safety violation) or otherwise. As the system is too complicated to be manually modelled, we apply latest automatic model learning techniques to construct a set of Markov chains through abstraction and refinement, based on two long system execution logs (one for training and the other for testing). For each probabilistic property, we either report it does not hold with a certain level of probabilistic confidence, or report that it holds by showing the evidence in the form of an abstract Markov chain. The Markov chains can subsequently be implemented as runtime monitors in SWaT. This is the first case study of applying model learning techniques to a real-world system as far as we know.

##### Abstract (translated by Google)
对真实世界的网络物理系统进行建模和验证具有挑战性，特别是对于手动建模不可行的复杂系统。在这项工作中，我们汇报了模型学习和抽象精化相结合的经验，以分析一个具有挑战性的系统，即一个真实世界的安全水处理（SWaT）系统。给定一组安全要求，其目的是要么表明该系统是安全的，而且很有可能（因此，由于违反安全而很少触发系统关闭）或者其他情况。由于系统过于复杂，无法进行手工建模，因此我们采用最新的自动模型学习技术，通过抽象和细化，基于两个长的系统执行日志（一个用于训练，另一个用于测试）构建一组马尔可夫链。对于每个概率性质，我们要么报告它不具有一定的概率信度，要么通过以抽象马尔可夫链的形式显示证据来证明它是成立的。马尔可夫链随后可以在SWaT中实现为运行时监视器。据我们所知，这是第一个将模型学习技术应用于真实系统的案例研究。

##### URL
[https://arxiv.org/abs/1712.04155](https://arxiv.org/abs/1712.04155)

##### PDF
[https://arxiv.org/pdf/1712.04155](https://arxiv.org/pdf/1712.04155)

