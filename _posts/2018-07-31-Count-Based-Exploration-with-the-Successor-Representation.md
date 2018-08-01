---
layout: post
title: "Count-Based Exploration with the Successor Representation"
date: 2018-07-31 01:25:44
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Marlos C. Machado, Marc G. Bellemare, Michael Bowling
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of exploration in reinforcement learning is well-understood in the tabular case and many sample-efficient algorithms are known. Nevertheless, it is often unclear how the algorithms in the tabular setting can be extended to tasks with large state-spaces where generalization is required. Recent promising developments generally depend on problem-specific density models or handcrafted features. In this paper we introduce a simple approach for exploration that allows us to develop theoretically justified algorithms in the tabular case but that also give us intuitions for new algorithms applicable to settings where function approximation is required. Our approach and its underlying theory is based on the substochastic successor representation, a concept we develop here. While the traditional successor representation is a representation that defines state generalization by the similarity of successor states, the substochastic successor representation is also able to implicitly count the number of times each state (or feature) has been observed. This extension connects two until now disjoint areas of research. We show in traditional tabular domains (RiverSwim and SixArms) that our algorithm empirically performs as well as other sample-efficient algorithms. We then describe a deep reinforcement learning algorithm inspired by these ideas and show that it matches the performance of recent pseudo-count-based methods in hard exploration Atari 2600 games.

##### Abstract (translated by Google)
在表格案例中很好地理解了强化学习中的探索问题，并且已知许多样本有效算法。然而，通常不清楚如何将表格设置中的算法扩展到具有需要泛化的大状态空间的任务。最近有希望的发展通常取决于特定问题的密度模型或手工制作的特征。在本文中，我们介绍了一种简单的探索方法，它允许我们在表格案例中开发理论上合理的算法，但这也为我们提供了适用于需要函数逼近的设置的新算法的直觉。我们的方法及其基础理论基于随机后继表示，这是我们在此开发的概念。虽然传统后继表示是通过后继状态的相似性来定义状态泛化的表示，但是随机后继表示也能够隐含地计算已经观察到每个状态（或特征）的次数。这个扩展连接了两个直到现在不相关的研究领域。我们在传统的表格域（RiverSwim和SixArms）中展示了我们的算法在经验上和其他样本有效算法一样。然后，我们描述了一个受这些想法启发的深度强化学习算法，并表明它与最近的基于伪计数的方法在硬探索Atari 2600游戏中的性能相匹配。

##### URL
[http://arxiv.org/abs/1807.11622](http://arxiv.org/abs/1807.11622)

##### PDF
[http://arxiv.org/pdf/1807.11622](http://arxiv.org/pdf/1807.11622)

