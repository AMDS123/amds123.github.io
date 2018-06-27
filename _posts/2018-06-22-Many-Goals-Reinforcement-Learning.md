---
layout: post
title: "Many-Goals Reinforcement Learning"
date: 2018-06-22 18:31:24
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Vivek Veeriah, Junhyuk Oh, Satinder Singh
mathjax: true
---

* content
{:toc}

##### Abstract
All-goals updating exploits the off-policy nature of Q-learning to update all possible goals an agent could have from each transition in the world, and was introduced into Reinforcement Learning (RL) by Kaelbling (1993). In prior work this was mostly explored in small-state RL problems that allowed tabular representations and where all possible goals could be explicitly enumerated and learned separately. In this paper we empirically explore 3 different extensions of the idea of updating many (instead of all) goals in the context of RL with deep neural networks (or DeepRL for short). First, in a direct adaptation of Kaelbling's approach we explore if many-goals updating can be used to achieve mastery in non-tabular visual-observation domains. Second, we explore whether many-goals updating can be used to pre-train a network to subsequently learn faster and better on a single main task of interest. Third, we explore whether many-goals updating can be used to provide auxiliary task updates in training a network to learn faster and better on a single main task of interest. We provide comparisons to baselines for each of the 3 extensions.

##### Abstract (translated by Google)
所有目标更新利用Q学习的非政策性质来更新代理人可能从世界上每个转变中获得的所有可能目标，并由Kaelbling（1993）引入到强化学习（RL）中。在之前的工作中，这主要是在小型国家RL问题上进行探索，这些问题允许表格表示，并且所有可能的目标都可以明确列举和分别学习。在本文中，我们通过实证研究了RL在深度神经网络（或简称DeepRL）环境下更新许多（而非全部）目标的想法的3种不同扩展。首先，在Kaelbling方法的直接改编中，我们探讨了是否可以使用多目标更新来实现非表格视觉观察领域的掌握。其次，我们探讨是否可以使用多目标更新来预先训练一个网络，以便随后在单个感兴趣的主要任务上更快更好地学习。第三，我们探讨是否可以使用多目标更新来提供辅助任务更新以培训网络，从而更快，更好地学习单个感兴趣的主要任务。我们提供3个扩展中每一个的基线比较。

##### URL
[http://arxiv.org/abs/1806.09605](http://arxiv.org/abs/1806.09605)

##### PDF
[http://arxiv.org/pdf/1806.09605](http://arxiv.org/pdf/1806.09605)

