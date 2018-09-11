---
layout: post
title: "Online Convex Optimization for Sequential Decision Processes and Extensive-Form Games"
date: 2018-09-10 01:28:24
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Gabriele Farina, Christian Kroer, Tuomas Sandholm
mathjax: true
---

* content
{:toc}

##### Abstract
Regret minimization is a powerful tool for solving large-scale extensive-form games. State-of-the-art methods rely on minimizing regret locally at each decision point. In this work we derive a new framework for regret minimization on sequential decision problems and extensive-form games with general compact convex sets at each decision point and general convex losses, as opposed to prior work which has been for simplex decision points and linear losses. We call our framework laminar regret decomposition. It generalizes the CFR algorithm to this more general setting. Furthermore, our framework enables a new proof of CFR even in the known setting, which is derived from a perspective of decomposing polytope regret, thereby leading to an arguably simpler interpretation of the algorithm. Our generalization to convex compact sets and convex losses allows us to develop new algorithms for several problems: regularized sequential decision making, regularized Nash equilibria in extensive-form games, and computing approximate extensive-form perfect equilibria. Our generalization also leads to the first regret-minimization algorithm for computing reduced-normal-form quantal response equilibria based on minimizing local regrets. Experiments show that our framework leads to algorithms that scale at a rate comparable to the fastest variants of counterfactual regret minimization for computing Nash equilibrium, and therefore our approach leads to the first algorithm for computing quantal response equilibria in extremely large games. Finally we show that our framework enables a new kind of scalable opponent exploitation approach.

##### Abstract (translated by Google)
遗憾最小化是解决大规模广泛形式游戏的有力工具。最先进的方法依赖于在每个决策点本地最大限度地减少遗憾。在这项工作中，我们推导出一个新的框架，用于顺序决策问题的遗憾最小化和在每个决策点具有一般紧致凸集和一般凸损失的广义形式博弈，而不是先前的单一决策点和线性损失的工作。我们称之为框架层流后悔分解。它将CFR算法推广到这个更一般的设置。此外，我们的框架即使在已知设置中也能够实现CFR的新证据，这是从分解多面体遗憾的角度得出的，从而导致对该算法的可解释的更简单的解释。我们对凸紧集和凸损失的推广使我们能够针对几个问题开发新算法：正则化顺序决策，广义形式博弈中的正则化纳什均衡，以及计算近似广义形式的完美均衡。我们的推广也导致了第一个基于最小化局部遗憾计算简约形式量子响应平衡的遗憾最小化算法。实验表明，我们的框架导致算法的扩展速度与用于计算纳什均衡的反事实后悔最小化的最快变体相当，因此我们的方法导致了在极大型游戏中计算量子响应均衡的第一种算法。最后，我们展示了我们的框架实现了一种新的可扩展的对手开发方法。

##### URL
[http://arxiv.org/abs/1809.03075](http://arxiv.org/abs/1809.03075)

##### PDF
[http://arxiv.org/pdf/1809.03075](http://arxiv.org/pdf/1809.03075)

