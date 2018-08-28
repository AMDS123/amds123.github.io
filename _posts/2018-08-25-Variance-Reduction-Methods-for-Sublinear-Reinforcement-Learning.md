---
layout: post
title: "Variance Reduction Methods for Sublinear Reinforcement Learning"
date: 2018-08-25 05:22:45
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Sham Kakade, Mengdi Wang, Lin F. Yang
mathjax: true
---

* content
{:toc}

##### Abstract
This work considers the problem of provably optimal reinforcement learning for episodic finite horizon MDPs, i.e. how an agent learns to maximize his/her long term reward in an uncertain environment. The main contribution is in providing a novel algorithm --- Variance-reduced Upper Confidence Q-learning (vUCQ) --- which enjoys a regret bound of $\widetilde{O}(\sqrt{HSAT} + H^5SA)$, where the $T$ is the number of time steps the agent acts in the MDP, $S$ is the number of states, $A$ is the number of actions, and $H$ is the (episodic) horizon time. 
 This is the first regret bound that is both sub-linear in the model size and asymptotically optimal. The algorithm is sub-linear in that the time to achieve $\epsilon$-average regret for any constant $\epsilon$ is $O(SA)$, which is a number of samples that is far less than that required to learn any non-trivial estimate of the transition model (the transition model is specified by $O(S^2A)$ parameters). The importance of sub-linear algorithms is largely the motivation for algorithms such as $Q$-learning and other "model free" approaches. vUCQ algorithm also enjoys minimax optimal regret in the long run, matching the $\Omega(\sqrt{HSAT})$ lower bound. 
 Variance-reduced Upper Confidence Q-learning (vUCQ) is a successive refinement method in which the algorithm reduces the variance in $Q$-value estimates and couples this estimation scheme with an upper confidence based algorithm. Technically, the coupling of both of these techniques is what leads to the algorithm enjoying both the sub-linear regret property and the asymptotically optimal regret.

##### Abstract (translated by Google)
这项工作考虑了对于情节有限地平线MDP的可证明最佳强化学习的问题，即代理如何在不确定的环境中学习最大化他/她的长期奖励。主要贡献在于提供一种新颖的算法---方差减少的上信心Q学习（vUCQ）---它具有$ \ widetilde {O}（\ sqrt {HSAT} + H ^ 5SA）$的后悔限制，其中$ T $是代理在MDP中行动的时间步数，$ S $是状态数，$ A $是行动数，$ H $是（偶发）时间范围。
 这是第一个在模型尺寸上呈亚线性且渐近最优的后悔界限。该算法是次线性的，因为任何常量$ \ epsilon $实现$ \ epsilon $ -average遗憾的时间是$ O（SA）$，这是一些远远少于学习任何东西所需的样本。过渡模型的非平凡估计（过渡模型由$ O（S ^ 2A）$参数指定）。子线性算法的重要性在很大程度上是诸如$ Q $ -learning和其他“无模型”方法之类的算法的动机。从长远来看，vUCQ算法也享有minimax最佳遗憾，匹配$ \ Omega（\ sqrt {HSAT}）$下限。
 方差减少的上置信Q-学习（vUCQ）是一种连续的细化方法，其中该算法减少$ Q $  - 值估计的方差，并将该估计方案与基于上置信度的算法耦合。从技术上讲，这两种技术的结合是导致算法同时享受亚线性后悔属性和渐近最优遗憾的原因。

##### URL
[http://arxiv.org/abs/1802.09184](http://arxiv.org/abs/1802.09184)

##### PDF
[http://arxiv.org/pdf/1802.09184](http://arxiv.org/pdf/1802.09184)

