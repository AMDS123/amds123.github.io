---
layout: post
title: "Directly Estimating the Variance of the {lambda}-Return Using Temporal-Difference Methods"
date: 2018-01-25 06:48:14
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Craig Sherstan, Brendan Bennett, Kenny Young, Dylan R. Ashley, Adam White, Martha White, Richard S. Sutton
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates estimating the variance of a temporal-difference learning agent's update target. Most reinforcement learning methods use an estimate of the value function, which captures how good it is for the agent to be in a particular state and is mathematically expressed as the expected sum of discounted future rewards (called the return). These values can be straightforwardly estimated by averaging batches of returns using Monte Carlo methods. However, if we wish to update the agent's value estimates during learning--before terminal outcomes are observed--we must use a different estimation target called the {\lambda}-return, which truncates the return with the agent's own estimate of the value function. Temporal difference learning methods estimate the expected {\lambda}-return for each state, allowing these methods to update online and incrementally, and in most cases achieve better generalization error and faster learning than Monte Carlo methods. Naturally one could attempt to estimate higher-order moments of the {\lambda}-return. This paper is about estimating the variance of the {\lambda}-return. Prior work has shown that given estimates of the variance of the {\lambda}-return, learning systems can be constructed to (1) mitigate risk in action selection, and (2) automatically adapt the parameters of the learning process itself to improve performance. Unfortunately, existing methods for estimating the variance of the {\lambda}-return are complex and not well understood empirically. We contribute a method for estimating the variance of the {\lambda}-return directly using policy evaluation methods from reinforcement learning. Our approach is significantly simpler than prior methods that independently estimate the second moment of the {\lambda}-return. Empirically our new approach behaves at least as well as existing approaches, but is generally more robust.

##### Abstract (translated by Google)
本文研究估计一个时间差学习代理的更新目标的方差。大多数强化学习方法使用价值函数的估计值，其捕获代理人处于特定状态的优良程度，并在数学上表示为折扣未来奖励的预期总和（称为回报）。通过使用蒙特卡罗方法对多批回报进行平均，可以直接估计这些值。然而，如果我们希望在学习期间更新代理人的价值估计 - 在观察到终端结果之前 - 我们必须使用一个不同的估计目标，称为{\ lambda}  - 返回值，用代理人自己估计的价值功能。时间差分学习方法估计每个状态的预期收益率，允许这些方法在线更新，并且在大多数情况下比蒙特卡罗方法实现更好的泛化误差和更快的学习。自然地，人们可以尝试估计高阶矩。本文是关于估计{\ lambda}  - 返回的方差。以前的工作表明，给定估计的方差，学习系统可以被构造为（1）减少动作选择的风险，（2）自动调整学习过程本身的参数来提高性能。不幸的是，现有的估计方差的方法是复杂的，并且不能很好地理解。我们提供了一种直接使用强化学习的策略评估方法来估计{\ lambda}返回的方差的方法。我们的方法比先前的方法简单得多，这些方法可以独立估计返回的二阶矩。从经验上讲，我们的新方法至少和现有的方法一样，但通常更强大。

##### URL
[http://arxiv.org/abs/1801.08287](http://arxiv.org/abs/1801.08287)

##### PDF
[http://arxiv.org/pdf/1801.08287](http://arxiv.org/pdf/1801.08287)

