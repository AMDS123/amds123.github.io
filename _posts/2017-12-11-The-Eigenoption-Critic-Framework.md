---
layout: post
title: "The Eigenoption-Critic Framework"
date: 2017-12-11 23:21:42
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Miao Liu, Marlos C. Machado, Gerald Tesauro, Murray Campbell
mathjax: true
---

* content
{:toc}

##### Abstract
Eigenoptions (EOs) have been recently introduced as a promising idea for generating a diverse set of options through the graph Laplacian, having been shown to allow efficient exploration. Despite its initial promising results, a couple of issues in current algorithms limit its application, namely: (1) EO methods require two separate steps (eigenoption discovery and reward maximization) to learn a control policy, which can incur a significant amount of storage and computation; (2) EOs are only defined for problems with discrete state-spaces and; (3) it is not easy to take the environment's reward function into consideration when discovering EOs. To addresses these issues, we introduce an algorithm termed eigenoption-critic (EOC) based on the Option-critic (OC) framework [Bacon17], a general hierarchical reinforcement learning (RL) algorithm that allows learning the intra-option policies simultaneously with the policy over options. We also propose a generalization of EOC to problems with continuous state-spaces through the Nystr\"om approximation. EOC can also be seen as extending OC to nonstationary settings, where the discovered options are not tailored for a single task.

##### Abstract (translated by Google)
Eigenoptions（EO）最近被引入作为一个有希望的想法，通过图拉普拉斯算子产生了多种选择，已被证明可以进行有效的探索。尽管最初的结果是令人鼓舞的，但目前算法中的一些问题限制了它的应用，即：（1）EO方法需要两个独立的步骤（特征选择发现和奖励最大化）来学习控制策略，这会产生大量的存储和计算; （2）EO只针对离散状态空间的问题而定义; （3）在发现驻外办事处时，要考虑环境的回报功能并不容易。为了解决这些问题，我们引入了基于期权评论（OC）框架[Bacon17]的一种称为特征选择批评（EOC）的算法，一种通用的分层强化学习（RL）算法，允许学习期权内政策政策的选择。我们还提出了通过Nystr的近似将EOC推广到连续状态空间的问题，EOC也可以被看作是将OC扩展到非平稳的环境，其中发现的选项不是针对单个任务的。

##### URL
[https://arxiv.org/abs/1712.04065](https://arxiv.org/abs/1712.04065)

##### PDF
[https://arxiv.org/pdf/1712.04065](https://arxiv.org/pdf/1712.04065)

