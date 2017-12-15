---
layout: post
title: "Hierarchical Deep Reinforcement Learning: Integrating Temporal Abstraction and Intrinsic Motivation"
date: 2016-05-31 14:45:58
categories: arXiv_CV
tags: arXiv_CV Sparse Reinforcement_Learning Relation
author: Tejas D. Kulkarni, Karthik R. Narasimhan, Ardavan Saeedi, Joshua B. Tenenbaum
mathjax: true
---

* content
{:toc}

##### Abstract
Learning goal-directed behavior in environments with sparse feedback is a major challenge for reinforcement learning algorithms. The primary difficulty arises due to insufficient exploration, resulting in an agent being unable to learn robust value functions. Intrinsically motivated agents can explore new behavior for its own sake rather than to directly solve problems. Such intrinsic behaviors could eventually help the agent solve tasks posed by the environment. We present hierarchical-DQN (h-DQN), a framework to integrate hierarchical value functions, operating at different temporal scales, with intrinsically motivated deep reinforcement learning. A top-level value function learns a policy over intrinsic goals, and a lower-level function learns a policy over atomic actions to satisfy the given goals. h-DQN allows for flexible goal specifications, such as functions over entities and relations. This provides an efficient space for exploration in complicated environments. We demonstrate the strength of our approach on two problems with very sparse, delayed feedback: (1) a complex discrete stochastic decision process, and (2) the classic ATARI game `Montezuma's Revenge'.

##### Abstract (translated by Google)
在具有稀疏反馈的环境中学习目标导向的行为是强化学习算法的主要挑战。主要困难是由于探索不足导致代理人无法学习健全的价值功能。本质上动机的代理人可以为自己的缘故探索新的行为，而不是直接解决问题。这种内在的行为最终可以帮助代理人解决环境所造成的任务。我们提出了层次DQN（h-DQN），这是一个集成分层价值函数的框架，在不同的时间尺度上运行，具有内在动机的深层强化学习。一个顶层的价值函数学习一个关于内在目标的策略，而一个较低层次的函数学习一个关于原子动作的策略来满足既定的目标。 h-DQN允许灵活的目标规范，如对实体和关系的功能。这为在复杂的环境中进行勘探提供了有效的空间。我们证明了我们的方法在非常稀疏，延迟反馈的两个问题上的优势：（1）复杂的离散随机决策过程;（2）经典的ATARI游戏“蒙特苏马的复仇”。

##### URL
[https://arxiv.org/abs/1604.06057](https://arxiv.org/abs/1604.06057)

##### PDF
[https://arxiv.org/pdf/1604.06057](https://arxiv.org/pdf/1604.06057)

