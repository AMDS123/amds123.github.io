---
layout: post
title: "Muscle Excitation Estimation in Biomechanical Simulation Using NAF Reinforcement Learning"
date: 2018-09-17 10:38:20
categories: arXiv_RO
tags: arXiv_RO Tracking Reinforcement_Learning
author: Amir H. Abdi, Pramit Saha, Praneeth Srungarapu, Sidney Fels
mathjax: true
---

* content
{:toc}

##### Abstract
Motor control is a set of time-varying muscle excitations which generate desired motions for a biomechanical system. Muscle excitations cannot be directly measured from live subjects. An alternative approach is to estimate muscle activations using inverse motion-driven simulation. In this article, we propose a deep reinforcement learning method to estimate the muscle excitations in simulated biomechanical systems. Here, we introduce a custom-made reward function which incentivizes faster point-to-point tracking of target motion. Moreover, we deploy two new techniques, namely, episode-based hard update and dual buffer experience replay, to avoid feedback training loops. The proposed method is tested in four simulated 2D and 3D environments with 6 to 24 axial muscles. The results show that the models were able to learn muscle excitations for given motions after nearly 100,000 simulated steps. Moreover, the root mean square error in point-to-point reaching of the target across experiments was less than 1% of the length of the domain of motion. Our reinforcement learning method is far from the conventional dynamic approaches as the muscle control is derived functionally by a set of distributed neurons. This can open paths for neural activity interpretation of this phenomenon.

##### Abstract (translated by Google)
电机控制是一组随时间变化的肌肉激励，它为生物力学系统产生所需的运动。肌肉激动不能直接从活体受试者测量。另一种方法是使用反向运动模拟来估计肌肉激活。在本文中，我们提出了一种深度强化学习方法来估计模拟生物力学系统中的肌肉激发。在这里，我们介绍了一个定制的奖励功能，它可以激励更快的点对点跟踪目标运动。此外，我们部署了两种新技术，即基于剧集的硬更新和双缓冲体验重放，以避免反馈训练循环。所提出的方法在具有6至24个轴向肌肉的四个模拟的2D和3D环境中进行测试。结果表明，模型能够在近100,000次模拟步骤后学习给定运动的肌肉激发。此外，跨越实验的目标的点对点到达的均方根误差小于运动域长度的1％。我们的强化学习方法远非传统的动态方法，因为肌肉控制是由一组分布式神经元在功能上导出的。这可以为这种现象的神经活动解释打开路径。

##### URL
[http://arxiv.org/abs/1809.06121](http://arxiv.org/abs/1809.06121)

##### PDF
[http://arxiv.org/pdf/1809.06121](http://arxiv.org/pdf/1809.06121)

