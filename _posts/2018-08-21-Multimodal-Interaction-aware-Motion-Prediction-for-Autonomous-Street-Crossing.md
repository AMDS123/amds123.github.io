---
layout: post
title: "Multimodal Interaction-aware Motion Prediction for Autonomous Street Crossing"
date: 2018-08-21 13:18:27
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Recognition
author: Noha Radwan, Abhinav Valada, Wolfram Burgard
mathjax: true
---

* content
{:toc}

##### Abstract
For mobile robots sharing the space with humans, acting in accordance with the behavioral norms is a critical prerequisite for their deployment and ease of adoption. One particular challenge for robots navigating in urban environments is the ability to handle street intersections. While the most commonly employed approach to safely cross the road primarily relies on predicting the state of the traffic light, failure to accurately recognize the signal can lead to catastrophic outcomes. Furthermore, the problem becomes even more challenging at unsignalized intersections. In order to address these challenges, we propose a multimodal convolutional neural network framework to predict the safety of a street intersection for crossing. Our architecture consists of two subnetworks; an interaction aware trajectory estimation stream, IA-TCNN that predicts the future states of all observed traffic participants in the scene, and a traffic light recognition stream, AtteNet. IA-TCNN utilizes dilated causal convolutions to model the behavior of all the observable dynamic agents in the scene without explicitly assigning priorities to the interactions among them. While AtteNet utilizes Squeeze-Excitation blocks to learn a content-aware mechanism for selecting the relevant features from the data, thereby improving the noise robustness. Learned representations from the traffic light recognition stream are fused with the estimated trajectories from the motion prediction stream to learn the crossing decision. Extensive experimental evaluations on public benchmark datasets and our proposed Freiburg Street Crossing dataset demonstrate that our network achieves state-of-the-art performance for each of the subtasks, as well as for the crossing safety prediction.

##### Abstract (translated by Google)
对于与人类共享空间的移动机器人，根据行为规范行事是部署和易于采用的关键先决条件。机器人在城市环境中导航的一个特殊挑战是处理街道交叉口的能力。虽然最常用的安全过马路方法主要依赖于预测交通信号灯的状态，但未准确识别信号可能会导致灾难性后果。此外，在无信号交叉口处，问题变得更具挑战性。为了应对这些挑战，我们提出了一种多模态卷积神经网络框架来预测交叉口的街道交叉口的安全性。我们的架构由两个子网组成;交互感知轨迹估计流，IA-TCNN，其预测场景中所有观察到的交通参与者的未来状态，以及交通灯识别流，AtteNet。 IA-TCNN利用扩张的因果卷积来模拟场景中所有可观察的动态代理的行为，而不明确地为它们之间的交互分配优先级。 AtteNet利用Squeeze-Excitation模块学习内容感知机制，从数据中选择相关特征，从而提高噪声鲁棒性。来自交通灯识别流的学习表示与来自运动预测流的估计轨迹融合以学习交叉决策。对公共基准数据集和我们提出的Freiburg Street Crossing数据集的广泛实验评估表明，我们的网络为每个子任务以及交叉安全预测实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1808.06887](http://arxiv.org/abs/1808.06887)

##### PDF
[http://arxiv.org/pdf/1808.06887](http://arxiv.org/pdf/1808.06887)

