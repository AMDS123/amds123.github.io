---
layout: post
title: "Variance Reduction Methods for Sublinear Reinforcement Learning"
date: 2018-02-26 07:01:24
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Sham Kakade, Mengdi Wang, Lin F. Yang
mathjax: true
---

* content
{:toc}

##### Abstract
This work considers the problem of provably optimal reinforcement learning for (episodic) finite horizon MDPs, i.e. how an agent learns to maximize his/her (long term) reward in an uncertain environment. The main contribution is in providing a novel algorithm --- Variance-reduced Upper Confidence Q-learning (vUCQ) --- which enjoys a regret bound of $\widetilde{O}(\sqrt{HSAT} + H^5SA)$, where the $T$ is the number of time steps the agent acts in the MDP, $S$ is the number of states, $A$ is the number of actions, and $H$ is the (episodic) horizon time. 
 This is the first regret bound that is both sub-linear in the model size and asymptotically optimal. The algorithm is sub-linear in that the time to achieve $\epsilon$-average regret (for any constant $\epsilon$) is $O(SA)$, which is a number of samples that is far less than that required to learn any (non-trivial) estimate of the transition model (the transition model is specified by $O(S^2A)$ parameters). The importance of sub-linear algorithms is largely the motivation for algorithms such as $Q$-learning and other "model free" approaches. vUCQ algorithm also enjoys minimax optimal regret in the long run, matching the $\Omega(\sqrt{HSAT})$ lower bound. 
 Variance-reduced Upper Confidence Q-learning (vUCQ) is a successive refinement method in which the algorithm reduces the variance in $Q$-value estimates and couples this estimation scheme with an upper confidence based algorithm. Technically, the coupling of both of these techniques is what leads to the algorithm enjoying both the sub-linear regret property and the (asymptotically) optimal regret.

##### Abstract (translated by Google)
这项工作考虑了（情节性的）有限范围MDPs的可证明的最优强化学习问题，即一个智能体如何学习如何在不确定的环境中最大化他/她（长期）的奖励。主要贡献在于提供了一种新颖的算法 - 方差减少上置信问题学习（vUCQ）---它具有$ \ widetilde {O}（\ sqrt {HSAT} + H ^ 5SA）$ ，其中$ T $是代理人在MDP中行动的时间步数，$ S $是状态数，$ A $是动作数，$ H $是（情节）地平线时间。
 这是模型大小和渐近最优的第一个后悔约束。该算法是次线性的，因为实现$ \ epsilon $ -average后悔（对于任何常量$ \ epsilon $）的时间为$ O（SA）$，这是一些样本数远远小于学习转换模型的任何（非平凡）估计（转换模型由$ O（S ^ 2A）$参数指定）。亚线性算法的重要性主要是诸如$ Q $学习和其他“无模型”方法等算法的动机。 vUCQ算法在长期运行中也享有最小最优遗憾，匹配$ \ Omega（\ sqrt {HSAT}）$下界。
 方差降低的上置信度Q学习（vUCQ）是一种连续细化方法，其中该算法减少$ Q $  - 值估计中的方差，并将该估计方案与基于上置信度的算法相耦合。从技术上讲，这两种技术的耦合导致该算法同时具有亚线性遗憾属性和（渐近）最优遗憾。

##### URL
[http://arxiv.org/abs/1802.09184](http://arxiv.org/abs/1802.09184)

##### PDF
[http://arxiv.org/pdf/1802.09184](http://arxiv.org/pdf/1802.09184)

