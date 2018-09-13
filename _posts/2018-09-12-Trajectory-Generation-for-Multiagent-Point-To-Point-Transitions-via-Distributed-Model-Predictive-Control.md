---
layout: post
title: "Trajectory Generation for Multiagent Point-To-Point Transitions via Distributed Model Predictive Control"
date: 2018-09-12 02:37:27
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Carlos E. Luis, Angela P. Schoellig
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a novel algorithm for multiagent offline trajectory generation based on distributed model predictive control (DMPC). By predicting future states and sharing this information with their neighbours, the agents are able to detect and avoid collisions while moving towards their goals. The proposed algorithm computes transition trajectories for dozens of vehicles in a few seconds. It reduces the computation time by more than 85% compared to previous optimization approaches based on sequential convex programming (SCP), with only causing a small impact on the optimality of the plans. We replaced the previous compatibility constraints in DMPC, which limit the motion of the agents in order to avoid collisions, by relaxing the collision constraints and enforcing them only when required. The approach was validated both through extensive simulations for a wide range of randomly generated transitions and with teams of up to 25 quadrotors flying in confined indoor spaces.

##### Abstract (translated by Google)
本文介绍了一种基于分布式模型预测控制（DMPC）的多智能离线轨迹生成算法。通过预测未来状态并与邻居共享此信息，代理能够在朝着目标前进时检测并避免冲突。所提出的算法在几秒钟内计算出数十辆车辆的过渡轨迹。与先前基于顺序凸规划（SCP）的优化方法相比，它将计算时间缩短了85％以上，只对计划的最优性产生了很小的影响。我们通过放宽碰撞约束并仅在需要时强制执行它们来替换DMPC中的先前兼容性约束，DMPC限制代理的运动以避免冲突。该方法通过对各种随机生成的过渡的广泛模拟以及在有限的室内空间中飞行的多达25个四旋翼飞行器的团队进行了验证。

##### URL
[https://arxiv.org/abs/1809.04230](https://arxiv.org/abs/1809.04230)

##### PDF
[https://arxiv.org/pdf/1809.04230](https://arxiv.org/pdf/1809.04230)

