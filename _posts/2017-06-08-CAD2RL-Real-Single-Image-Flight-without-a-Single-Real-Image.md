---
layout: post
title: "CAD2RL: Real Single-Image Flight without a Single Real Image"
date: 2017-06-08 07:21:39
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning CNN Prediction
author: Fereshteh Sadeghi, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning has emerged as a promising and powerful technique for automatically acquiring control policies that can process raw sensory inputs, such as images, and perform complex behaviors. However, extending deep RL to real-world robotic tasks has proven challenging, particularly in safety-critical domains such as autonomous flight, where a trial-and-error learning process is often impractical. In this paper, we explore the following question: can we train vision-based navigation policies entirely in simulation, and then transfer them into the real world to achieve real-world flight without a single real training image? We propose a learning method that we call CAD$^2$RL, which can be used to perform collision-free indoor flight in the real world while being trained entirely on 3D CAD models. Our method uses single RGB images from a monocular camera, without needing to explicitly reconstruct the 3D geometry of the environment or perform explicit motion planning. Our learned collision avoidance policy is represented by a deep convolutional neural network that directly processes raw monocular images and outputs velocity commands. This policy is trained entirely on simulated images, with a Monte Carlo policy evaluation algorithm that directly optimizes the network's ability to produce collision-free flight. By highly randomizing the rendering settings for our simulated training set, we show that we can train a policy that generalizes to the real world, without requiring the simulator to be particularly realistic or high-fidelity. We evaluate our method by flying a real quadrotor through indoor environments, and further evaluate the design choices in our simulator through a series of ablation studies on depth prediction. For supplementary video see: this https URL

##### Abstract (translated by Google)
深度强化学习已经成为一种有前途的强大技术，用于自动获取可以处理原始感官输入（例如图像）并执行复杂行为的控制策略。然而，将深度RL延伸到现实世界的机器人任务已经被证明是具有挑战性的，特别是在诸如自主飞行这样的安全关键领域，其中尝试 - 错误学习过程通常是不切实际的。在本文中，我们探讨以下问题：我们能否完全在模拟中训练基于视觉的导航策略，然后将它们转移到真实世界中以实现真实世界的飞行而不需要一个真实的训练图像？我们提出了一种学习方法，我们称之为CAD $ ^ 2 $ RL，可以用来在真实世界中进行无碰撞的室内飞行，同时完全在三维CAD模型上进行训练。我们的方法使用来自单目相机的单个RGB图像，而不需要显式地重构环境的3D几何体或执行明确的运动规划。我们学习的避碰策略是由一个深层卷积神经网络来表示的，它直接处理原始单目图像并输出速度命令。该策略完全是在模拟图像上进行训练的，蒙特卡洛策略评估算法直接优化网络产生无碰撞飞行的能力。通过高度随机化我们的模拟训练集的渲染设置，我们显示我们可以训练一个推广到现实世界的策略，而不要求模拟器特别逼真或高保真。我们通过在室内环境中飞行真正的四旋翼飞行器来评估我们的方法，并通过一系列关于深度预测的消融研究来进一步评估模拟器中的设计选择。有关补充视频，请参阅：https网址

##### URL
[https://arxiv.org/abs/1611.04201](https://arxiv.org/abs/1611.04201)

##### PDF
[https://arxiv.org/pdf/1611.04201](https://arxiv.org/pdf/1611.04201)

