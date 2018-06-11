---
layout: post
title: "Programmatically Interpretable Reinforcement Learning"
date: 2018-06-08 02:27:26
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Abhinav Verma, Vijayaraghavan Murali, Rishabh Singh, Pushmeet Kohli, Swarat Chaudhuri
mathjax: true
---

* content
{:toc}

##### Abstract
We present a reinforcement learning framework, called Programmatically Interpretable Reinforcement Learning (PIRL), that is designed to generate interpretable and verifiable agent policies. Unlike the popular Deep Reinforcement Learning (DRL) paradigm, which represents policies by neural networks, PIRL represents policies using a high-level, domain-specific programming language. Such programmatic policies have the benefits of being more easily interpreted than neural networks, and being amenable to verification by symbolic methods. We propose a new method, called Neurally Directed Program Search (NDPS), for solving the challenging nonsmooth optimization problem of finding a programmatic policy with maximal reward. NDPS works by first learning a neural policy network using DRL, and then performing a local search over programmatic policies that seeks to minimize a distance from this neural "oracle". We evaluate NDPS on the task of learning to drive a simulated car in the TORCS car-racing environment. We demonstrate that NDPS is able to discover human-readable policies that pass some significant performance bars. We also show that PIRL policies can have smoother trajectories, and can be more easily transferred to environments not encountered during training, than corresponding policies discovered by DRL.

##### Abstract (translated by Google)
我们提出了一个强化学习框架，称为编程式可解释强化学习（PIRL），旨在生成可解释和可验证的代理策略。与流行的Deep Reinforcement Learning（DRL）范式不同，后者代表了神经网络的策略，PIRL使用高级的，特定领域的编程语言来表示策略。这种程序化政策的好处是比神经网络更容易解释，并且可以通过符号方法进行验证。我们提出了一种称为神经导向程序搜索（NDPS）的新方法，用于解决寻找具有最大奖励的程序化策略的具有挑战性的非光滑优化问题。 NDPS首先通过使用DRL学习一个神经策略网络，然后对程序化策略进行局部搜索，试图将距离这个神经“oracle”的距离最小化。我们评估NDPS的任务是学习在TORCS赛车环境中驾驶模拟汽车。我们证明NDPS能够发现通过一些重要性能条的人类可读的策略。我们还表明PIRL策略可以具有更平滑的轨迹，并且可以更容易地转移到培训期间未遇到的环境，而不是DRL发现的相应策略。

##### URL
[http://arxiv.org/abs/1804.02477](http://arxiv.org/abs/1804.02477)

##### PDF
[http://arxiv.org/pdf/1804.02477](http://arxiv.org/pdf/1804.02477)

