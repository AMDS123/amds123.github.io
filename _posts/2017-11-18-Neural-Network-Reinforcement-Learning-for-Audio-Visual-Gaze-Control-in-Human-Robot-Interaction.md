---
layout: post
title: "Neural Network Reinforcement Learning for Audio-Visual Gaze Control in Human-Robot Interaction"
date: 2017-11-18 09:19:47
categories: arXiv_CV
tags: arXiv_CV Attention Reinforcement_Learning RNN
author: Stéphane Lathuilière, Benoit Massé, Pablo Mesejo, Radu Horaud
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a novel neural network-based reinforcement learning approach for robot gaze control. Our approach enables a robot to learn and adapt its gaze control strategy for human-robot interaction without the use of external sensors or human supervision. The robot learns to focus its attention on groups of people from its own audio-visual experiences, and independently of the number of people in the environment, their position and physical appearance. In particular, we use recurrent neural networks and Q-learning to find an optimal action-selection policy, and we pretrain on a synthetic environment that simulates sound sources and moving participants to avoid the need of interacting with people for hours. Our experimental evaluation suggests that the proposed method is robust in terms of parameters configuration (i.e. the selection of the parameter values has not a decisive impact on the performance). The best results are obtained when audio and video information are jointly used, and when a late fusion strategy is employed (i.e. when both sources of information are separately processed and then fused). Successful experiments on a real environment with the Nao robot indicate that our framework is a step forward towards the autonomous learning of a perceivable and socially acceptable gaze behavior.

##### Abstract (translated by Google)
本文介绍了一种新的基于神经网络的强化学习机器人视觉控制方法。我们的方法使机器人能够学习和适应人机交互的注视控制策略，而无需使用外部传感器或人工监控。机器人学习把注意力集中在自己的视听体验上，而不依赖于环境中的人数，位置和外表。特别是，我们使用递归神经网络和Q学习来找到一个最佳的动作选择策略，并且我们在一个模拟声源和移动参与者的综合环境中进行预训练，以避免需要与人进行数小时的交互。我们的实验评估表明，所提出的方法在参数配置方面是稳健的（即参数值的选择对性能没有决定性的影响）。当共同使用音频和视频信息时，以及当采用晚期融合策略时（即，当两个信息源分开处理然后融合时），获得最佳结果。使用Nao机器人在真实环境中进行的成功实验表明，我们的框架是向自主学习可察觉和社会上可以接受的注视行为迈出的一步。

##### URL
[https://arxiv.org/abs/1711.06834](https://arxiv.org/abs/1711.06834)

##### PDF
[https://arxiv.org/pdf/1711.06834](https://arxiv.org/pdf/1711.06834)

