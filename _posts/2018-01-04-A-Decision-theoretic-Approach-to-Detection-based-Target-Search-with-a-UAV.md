---
layout: post
title: "A Decision-theoretic Approach to Detection-based Target Search with a UAV"
date: 2018-01-04 02:29:19
categories: arXiv_AI
tags: arXiv_AI Drone Detection
author: Aayush Gupta, Daniel Bessonov, Patrick Li
mathjax: true
---

* content
{:toc}

##### Abstract
Search and rescue missions and surveillance require finding targets in a large area. These tasks often use unmanned aerial vehicles (UAVs) with cameras to detect and move towards a target. However, common UAV approaches make two simplifying assumptions. First, they assume that observations made from different heights are deterministically correct. In practice, observations are noisy, with the noise increasing as the height used for observations increases. Second, they assume that a motion command executes correctly, which may not happen due to wind and other environmental factors. To address these, we propose a sequential algorithm that determines actions in real time based on observations, using partially observable Markov decision processes (POMDPs). Our formulation handles both observations and motion uncertainty and errors. We run offline simulations and learn a policy. This policy is run on a UAV to find the target efficiently. We employ a novel compact formulation to represent the coordinates of the drone relative to the target coordinates. Our POMDP policy finds the target up to 3.4 times faster when compared to a heuristic policy.

##### Abstract (translated by Google)
搜救任务和监视要求在大面积上找到目标。这些任务经常使用带相机的无人驾驶飞行器（UAV）来检测并向目标移动。然而，普通的无人机方法做了两个简化的假设。首先，他们假设从不同高度进行的观测是确定性的。在实践中，观测是嘈杂的，随着用于观测的高度增加，噪声也在增加。其次，他们假定一个动作命令执行正确，这可能不会由于风和其他环境因素而发生。为了解决这些问题，我们提出了一种顺序算法，它使用部分可观察的马尔可夫决策过程（POMDPs）根据观察结果实时确定行动。我们的公式处理观测和运动的不确定性和错误。我们运行离线模拟并学习一项政策。这项政策是在无人机上运行，​​以有效地找到目标。我们采用新颖的紧凑公式来表示无人机相对于目标坐标的坐标。与启发式政策相比，我们的POMDP政策发现目标速度提高了3.4倍。

##### URL
[http://arxiv.org/abs/1801.01228](http://arxiv.org/abs/1801.01228)

##### PDF
[http://arxiv.org/pdf/1801.01228](http://arxiv.org/pdf/1801.01228)

