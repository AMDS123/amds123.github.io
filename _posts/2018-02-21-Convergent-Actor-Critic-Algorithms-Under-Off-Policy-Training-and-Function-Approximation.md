---
layout: post
title: "Convergent Actor-Critic Algorithms Under Off-Policy Training and Function Approximation"
date: 2018-02-21 23:14:44
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Hamid Reza Maei
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first class of policy-gradient algorithms that work with both state-value and policy function-approximation, and are guaranteed to converge under off-policy training. Our solution targets problems in reinforcement learning where the action representation adds to the-curse-of-dimensionality; that is, with continuous or large action sets, thus making it infeasible to estimate state-action value functions (Q functions). Using state-value functions helps to lift the curse and as a result naturally turn our policy-gradient solution into classical Actor-Critic architecture whose Actor uses state-value function for the update. Our algorithms, Gradient Actor-Critic and Emphatic Actor-Critic, are derived based on the exact gradient of averaged state-value function objective and thus are guaranteed to converge to its optimal solution, while maintaining all the desirable properties of classical Actor-Critic methods with no additional hyper-parameters. To our knowledge, this is the first time that convergent off-policy learning methods have been extended to classical Actor-Critic methods with function approximation.

##### Abstract (translated by Google)
我们提出了第一类与状态值和策略函数近似一起工作的策略梯度算法，并保证在非策略培训下收敛。我们的解决方案针对强化学习中的问题，其中行为表示会增加维度的诅咒;也就是说，连续的或大的动作集合，因此估计状态动作值函数（Q函数）是不可行的。使用状态值函数有助于解除诅咒，因此自然而然地将我们的策略梯度解决方案转化为Actor的批评架构，其Actor使用状态值函数进行更新。我们的算法，梯度演员 - 评论家和强调演员 - 批评者是基于平均状态值函数目标的确切梯度推导出来的，因此可以保证收敛到其最优解，同时保持经典演员 - 评论者方法的所有理想特性没有额外的超参数。就我们所知，这是第一次将收敛的关闭策略学习方法扩展到具有函数逼近的经典Actor  -  Critic方法。

##### URL
[http://arxiv.org/abs/1802.07842](http://arxiv.org/abs/1802.07842)

##### PDF
[http://arxiv.org/pdf/1802.07842](http://arxiv.org/pdf/1802.07842)

