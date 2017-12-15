---
layout: post
title: "Integrating Graph Partitioning and Matching for Trajectory Analysis in Video Surveillance"
date: 2015-02-02 06:52:47
categories: arXiv_CV
tags: arXiv_CV Tracking Inference
author: Liang Lin, Yongyi Lu, Yan Pan, Xiaowu Chen
mathjax: true
---

* content
{:toc}

##### Abstract
In order to track the moving objects in long range against occlusion, interruption, and background clutter, this paper proposes a unified approach for global trajectory analysis. Instead of the traditional frame-by-frame tracking, our method recovers target trajectories based on a short sequence of video frames, e.g. $15$ frames. We initially calculate a foreground map at each frame, as obtained from a state-of-the-art background model. An attribute graph is then extracted from the foreground map, where the graph vertices are image primitives represented by the composite features. With this graph representation, we pose trajectory analysis as a joint task of spatial graph partitioning and temporal graph matching. The task can be formulated by maximizing a posteriori under the Bayesian framework, in which we integrate the spatio-temporal contexts and the appearance models. The probabilistic inference is achieved by a data-driven Markov Chain Monte Carlo (MCMC) algorithm. Given a peroid of observed frames, the algorithm simulates a ergodic and aperiodic Markov Chain, and it visits a sequence of solution states in the joint space of spatial graph partitioning and temporal graph matching. In the experiments, our method is tested on several challenging videos from the public datasets of visual surveillance, and it outperforms the state-of-the-art methods.

##### Abstract (translated by Google)
为了追踪远距离运动物体的遮挡，中断和背景杂波，本文提出了一种统一的全局轨迹分析方法。取代传统的逐帧跟踪，我们的方法基于视频帧的短序列恢复目标轨迹，例如， $ 15 $帧。我们最初计算每帧的前景地图，从最先进的背景模型中获得。然后从前景地图中提取属性图，其中图顶点是由复合要素表示的图像基元。利用这种图形表示，我们将轨迹分析作为空间图分区和时间图匹配的联合任务。这个任务可以通过在贝叶斯框架下最大化后验概率来表示，在这个框架中我们整合了时空上下文和外观模型。概率推理是通过数据驱动的马尔可夫链蒙特卡洛（MCMC）算法实现的。给定一个观测帧的周期，该算法模拟遍历和非周期马尔可夫链，并在空间图分区和时间图匹配的联合空间中访问一系列求解态。在实验中，我们的方法在视觉监控公共数据集的几个具有挑战性的视频上进行了测试，并且胜过了最先进的方法。

##### URL
[https://arxiv.org/abs/1502.00377](https://arxiv.org/abs/1502.00377)

##### PDF
[https://arxiv.org/pdf/1502.00377](https://arxiv.org/pdf/1502.00377)

