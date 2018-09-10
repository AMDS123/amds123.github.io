---
layout: post
title: "Monte Carlo Tree Search with Scalable Simulation Periods for Continuously Running Tasks"
date: 2018-09-07 09:56:21
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Seydou Ba, Takuya Hiraoka, Takashi Onishi, Toru Nakata, Yoshimasa Tsuruoka
mathjax: true
---

* content
{:toc}

##### Abstract
Monte Carlo Tree Search (MCTS) is particularly adapted to domains where the potential actions can be represented as a tree of sequential decisions. For an effective action selection, MCTS performs many simulations to build a reliable tree representation of the decision space. As such, a bottleneck to MCTS appears when enough simulations cannot be performed between action selections. This is particularly highlighted in continuously running tasks, for which the time available to perform simulations between actions tends to be limited due to the environment's state constantly changing. In this paper, we present an approach that takes advantage of the anytime characteristic of MCTS to increase the simulation time when allowed. Our approach is to effectively balance the prospect of selecting an action with the time that can be spared to perform MCTS simulations before the next action selection. For that, we considered the simulation time as a decision variable to be selected alongside an action. We extended the Hierarchical Optimistic Optimization applied to Tree (HOOT) method to adapt our approach to environments with a continuous decision space. We evaluated our approach for environments with a continuous decision space through OpenAI gym's Pendulum and Continuous Mountain Car environments and for environments with discrete action space through the arcade learning environment (ALE) platform. The evaluation results show that, with variable simulation times, the proposed approach outperforms the conventional MCTS in the evaluated continuous decision space tasks and improves the performance of MCTS in most of the ALE tasks.

##### Abstract (translated by Google)
蒙特卡罗树搜索（MCTS）特别适用于可以将潜在行动表示为顺序决策树的域。对于有效的动作选择，MCTS执行许多模拟以构建决策空间的可靠树表示。因此，当在动作选择之间不能进行足够的模拟时，会出现MCTS的瓶颈。这在连续运行的任务中尤为突出，由于环境的状态不断变化，因此可以在行动之间执行模拟的时间受到限制。在本文中，我们提出了一种方法，利用MCTS的任何时间特性来增加允许时的仿真时间。我们的方法是有效地平衡选择动作的前景与在下一个动作选择之前可以执行MCTS模拟的时间。为此，我们将模拟时间视为与动作一起选择的决策变量。我们扩展了应用于树（HOOT）方法的分层乐观优化，以使我们的方法适应具有连续决策空间的环境。我们通过OpenAI健身房的Pendulum和Continuous Mountain Car环境以及通过街机学习环境（ALE）平台的具有离散动作空间的环境评估我们的方法，以获得具有连续决策空间的环境。评估结果表明，在可变仿真时间内，所提出的方法在评估的连续决策空间任务中优于传统MCTS，并且在大多数ALE任务中提高了MCTS的性能。

##### URL
[http://arxiv.org/abs/1809.02378](http://arxiv.org/abs/1809.02378)

##### PDF
[http://arxiv.org/pdf/1809.02378](http://arxiv.org/pdf/1809.02378)

