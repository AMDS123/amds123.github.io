---
layout: post
title: "Sim-to-Real: Learning Agile Locomotion For Quadruped Robots"
date: 2018-04-27 03:42:55
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Jie Tan, Tingnan Zhang, Erwin Coumans, Atil Iscen, Yunfei Bai, Danijar Hafner, Steven Bohez, Vincent Vanhoucke
mathjax: true
---

* content
{:toc}

##### Abstract
Designing agile locomotion for quadruped robots often requires extensive expertise and tedious manual tuning. In this paper, we present a system to automate this process by leveraging deep reinforcement learning techniques. Our system can learn quadruped locomotion from scratch using simple reward signals. In addition, users can provide an open loop reference to guide the learning process when more control over the learned gait is needed. The control policies are learned in a physics simulator and then deployed on real robots. In robotics, policies trained in simulation often do not transfer to the real world. We narrow this reality gap by improving the physics simulator and learning robust policies. We improve the simulation using system identification, developing an accurate actuator model and simulating latency. We learn robust controllers by randomizing the physical environments, adding perturbations and designing a compact observation space. We evaluate our system on two agile locomotion gaits: trotting and galloping. After learning in simulation, a quadruped robot can successfully perform both gaits in the real world.

##### Abstract (translated by Google)
设计四足机器人的敏捷移动通常需要广泛的专业知识和繁琐的手动调整。在本文中，我们提出了一个通过利用深度强化学习技术来自动化此过程的系统。我们的系统可以使用简单的奖励信号从零开始学习四足运动。此外，用户可以在需要更多控制学习步态时提供开环参考来指导学习过程。控制策略在物理模拟器中学习，然后部署在真实的机器人上。在机器人技术中，模拟培训的政策通常不会转移到现实世界。我们通过改进物理模拟器和学习稳健的策略来缩小这种现实差距。我们使用系统识别来改进仿真，开发精确的执行器模型和模拟延迟。我们通过随机化物理环境，添加扰动和设计紧凑的观察空间来学习鲁棒控制器。我们用两种敏捷运动步法评估我们的系统：小跑和奔跑。模拟学习后，四足机器人可以在现实世界中成功执行两种步态。

##### URL
[https://arxiv.org/abs/1804.10332](https://arxiv.org/abs/1804.10332)

##### PDF
[https://arxiv.org/pdf/1804.10332](https://arxiv.org/pdf/1804.10332)

