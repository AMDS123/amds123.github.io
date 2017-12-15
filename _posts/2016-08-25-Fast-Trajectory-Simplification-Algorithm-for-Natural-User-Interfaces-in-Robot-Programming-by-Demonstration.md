---
layout: post
title: "Fast Trajectory Simplification Algorithm for Natural User Interfaces in Robot Programming by Demonstration"
date: 2016-08-25 23:33:23
categories: arXiv_CV
tags: arXiv_CV Face Tracking
author: Daniel L. Marino, Milos Manic
mathjax: true
---

* content
{:toc}

##### Abstract
Trajectory simplification is a problem encountered in areas like Robot programming by demonstration, CAD/CAM, computer vision, and in GPS-based applications like traffic analysis. This problem entails reduction of the points in a given trajectory while keeping the relevant points which preserve important information. The benefits include storage reduction, computational expense, while making data more manageable. Common techniques formulate a minimization problem to be solved, where the solution is found iteratively under some error metric, which causes the algorithms to work in super-linear time. We present an algorithm called FastSTray, which selects the relevant points in the trajectory in linear time by following an open loop heuristic approach. While most current trajectory simplification algorithms are tailored for GPS trajectories, our approach focuses on smooth trajectories for robot programming by demonstration recorded using motion capture systems.Two variations of the algorithm are presented: 1. aims to preserve shape and temporal information; 2. preserves only shape information. Using the points in the simplified trajectory we use cubic splines to interpolate between these points and recreate the original trajectory. The presented algorithm was tested on trajectories recorded from a hand-tracking system. It was able to eliminate about 90% of the points in the original trajectories while maintaining errors between 0.78-2cm which corresponds to 1%-2.4% relative error with respect to the bounding box of the trajectories.

##### Abstract (translated by Google)
轨迹简化是诸如机器人编程演示，CAD / CAM，计算机视觉以及基于GPS的应用（诸如流量分析）中遇到的问题。这个问题需要在给定的轨迹上减少点数，同时保留保存重要信息的相关点。其优点包括减少存储量，计算成本，同时使数据更易于管理。常用的技术是制定一个最小化问题来解决，其中的解决方案是在一定的误差度量下迭代求得的，这使得算法在超线性时间工作。我们提出一种称为FastSTray的算法，它按照开环启发式方法在线性时间内选择轨迹中的相关点。虽然大多数当前的轨迹简化算法是为GPS轨迹量身定制的，但是我们的方法侧重于通过使用运动捕捉系统记录的演示的机器人编程的平滑轨迹。提出了算法的两种变型：1.旨在保存形状和时间信息; 2.只保留形状信息。使用简化轨迹中的点，我们使用三次样条插值在这些点之间并重新创建原始轨迹。所提出的算法在从手动跟踪系统记录的轨迹上进行测试。它能够消除原始轨迹中约90％的点，同时保持0.78-2cm之间的误差，相对于轨迹的边界框相对于1％-2.4％的相对误差。

##### URL
[https://arxiv.org/abs/1608.07338](https://arxiv.org/abs/1608.07338)

##### PDF
[https://arxiv.org/pdf/1608.07338](https://arxiv.org/pdf/1608.07338)

