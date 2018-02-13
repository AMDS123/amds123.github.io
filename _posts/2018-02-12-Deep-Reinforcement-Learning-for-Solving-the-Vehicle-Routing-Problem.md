---
layout: post
title: "Deep Reinforcement Learning for Solving the Vehicle Routing Problem"
date: 2018-02-12 18:41:57
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Inference
author: Mohammadreza Nazari, Afshin Oroojlooy, Lawrence V. Snyder, Martin Tak&#xe1;&#x10d;
mathjax: true
---

* content
{:toc}

##### Abstract
We present an end-to-end framework for solving Vehicle Routing Problem (VRP) using deep reinforcement learning. In this approach, we train a single model that finds near-optimal solutions for problem instances sampled from a given distribution, only by observing the reward signals and following feasibility rules. Our model represents a parameterized stochastic policy, and by applying a policy gradient algorithm to optimize its parameters, the trained model produces the solution as a sequence of consecutive actions in real time, without the need to re-train for every new problem instance. Our method is faster in both training and inference than a recent method that solves the Traveling Salesman Problem (TSP), with nearly identical solution quality. On the more general VRP, our approach outperforms classical heuristics on medium-sized instances in both solution quality and computation time (after training). Our proposed framework can be applied to variants of the VRP such as the stochastic VRP, and has the potential to be applied more generally to combinatorial optimization problems.

##### Abstract (translated by Google)
我们提出了一个使用深入强化学习来解决车辆路径问题（VRP）的端到端框架。在这种方法中，我们只通过观察奖励信号和遵循可行性规则来训练一个模型，该模型找到从给定分布抽样的问题实例的近似最优解。我们的模型表示一个参数化的随机策略，并且通过应用策略梯度算法来优化其参数，训练模型将解决方案作为一系列连续动作实时生成，而不需要为每个新问题实例重新训练。与最近解决旅行商问题（TSP）的方法相比，我们的方法在训练和推理上都更快，并且解决方案质量几乎相同。在更一般的VRP上，我们的方法在解决方案质量和计算时间（训练后）方面均优于中型实例的经典启发式算法。我们提出的框架可以应用于VRP的变体，例如随机VRP，并且可以更普遍地应用于组合优化问题。

##### URL
[http://arxiv.org/abs/1802.04240](http://arxiv.org/abs/1802.04240)

##### PDF
[http://arxiv.org/pdf/1802.04240](http://arxiv.org/pdf/1802.04240)

