---
layout: post
title: "Playing Doom with SLAM-Augmented Deep Reinforcement Learning"
date: 2016-12-01 18:54:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection Reinforcement_Learning Detection SLAM
author: Shehroze Bhatti, Alban Desmaison, Ondrej Miksik, Nantas Nardelli, N. Siddharth, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
A number of recent approaches to policy learning in 2D game domains have been successful going directly from raw input images to actions. However when employed in complex 3D environments, they typically suffer from challenges related to partial observability, combinatorial exploration spaces, path planning, and a scarcity of rewarding scenarios. Inspired from prior work in human cognition that indicates how humans employ a variety of semantic concepts and abstractions (object categories, localisation, etc.) to reason about the world, we build an agent-model that incorporates such abstractions into its policy-learning framework. We augment the raw image input to a Deep Q-Learning Network (DQN), by adding details of objects and structural elements encountered, along with the agent's localisation. The different components are automatically extracted and composed into a topological representation using on-the-fly object detection and 3D-scene reconstruction.We evaluate the efficacy of our approach in Doom, a 3D first-person combat game that exhibits a number of challenges discussed, and show that our augmented framework consistently learns better, more effective policies.

##### Abstract (translated by Google)
2D游戏领域最近的一些政策学习方法已经成功地从原始输入图像直接转化为行动。然而，当在复杂的三维环境中使用时，他们通常会遇到与部分可观察性，组合探索空间，路径规划以及缺乏奖励情景有关的挑战。受到以往人类认知工作的启发，这些工作指出人类如何运用各种语义概念和抽象（对象类别，本地化等）来推理世界，我们建立了一个代理模型，将这种抽象纳入其政策学习框架。通过添加对象和结构元素的细节以及代理的本地化，我们将原始图像输入扩展到深度学习网络（DQN）。通过运动中的物体检测和三维场景重建，将不同的组件自动提取并组合成拓扑表示。我们评估了我们的方法在Doom中的效果，这是一款3D第一人称战斗游戏，展现了一些挑战并表明我们的增强框架不断学习更好，更有效的政策。

##### URL
[https://arxiv.org/abs/1612.00380](https://arxiv.org/abs/1612.00380)

##### PDF
[https://arxiv.org/pdf/1612.00380](https://arxiv.org/pdf/1612.00380)

