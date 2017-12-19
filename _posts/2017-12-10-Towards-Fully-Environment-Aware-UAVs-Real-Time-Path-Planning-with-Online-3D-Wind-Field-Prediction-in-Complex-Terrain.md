---
layout: post
title: "Towards Fully Environment-Aware UAVs: Real-Time Path Planning with Online 3D Wind Field Prediction in Complex Terrain"
date: 2017-12-10 23:13:45
categories: arXiv_RO
tags: arXiv_RO Optimization Prediction
author: Philipp Oettershagen, Florian Achermann, Benjamin Müller, Daniel Schneider, Roland Siegwart
mathjax: true
---

* content
{:toc}

##### Abstract
Today, low-altitude fixed-wing Unmanned Aerial Vehicles (UAVs) are largely limited to primitively follow user-defined waypoints. To allow fully-autonomous remote missions in complex environments, real-time environment-aware navigation is required both with respect to terrain and strong wind drafts. This paper presents two relevant initial contributions: First, the literature's first-ever 3D wind field prediction method which can run in real time onboard a UAV is presented. The approach retrieves low-resolution global weather data, and uses potential flow theory to adjust the wind field such that terrain boundaries, mass conservation, and the atmospheric stratification are observed. A comparison with 1D LIDAR data shows an overall wind error reduction of 23% with respect to the zero-wind assumption that is mostly used for UAV path planning today. However, given that the vertical winds are not resolved accurately enough further research is required and identified. Second, a sampling-based path planner that considers the aircraft dynamics in non-uniform wind iteratively via Dubins airplane paths is presented. Performance optimizations, e.g. obstacle-aware sampling and fast 2.5D-map collision checks, render the planner 50% faster than the Open Motion Planning Library (OMPL) implementation. Test cases in Alpine terrain show that the wind-aware planning performs up to 50x less iterations than shortest-path planning and is thus slower in low winds, but that it tends to deliver lower-cost paths in stronger winds. More importantly, in contrast to the shortest-path planner, it always delivers collision-free paths. Overall, our initial research demonstrates the feasibility of 3D wind field prediction from a UAV and the advantages of wind-aware planning. This paves the way for follow-up research on fully-autonomous environment-aware navigation of UAVs in real-life missions and complex terrain.

##### Abstract (translated by Google)
今天，低空固定翼无人机（UAV）很大程度上受限于原始地遵循用户定义的航点。为了在复杂的环境中实现完全自主的远程任务，需要对地形和风力强大的实时环境感知导航。本文提出了两个相关的初步贡献：首先，介绍了可以在无人机上实时运行的文献中第一个三维风场预测方法。该方法检索低分辨率的全球天气数据，并使用势流理论来调整风场，以便观察地形边界，质量守恒和大气层化。与一维激光雷达数据的比较显示，相对于目前主要用于无人机路径规划的零风假设，总风错误减少了23％。然而，鉴于垂直风的解决不够准确，需要进一步的研究和确定。其次，提出了一种基于采样的路径规划器，该路径规划器通过Dubins飞机路径迭代地考虑非均匀风中的飞机动力学。性能优化，例如障碍感知采样和快速2.5D地图冲突检查，使规划人员比开放运动规划库（OMPL）实施快50％。在阿尔卑斯山地区的测试案例表明，风能感知计划比最短路径计划的迭代次数减少了50倍，因此在低风速下运行速度较慢，但​​在较强的风力条件下往往会提供成本较低的路径。更重要的是，与最短路径规划器相反，它总是提供无碰撞路径。总体而言，我们的初步研究表明了无人机三维风场预测的可行性以及风能计划的优势。这为在实际任务和复杂地形上进行无人机完全自主环境感知导航的后续研究铺平了道路。

##### URL
[https://arxiv.org/abs/1712.03608](https://arxiv.org/abs/1712.03608)

##### PDF
[https://arxiv.org/pdf/1712.03608](https://arxiv.org/pdf/1712.03608)

