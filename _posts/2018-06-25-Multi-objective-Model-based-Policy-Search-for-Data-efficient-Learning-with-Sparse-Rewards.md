---
layout: post
title: "Multi-objective Model-based Policy Search for Data-efficient Learning with Sparse Rewards"
date: 2018-06-25 09:46:47
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning Optimization
author: Rituraj Kaushik, Konstantinos Chatzilygeroudis, Jean-Baptiste Mouret
mathjax: true
---

* content
{:toc}

##### Abstract
The most data-efficient algorithms for reinforcement learning in robotics are model-based policy search algorithms, which alternate between learning a dynamical model of the robot and optimizing a policy to maximize the expected return given the model and its uncertainties. However, the current algorithms lack an effective exploration strategy to deal with sparse or misleading reward scenarios: if they do not experience any state with a positive reward during the initial random exploration, it is very unlikely to solve the problem. Here, we propose a novel model-based policy search algorithm, Multi-DEX, that leverages a learned dynamical model to efficiently explore the task space and solve tasks with sparse rewards in a few episodes. To achieve this, we frame the policy search problem as a multi-objective, model-based policy optimization problem with three objectives: (1) generate maximally novel state trajectories, (2) maximize the expected return and (3) keep the system in state-space regions for which the model is as accurate as possible. We then optimize these objectives using a Pareto-based multi-objective optimization algorithm. The experiments show that Multi-DEX is able to solve sparse reward scenarios (with a simulated robotic arm) in much lower interaction time than VIME, TRPO, GEP-PG, CMA-ES and Black-DROPS.

##### Abstract (translated by Google)
用于机器人强化学习的最具数据效率的算法是基于模型的策略搜索算法，该算法在学习机器人的动力学模型和优化策略之间交替，从而在给定模型及其不确定性的情况下最大化策略。然而，目前的算法缺乏有效的探索策略来处理稀疏或误导性的奖励情景：如果他们在最初的随机探索期间没有经历任何具有积极回报的状态，则很难解决问题。在这里，我们提出了一种基于模型的新型策略搜索算法Multi-DEX，它利用学习的动态模型有效地探索任务空间，并在少数情节中用稀疏奖励来解决任务。为了实现这一目标，我们将策略搜索问题定义为一个多目标，基于模型的策略优化问题，它有三个目标：（1）产生最大限度的新颖状态轨迹，（2）最大化期望收益和（3）使系统保持在状态空间区域，其模型尽可能准确。然后，我们使用基于Pareto的多目标优化算法优化这些目标。实验表明，Multi-DEX能够以比VIME，TRPO，GEP-PG，CMA-ES和Black-DROPS更低的交互时间解决稀疏奖励场景（使用模拟机器人手臂）。

##### URL
[http://arxiv.org/abs/1806.09351](http://arxiv.org/abs/1806.09351)

##### PDF
[http://arxiv.org/pdf/1806.09351](http://arxiv.org/pdf/1806.09351)

