---
layout: post
title: "Online UAV Path Planning for Joint Detection and Tracking of Multiple Radio-tagged Objects"
date: 2018-08-09 00:18:23
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Hoa Van Nguyen, S. Hamid Rezatofighi, Ba-Ngu Vo, Damith C. Ranasinghe
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of online path planning for joint detection and tracking of multiple unknown radio-tagged objects. This is a necessary task for gathering spatio-temporal information using UAVs with on-board sensors in a range of monitoring applications. In this paper, we propose an online path planning algorithm with joint detection and tracking for the problem because signal measurements from these object are inherently noisy. We derive a partially observable Markov decision process with a random finite set track-before-detect (TBD) multi-object filter. We show that, in practice, the likelihood function of raw signals received by the UAV transformed into the time-frequency domain is separable for multiple radio-tagged objects and results in a numerically efficient multi-object TBD filter. We derive a TBD filter with a jump Markov system to accommodate maneuvering objects capable of switching between different dynamic modes. Further, we impose a practical constraint using a void probability formulation to maintain a safe distance between the UAV and objects of interest. Our evaluations demonstrate the capability of our approach handle multiple radio-tagged object behaviors such as birth, death, motion modes and the superiority of the proposed online planning method with the TBD-based filter at tracking and detecting objects compared to the detection-based counterpart, especially under low signal-to-noise ratio environments.

##### Abstract (translated by Google)
我们考虑联合检测和跟踪多个未知无线电标记对象的在线路径规划问题。这是在一系列监控应用中使用带有板载传感器的无人机收集时空信息的必要任务。在本文中，我们提出了一种在线路径规划算法，该算法具有联合检测和跟踪问题，因为来自这些物体的信号测量本质上是有噪声的。我们利用随机有限集跟踪前检测（TBD）多目标过滤器推导出部分可观察马尔可夫决策过程。我们表明，在实践中，由变换到时频域的UAV接收的原始信号的似然函数对于多个无线电标记的对象是可分离的，并且导致数值有效的多对象TBD滤波器。我们推导出具有跳跃马尔可夫系统的TBD滤波器，以适应能够在不同动态模式之间切换的机动对象。此外，我们使用空隙概率公式来实施实际约束，以维持UAV与感兴趣对象之间的安全距离。我们的评估证明了我们的方法能够处理多种无线电标记的对象行为，例如出生，死亡，运动模式以及所提出的在线规划方法与基于TBD的过滤器在跟踪和检测对象方面的优越性，与基于检测的对应物相比较，尤其是在低信噪比环境下。

##### URL
[https://arxiv.org/abs/1808.04445](https://arxiv.org/abs/1808.04445)

##### PDF
[https://arxiv.org/pdf/1808.04445](https://arxiv.org/pdf/1808.04445)

