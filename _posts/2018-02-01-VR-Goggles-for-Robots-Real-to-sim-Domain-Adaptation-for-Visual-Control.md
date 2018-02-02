---
layout: post
title: "VR Goggles for Robots: Real-to-sim Domain Adaptation for Visual Control"
date: 2018-02-01 12:42:02
categories: arXiv_CV
tags: arXiv_CV Style_Transfer Reinforcement_Learning
author: Jingwei Zhang, Lei Tai, Yufeng Xiong, Ming Liu, Joschka Boedecker, Wolfram Burgard
mathjax: true
---

* content
{:toc}

##### Abstract
This paper deals with the reality gap from a novel perspective, targeting transferring Deep Reinforcement Learning (DRL) policies learned in simulated environments to the real-world domain for visual control tasks. Instead of adopting the common solutions to the problem by increasing the visual fidelity of synthetic images output from simulators during the training phase, this paper seeks to tackle the problem by translating the real-world image streams back to the synthetic domain during the deployment phase, to make the robot feel at home. We propose this as a lightweight, flexible, and efficient solution for visual control, as 1) no extra transfer steps are required during the expensive training of DRL agents in simulation; 2) the trained DRL agents will not be constrained to being deployable in only one specific real-world environment; 3) the policy training and the transfer operations are decoupled, and can be conducted in parallel. Besides this, we propose a conceptually simple yet very effective shift loss to constrain the consistency between subsequent frames, eliminating the need for optical flow. We validate the shift loss for artistic style transfer for videos and domain adaptation, and validate our visual control approach in real-world robot experiments. A video of our results is available at: https://goo.gl/b1xz1s.

##### Abstract (translated by Google)
本文从新的角度处理现实差距，将模拟环境中学习的深度强化学习（DRL）策略转移到真实世界的视觉控制任务领域。本文通过在训练阶段提高模拟器输出的合成图像的视觉保真度，而不是采用常见的解决方案来解决这个问题，而是在部署阶段通过将真实图像流转换回合成域来解决这个问题，使机器人感到宾至如归。我们提出这是一个轻量级的，灵活的，有效的视觉控制解决方案，因为1）在仿真DRL代理昂贵的培训期间，不需要额外的转移步骤; 2）训练有素的DRL代理不会被限制只能在一个特定的现实世界中部署; 3）政策培训和转移操作是分开的，可以并行进行。除此之外，我们提出了一个概念上简单但非常有效的移位损失来约束后续帧之间的一致性，消除了对光流的需求。我们验证了视频和领域适应的艺术风格转移的转移损失，并验证了我们在真实世界机器人实验中的视觉控制方法。我们的结果视频可在https://goo.gl/b1xz1s获得。

##### URL
[http://arxiv.org/abs/1802.00265](http://arxiv.org/abs/1802.00265)

##### PDF
[http://arxiv.org/pdf/1802.00265](http://arxiv.org/pdf/1802.00265)

