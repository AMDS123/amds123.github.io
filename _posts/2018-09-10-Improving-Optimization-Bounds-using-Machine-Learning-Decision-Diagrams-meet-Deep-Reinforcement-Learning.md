---
layout: post
title: "Improving Optimization Bounds using Machine Learning: Decision Diagrams meet Deep Reinforcement Learning"
date: 2018-09-10 14:41:17
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning Optimization
author: Quentin Cappart, Emmanuel Goutierre, David Bergman, Louis-Martin Rousseau
mathjax: true
---

* content
{:toc}

##### Abstract
Finding tight bounds on the optimal solution is a critical element of practical solution methods for discrete optimization problems. In the last decade, decision diagrams (DDs) have brought a new perspective on obtaining upper and lower bounds that can be significantly better than classical bounding mechanisms, such as linear relaxations. It is well known that the quality of the bound achieved through this flexible bounding method is highly reliant on the ordering of variables chosen for building the diagram, and finding an ordering that optimizes standard metrics, or even improving one, is an NP-hard problem. In this paper, we propose an innovative and generic approach based on deep reinforcement learning for obtaining an ordering for tightening the bounds obtained with relaxed and restricted DDs. We apply the approach to both the Maximum Independent Set Problem and the Maximum Cut Problem. Experimental results on synthetic instances show that the deep reinforcement learning approach, by achieving tighter objective function bounds, generally outperforms ordering methods commonly used in the literature when the distribution of instances is known. To the best knowledge of the authors, this is the first paper to apply machine learning to directly improve relaxation bounds obtained by general-purpose bounding mechanisms for combinatorial optimization problems.

##### Abstract (translated by Google)
找到最优解的严格界限是离散优化问题的实际解决方法的关键要素。在过去的十年中，决策图（DDs）为获得上限和下限带来了新的视角，这些视角可以明显优于经典的边界机制，例如线性松弛。众所周知，通过这种灵活的边界方法实现的边界质量高度依赖于为构建图表而选择的变量的排序，并且找到优化标准度量或甚至改进标准度量的排序是NP难题。 。在本文中，我们提出了一种基于深度强化学习的创新和通用方法，以获得收紧放松和限制DD所获得的界限的顺序。我们将该方法应用于最大独立集问题和最大割问题。在合成实例上的实验结果表明，通过实现更严格的目标函数界限，深度强化学习方法通​​常优于实例分布时已知的文献中常用的排序方法。据作者所知，这是第一篇应用机器学习来直接改善组合优化问题的通用边界机制所获得的松弛界限的论文。

##### URL
[http://arxiv.org/abs/1809.03359](http://arxiv.org/abs/1809.03359)

##### PDF
[http://arxiv.org/pdf/1809.03359](http://arxiv.org/pdf/1809.03359)

