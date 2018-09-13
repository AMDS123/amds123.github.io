---
layout: post
title: "VR-Goggles for Robots: Real-to-sim Domain Adaptation for Visual Control"
date: 2018-09-12 02:22:47
categories: arXiv_CV
tags: arXiv_CV Style_Transfer Reinforcement_Learning
author: Jingwei Zhang, Lei Tai, Yufeng Xiong, Peng Yun, Ming Liu, Joschka Boedecker, Wolfram Burgard
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we deal with the reality gap from a novel perspective, targeting transferring Deep Reinforcement Learning (DRL) policies learned in simulated environments to the real-world domain for visual control tasks. Instead of adopting the common solutions to the problem by increasing the visual fidelity of synthetic images output from simulators during the training phase, we seek to tackle the problem by translating the real-world image streams back to the synthetic domain during the deployment phase, to make the robot feel at home. We propose this as a lightweight, flexible, and efficient solution for visual control, as 1) no extra transfer steps are required during the expensive training of DRL agents in simulation; 2) the trained DRL agents will not be constrained to being deployable in only one specific real-world environment; 3) the policy training and the transfer operations are decoupled, and can be conducted in parallel. Besides this, we propose a simple yet effective shift loss to constrain the consistency between subsequent frames, which is important for consistent policy outputs. We validate the shift loss for artistic style transfer for videos and domain adaptation, and validate our visual control approach in both indoor and outdoor robotics experiments. A video of our results is available at: https://goo.gl/P76TTo.

##### Abstract (translated by Google)
在本文中，我们从一个新颖的角度处理现实差距，目标是将在模拟环境中学习的深度强化学习（DRL）策略转移到视觉控制任务的真实领域。我们寻求通过在部署阶段将真实世界的图像流转换回合成域来解决问题，而不是通过在训练阶段提高模拟器输出的合成图像的视觉保真度来采用常见的解决方案。让机器人有宾至如归的感觉。我们认为这是一种轻量，灵活，高效的视觉控制解决方案，因为1）在模拟中对DRL代理进行昂贵的培训时，不需要额外的转移步骤; 2）受过训练的DRL代理不会被限制为只能在一个特定的现实世界环境中部署; 3）政策培训和转移操作是分离的，可以并行进行。除此之外，我们提出了一种简单但有效的移位损失来约束后续帧之间的一致性，这对于一致的策略输出非常重要。我们验证了视频和领域适应的艺术风格转移的转移损失，并在室内和室外机器人实验中验证了我们的视觉控制方法。我们的结果视频可在以下网址获得：https：//goo.gl/P76TTo。

##### URL
[http://arxiv.org/abs/1802.00265](http://arxiv.org/abs/1802.00265)

##### PDF
[http://arxiv.org/pdf/1802.00265](http://arxiv.org/pdf/1802.00265)

