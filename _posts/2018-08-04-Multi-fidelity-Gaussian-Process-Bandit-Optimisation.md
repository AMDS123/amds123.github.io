---
layout: post
title: "Multi-fidelity Gaussian Process Bandit Optimisation"
date: 2018-08-04 01:25:57
categories: arXiv_AI
tags: arXiv_AI
author: Kirthevasan Kandasamy, Gautam Dasarathy, Junier B. Oliva, Jeff Schneider, Barnabas Poczos
mathjax: true
---

* content
{:toc}

##### Abstract
In many scientific and engineering applications, we are tasked with the maximisation of an expensive to evaluate black box function $f$. Traditional settings for this problem assume just the availability of this single function. However, in many cases, cheap approximations to $f$ may be obtainable. For example, the expensive real world behaviour of a robot can be approximated by a cheap computer simulation. We can use these approximations to eliminate low function value regions cheaply and use the expensive evaluations of $f$ in a small but promising region and speedily identify the optimum. We formalise this task as a \emph{multi-fidelity} bandit problem where the target function and its approximations are sampled from a Gaussian process. We develop MF-GP-UCB, a novel method based on upper confidence bound techniques. In our theoretical analysis we demonstrate that it exhibits precisely the above behaviour, and achieves better regret than strategies which ignore multi-fidelity information. Empirically, MF-GP-UCB outperforms such naive strategies and other multi-fidelity methods on several synthetic and real experiments.

##### Abstract (translated by Google)
在许多科学和工程应用中，我们的任务是最大化昂贵的评估黑盒功能$ f $。此问题的传统设置仅假设此单个函数的可用性。但是，在许多情况下，可以获得$ f $的便宜近似值。例如，机器人的昂贵的现实世界行为可以通过廉价的计算机模拟来近似。我们可以使用这些近似值来廉价地消除低功能值区域，并在一个小而有希望的区域中使用昂贵的$ f $评估并快速确定最佳值。我们将此任务形式化为\ emph {multi-fidelity}强盗问题，其中目标函数及其近似值是从高斯过程中采样的。我们开发了MF-GP-UCB，一种基于上置信界限技术的新方法。在我们的理论分析中，我们证明它恰好表现出上述行为，并且比忽略多保真信息的策略实现更好的遗憾。根据经验，MF-GP-UCB在几个合成和真实实验中优于这种天真的策略和其他多保真方法。

##### URL
[http://arxiv.org/abs/1603.06288](http://arxiv.org/abs/1603.06288)

##### PDF
[http://arxiv.org/pdf/1603.06288](http://arxiv.org/pdf/1603.06288)

