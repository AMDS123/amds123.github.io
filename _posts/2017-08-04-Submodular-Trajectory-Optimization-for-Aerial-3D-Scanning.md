---
layout: post
title: "Submodular Trajectory Optimization for Aerial 3D Scanning"
date: 2017-08-04 05:22:24
categories: arXiv_CV
tags: arXiv_CV Drone Optimization Quantitative
author: Mike Roberts, Debadeepta Dey, Anh Truong, Sudipta Sinha, Shital Shah, Ashish Kapoor, Pat Hanrahan, Neel Joshi
mathjax: true
---

* content
{:toc}

##### Abstract
Drones equipped with cameras are emerging as a powerful tool for large-scale aerial 3D scanning, but existing automatic flight planners do not exploit all available information about the scene, and can therefore produce inaccurate and incomplete 3D models. We present an automatic method to generate drone trajectories, such that the imagery acquired during the flight will later produce a high-fidelity 3D model. Our method uses a coarse estimate of the scene geometry to plan camera trajectories that: (1) cover the scene as thoroughly as possible; (2) encourage observations of scene geometry from a diverse set of viewing angles; (3) avoid obstacles; and (4) respect a user-specified flight time budget. Our method relies on a mathematical model of scene coverage that exhibits an intuitive diminishing returns property known as submodularity. We leverage this property extensively to design a trajectory planning algorithm that reasons globally about the non-additive coverage reward obtained across a trajectory, jointly with the cost of traveling between views. We evaluate our method by using it to scan three large outdoor scenes, and we perform a quantitative evaluation using a photorealistic video game simulator.

##### Abstract (translated by Google)
配备摄像头的无人驾驶飞机正成为大规模航拍3D扫描的强大工具，但现有的自动飞行规划人员并没有利用有关现场的所有可用信息，因此可能产生不准确和不完整的3D模型。我们提出了一种自动生成无人机轨迹的方法，以便在飞行过程中获取的图像将在稍后生成高保真3D模型。我们的方法使用场景几何的粗略估计来规划相机轨迹：（1）尽可能彻底地覆盖场景; （2）鼓励从不同视角观察场景几何; （3）避开障碍; （4）尊重用户指定的飞行时间预算。我们的方法依赖于一个场景覆盖的数学模型，展现了一种直观的递归性质，称为子模数。我们广泛利用这个属性来设计一个轨迹规划算法，该算法在全球范围内导致在轨迹上获得的非附加覆盖奖励以及在视图之间旅行的成本。我们通过使用它来扫描三个大型户外场景来评估我们的方法，并且我们使用逼真的视频游戏模拟器来执行定量评估。

##### URL
[https://arxiv.org/abs/1705.00703](https://arxiv.org/abs/1705.00703)

##### PDF
[https://arxiv.org/pdf/1705.00703](https://arxiv.org/pdf/1705.00703)

