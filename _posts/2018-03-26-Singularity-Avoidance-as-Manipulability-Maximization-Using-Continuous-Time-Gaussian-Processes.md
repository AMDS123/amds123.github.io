---
layout: post
title: "Singularity Avoidance as Manipulability Maximization Using Continuous Time Gaussian Processes"
date: 2018-03-26 10:04:54
categories: arXiv_RO
tags: arXiv_RO Sparse Inference Quantitative
author: Filip Marić, Oliver Limoyo, Luka Petrović, Ivan Petrović, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
A significant challenge in motion planning is to avoid being in or near \emph{singular configurations}, that is, configurations in joint space that result in the loss of the ability to move in certain directions in task space. A robotic system's manipulability is reduced even in regions that are in close proximity to (i.e., neighbouring) a singularity. In this work we examine singularity avoidance in a motion planning context, that is, finding a trajectory which minimizes proximity to singular regions, subject to constraints. Representing the trajectory as a sample taken from a continuous time Gaussian process, we define a likelihood associated with singularity avoidance. We leverage recent work on motion planning using exactly sparse Gaussian processes and a factor graph representation to maximize the singularity avoidance likelihood using a \textit{maximum a posteriori} (MAP) estimator. Viewing the MAP problem as inference on a factor graph, we use gradient information from interpolated states to maximize the trajectory's overall manipulability. Both qualitative and quantitative analysis of experimental data show increases in manipulability which results in smooth trajectories with visibly more dexterous configurations.

##### Abstract (translated by Google)
运动规划中的一个重要挑战是避免出现在\ emph {奇异配置}中或附近，也就是说，联合空间中的配置会导致在任务空间中某些方向移动的能力丧失。即使在靠近（即，邻近）奇点的区域中，机器人系统的可操纵性也被降低。在这项工作中，我们研究了运动规划背景下的奇异规避问题，也就是寻找一个轨迹，该轨迹可以最小化奇异区域的接近程度，并受到约束。将轨迹表示为从连续时间高斯过程取得的样本，我们定义与奇异规避相关的可能性。我们利用最近的运动规划工作，使用完全稀疏的高斯过程和因子图表示法，以最大化使用\ textit {最大后验概率（MAP）估计量的奇异性避免可能性。将MAP问题视为一个因子图上的推理，我们使用来自插值状态的梯度信息来最大化轨迹的整体可操作性。对实验数据的定性和定量分析都显示可操作性的增加，这导致光滑的轨迹具有明显更灵活的配置。

##### URL
[https://arxiv.org/abs/1803.09493](https://arxiv.org/abs/1803.09493)

##### PDF
[https://arxiv.org/pdf/1803.09493](https://arxiv.org/pdf/1803.09493)

