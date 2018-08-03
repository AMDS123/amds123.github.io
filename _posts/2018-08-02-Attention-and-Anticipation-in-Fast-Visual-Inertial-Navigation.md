---
layout: post
title: "Attention and Anticipation in Fast Visual-Inertial Navigation"
date: 2018-08-02 04:02:54
categories: arXiv_RO
tags: arXiv_RO Knowledge Attention Drone
author: Luca Carlone, Sertac Karaman
mathjax: true
---

* content
{:toc}

##### Abstract
We study a Visual-Inertial Navigation (VIN) problem in which a robot needs to estimate its state using an on-board camera and an inertial sensor, without any prior knowledge of the external environment. We consider the case in which the robot can allocate limited resources to VIN, due to tight computational constraints. Therefore, we answer the following question: under limited resources, what are the most relevant visual cues to maximize the performance of visual-inertial navigation? Our approach has four key ingredients. First, it is task-driven, in that the selection of the visual cues is guided by a metric quantifying the VIN performance. Second, it exploits the notion of anticipation, since it uses a simplified model for forward-simulation of robot dynamics, predicting the utility of a set of visual cues over a future time horizon. Third, it is efficient and easy to implement, since it leads to a greedy algorithm for the selection of the most relevant visual cues. Fourth, it provides formal performance guarantees: we leverage submodularity to prove that the greedy selection cannot be far from the optimal (combinatorial) selection. Simulations and real experiments on agile drones show that our approach ensures state-of-the-art VIN performance while maintaining a lean processing time. In the easy scenarios, our approach outperforms appearance-based feature selection in terms of localization errors. In the most challenging scenarios, it enables accurate visual-inertial navigation while appearance-based feature selection fails to track robot's motion during aggressive maneuvers.

##### Abstract (translated by Google)
我们研究了一种视觉 - 惯性导航（VIN）问题，其中机器人需要使用机载摄像头和惯性传感器来估计其状态，而不需要任何先验的外部环境知识。我们考虑机器人可以通过严格的计算约束将有限的资源分配给VIN的情况。因此，我们回答以下问题：在有限的资源下，最大化视觉惯性导航性能的最相关的视觉线索是什么？我们的方法有四个关键要素。首先，它是任务驱动的，因为视觉提示的选择由量化VIN性能的度量指导。其次，它利用了预期的概念，因为它使用简化模型进行机器人动力学的前向模拟，预测未来时间范围内一组视觉线索的效用。第三，它是有效且易于实现的，因为它导致用于选择最相关的视觉线索的贪婪算法。第四，它提供正式的性能保证：我们利用子模块来证明贪婪选择不能远离最优（组合）选择。敏捷无人机的模拟和真实实验表明，我们的方法可确保最先进的VIN性能，同时保持精简的处理时间。在简单的场景中，我们的方法在本地化错误方面优于基于外观的特征选择。在最具挑战性的情况下，它可以实现精确的视觉惯性导航，而基于外观的特征选择无法跟踪机器人在激进操作期间的运动。

##### URL
[http://arxiv.org/abs/1610.03344](http://arxiv.org/abs/1610.03344)

##### PDF
[http://arxiv.org/pdf/1610.03344](http://arxiv.org/pdf/1610.03344)

