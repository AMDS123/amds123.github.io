---
layout: post
title: "An Improved Generic Bet-and-Run Strategy for Speeding Up Stochastic Local Search"
date: 2018-06-23 15:36:04
categories: arXiv_AI
tags: arXiv_AI Knowledge Optimization Relation
author: Thomas Weise, Zijun Wu, Markus Wagner
mathjax: true
---

* content
{:toc}

##### Abstract
A commonly used strategy for improving optimization algorithms is to restart the algorithm when it is believed to be trapped in an inferior part of the search space. Building on the recent success of Bet-and-Run approaches for restarted local search solvers, we introduce an improved generic Bet-and-Run strategy. The goal is to obtain the best possible results within a given time budget t using a given black-box optimization algorithm. If no prior knowledge about problem features and algorithm behavior is available, the question about how to use the time budget most efficiently arises. We propose to first start k&gt;=1 independent runs of the algorithm during an initialization budget t1&lt;t, pausing these runs, then apply a decision maker D to choose 1&lt;=m&lt;=k runs from them (consuming t2&gt;=0 time units in doing so), and then continuing these runs for the remaining t3=t-t1-t2 time units. In previous Bet-and-Run strategies, the decision maker D=currentBest would simply select the run with the best- so-far results at negligible time. We propose using more advanced methods to discriminate between "good" and "bad" sample runs, with the goal of increasing the correlation of the chosen run with the a-posteriori best one. We test several different approaches, including neural networks trained or polynomials fitted on the current trace of the algorithm to predict which run may yield the best results if granted the remaining budget. We show with extensive experiments that this approach can yield better results than the previous methods, but also find that the currentBest method is a very reliable and robust baseline approach.

##### Abstract (translated by Google)
一种常用的改进优化算法的策略是当算法被困在搜索空间的较低部分时重新启动算法。基于重新启动的本地搜索解决方案最近成功实施“即投即跑”方法，我们引入了改进的通用投注 - 运行策略。目标是使用给定的黑盒优化算法在给定的时间预算t内获得最佳结果。如果没有关于问题特征和算法行为的先验知识，那么关于如何最有效地使用时间预算的问题就会出现。我们建议首先在初始化预算t1 <t期间开始算法的k> = 1次独立运行，暂停这些运行，然后应用决策者D以从它们中选择1≤m≤k运行（消耗t2> = 0这样做的时间单位），然后继续这些运行以获得剩余的t3 = t-t1-t2时间单位。在之前的投注 - 运行策略中，决策者D = currentBest只需在可忽略的时间选择具有最佳结果的运行。我们建议使用更高级的方法来区分“好”和“坏”样品运行，目标是增加所选运行与后验最佳运行的相关性。我们测试了几种不同的方法，包括训练好的神经网络或适合算法当前轨迹的多项式，以预测哪些运行在获得剩余预算时可能产生最佳结果。我们通过广泛的实验表明，这种方法比以前的方法可以产生更好的结果，但是也发现currentBest方法是一种非常可靠和可靠的基准方法。

##### URL
[http://arxiv.org/abs/1806.08984](http://arxiv.org/abs/1806.08984)

##### PDF
[http://arxiv.org/pdf/1806.08984](http://arxiv.org/pdf/1806.08984)

