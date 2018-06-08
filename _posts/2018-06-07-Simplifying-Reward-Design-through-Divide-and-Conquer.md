---
layout: post
title: "Simplifying Reward Design through Divide-and-Conquer"
date: 2018-06-07 03:49:05
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Ellis Ratner, Dylan Hadfield-Menell, Anca D. Dragan
mathjax: true
---

* content
{:toc}

##### Abstract
Designing a good reward function is essential to robot planning and reinforcement learning, but it can also be challenging and frustrating. The reward needs to work across multiple different environments, and that often requires many iterations of tuning. We introduce a novel divide-and-conquer approach that enables the designer to specify a reward separately for each environment. By treating these separate reward functions as observations about the underlying true reward, we derive an approach to infer a common reward across all environments. We conduct user studies in an abstract grid world domain and in a motion planning domain for a 7-DOF manipulator that measure user effort and solution quality. We show that our method is faster, easier to use, and produces a higher quality solution than the typical method of designing a reward jointly across all environments. We additionally conduct a series of experiments that measure the sensitivity of these results to different properties of the reward design task, such as the number of environments, the number of feasible solutions per environment, and the fraction of the total features that vary within each environment. We find that independent reward design outperforms the standard, joint, reward design process but works best when the design problem can be divided into simpler subproblems.

##### Abstract (translated by Google)
设计一个好的奖励功能对机器人规划和强化学习至关重要，但它也可能具有挑战性和令人沮丧。奖励需要在多个不同的环境中工作，并且这往往需要许多重复的调整。我们引入了一种新颖的分而治之的方法，使设计师能够为每个环境单独指定奖励。通过将这些单独的奖励功能视为对潜在真实奖励的观察，我们得出一种方法来推断所有环境中的共同奖励。我们在抽象网格世界领域和运动规划领域进行用户研究，用于测量用户工作量和解决方案质量的7自由度机械手。我们表明，我们的方法更快，更易于使用，并且产生比在所有环境中共同设计奖励的典型方法更高质量的解决方案。我们另外进行了一系列实验，测量这些结果对奖励设计任务的不同属性的敏感性，例如环境数量，每个环境的可行解决方案数量以及每个环境中总体特征的百分比。我们发现独立奖励设计胜过标准，联合，奖励设计流程，但在设计问题可以分解为更简单的子问题时效果最佳。

##### URL
[http://arxiv.org/abs/1806.02501](http://arxiv.org/abs/1806.02501)

##### PDF
[http://arxiv.org/pdf/1806.02501](http://arxiv.org/pdf/1806.02501)

