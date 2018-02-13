---
layout: post
title: "Path Consistency Learning in Tsallis Entropy Regularized MDPs"
date: 2018-02-10 01:57:49
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Relation
author: Ofir Nachum, Yinlam Chow, Mohammad Ghavamzadeh
mathjax: true
---

* content
{:toc}

##### Abstract
We study the sparse entropy-regularized reinforcement learning (ERL) problem in which the entropy term is a special form of the Tsallis entropy. The optimal policy of this formulation is sparse, i.e.,~at each state, it has non-zero probability for only a small number of actions. This addresses the main drawback of the standard Shannon entropy-regularized RL (soft ERL) formulation, in which the optimal policy is softmax, and thus, may assign a non-negligible probability mass to non-optimal actions. This problem is aggravated as the number of actions is increased. In this paper, we follow the work of Nachum et al. (2017) in the soft ERL setting, and propose a class of novel path consistency learning (PCL) algorithms, called {\em sparse PCL}, for the sparse ERL problem that can work with both on-policy and off-policy data. We first derive a {\em sparse consistency} equation that specifies a relationship between the optimal value function and policy of the sparse ERL along any system trajectory. Crucially, a weak form of the converse is also true, and we quantify the sub-optimality of a policy which satisfies sparse consistency, and show that as we increase the number of actions, this sub-optimality is better than that of the soft ERL optimal policy. We then use this result to derive the sparse PCL algorithms. We empirically compare sparse PCL with its soft counterpart, and show its advantage, especially in problems with a large number of actions.

##### Abstract (translated by Google)
我们研究稀疏熵正则化强化学习（ERL）问题，其中熵项是Tsallis熵的一种特殊形式。这个公式的最优策略是稀疏的，也就是说，在每个状态下，只有少量行为具有非零概率。这解决了标准香农熵正则化RL（软ERL）公式的主要缺点，其中最优策略是softmax，因此可以将不可忽略的概率质量分配给非最优行动。随着行动次数的增加，这个问题变得更加严重。在本文中，我们遵循Nachum等人的工作。 （2017）在软ERL设置中，针对稀疏ERL问题提出了一类新的路径一致性学习（PCL）算法，称为{\ em稀疏PCL}，该算法可以同时处理策略中和非策略数据。我们首先导出一个稀疏一致性方程，它指定了沿着任何系统轨迹的稀疏ERL的最优值函数和策略之间的关系。至关重要的是，反面的弱形式也是如此，我们量化了满足稀疏一致性的策略的次优性，并且表明当我们增加行动次数时，这个次优性比软ERL最佳政策。然后我们使用这个结果来导出稀疏的PCL算法。我们通过实证比较稀疏的PCL和它的软对应，并展示它的优势，特别是在大量行为的问题上。

##### URL
[http://arxiv.org/abs/1802.03501](http://arxiv.org/abs/1802.03501)

##### PDF
[http://arxiv.org/pdf/1802.03501](http://arxiv.org/pdf/1802.03501)

