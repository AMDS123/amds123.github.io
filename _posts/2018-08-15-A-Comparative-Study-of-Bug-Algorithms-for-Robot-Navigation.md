---
layout: post
title: "A Comparative Study of Bug Algorithms for Robot Navigation"
date: 2018-08-15 12:15:51
categories: arXiv_RO
tags: arXiv_RO Survey SLAM
author: Kimberly McGuire, Guido de Croon, Karl Tuyls
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a literature survey and a comparative study of Bug Algorithms, with the goal of investigating their potential for robotic navigation. At first sight, these methods seem to provide an efficient navigation paradigm, ideal for implementations on tiny robots with limited resources. Closer inspection, however, shows that many of these Bug Algorithms assume perfect global position estimate of the robot which in GPS-denied environments implies considerable expenses of computation and memory -- relying on accurate Simultaneous Localization And Mapping (SLAM) or Visual Odometry (VO) methods. We compare a selection of Bug Algorithms in a simulated robot and environment where they endure different types noise and failure-cases of their on-board sensors. From the simulation results, we conclude that the implemented Bug Algorithms' performances are sensitive to many types of sensor-noise, which was most noticeable for odometry-drift. This raises the question if Bug Algorithms are suitable for real-world, on-board, robotic navigation as is. Variations that use multiple sensors to keep track of their progress towards the goal, were more adept in completing their task in the presence of sensor-failures. This shows that Bug Algorithms must spread their risk, by relying on the readings of multiple sensors, to be suitable for real-world deployment.

##### Abstract (translated by Google)
本文介绍了Bug算法的文献调查和比较研究，目的是研究它们的机器人导航潜力。乍一看，这些方法似乎提供了一种有效的导航范例，非常适合在资源有限的小型机器人上实现。然而，更仔细的检查表明，许多这些Bug算法假设机器人的完美全球位置估计，在GPS拒绝环境中意味着相当大的计算和记忆费用 - 依靠精确的同时定位和映射（SLAM）或视觉测距（VO） ） 方法。我们比较了模拟机器人和环境中的一系列Bug算法，它们承受着不同类型的噪声和故障情况。从仿真结果中，我们得出结论，实施的Bug算法的性能对许多类型的传感器噪声敏感，这对于odometry-drift来说是最明显的。如果Bug算法适用于现实世界，机载，机器人导航，这就提出了一个问题。使用多个传感器跟踪他们朝向目标的进度的变化在传感器故障的存在下更擅长完成任务。这表明Bug算法必须依靠多个传感器的读数来分散其风险，以适合实际部署。

##### URL
[http://arxiv.org/abs/1808.05050](http://arxiv.org/abs/1808.05050)

##### PDF
[http://arxiv.org/pdf/1808.05050](http://arxiv.org/pdf/1808.05050)

