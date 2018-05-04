---
layout: post
title: "Generating Interpretable Fuzzy Controllers using Particle Swarm Optimization and Genetic Programming"
date: 2018-04-29 16:18:12
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Daniel Hein, Steffen Udluft, Thomas A. Runkler
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomously training interpretable control strategies, called policies, using pre-existing plant trajectory data is of great interest in industrial applications. Fuzzy controllers have been used in industry for decades as interpretable and efficient system controllers. In this study, we introduce a fuzzy genetic programming (GP) approach called fuzzy GP reinforcement learning (FGPRL) that can select the relevant state features, determine the size of the required fuzzy rule set, and automatically adjust all the controller parameters simultaneously. Each GP individual's fitness is computed using model-based batch reinforcement learning (RL), which first trains a model using available system samples and subsequently performs Monte Carlo rollouts to predict each policy candidate's performance. We compare FGPRL to an extended version of a related method called fuzzy particle swarm reinforcement learning (FPSRL), which uses swarm intelligence to tune the fuzzy policy parameters. Experiments using an industrial benchmark show that FGPRL is able to autonomously learn interpretable fuzzy policies with high control performance.

##### Abstract (translated by Google)
使用预先存在的工厂轨迹数据自主培训可解释的控制策略（称为策略）对工业应用非常有意义。数十年来，模糊控制器作为可解释和高效的系统控制器已经在工业中使用。在本研究中，我们引入了模糊GP遗传编程（GP）方法，称为模糊GP强化学习（FGPRL），可以选择相关状态特征，确定所需模糊规则集的大小，并自动调整所有控制器参数。使用基于模型的批量强化学习（RL）计算每个GP个体的适应度，RL首先使用可用的系统样本训练模型，然后执行蒙特卡洛展开以预测每个候选策略的表现。我们将FGPRL与一种称为模糊粒子群强化学习（FPSRL）的相关方法的扩展版本进行比较，该算法使用群智能来调整模糊策略参数。使用行业基准的实验表明，FGPRL能够自主学习具有高控制性能的可解释模糊策略。

##### URL
[https://arxiv.org/abs/1804.10960](https://arxiv.org/abs/1804.10960)

##### PDF
[https://arxiv.org/pdf/1804.10960](https://arxiv.org/pdf/1804.10960)

