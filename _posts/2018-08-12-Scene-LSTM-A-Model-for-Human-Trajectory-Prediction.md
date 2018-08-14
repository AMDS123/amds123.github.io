---
layout: post
title: "Scene-LSTM: A Model for Human Trajectory Prediction"
date: 2018-08-12 23:19:36
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Huynh Manh, Gita Alaghband
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a human movement trajectory prediction system that incorporates the scene information (Scene-LSTM) as well as human movement trajectories (Pedestrian movement LSTM) in the prediction process within static crowded scenes. We superimpose a two-level grid structure (scene is divided into grid cells each modeled by a scene-LSTM, which are further divided into smaller sub-grids for finer spatial granularity) and explore common human trajectories occurring in the grid cell (e.g., making a right or left turn onto sidewalks coming out of an alley; or standing still at bus/train stops). Two coupled LSTM networks, Pedestrian movement LSTMs (one per target) and the corresponding Scene-LSTMs (one per grid-cell) are trained simultaneously to predict the next movements. We show that such common path information greatly influences prediction of future movement. We further design a scene data filter that holds important non-linear movement information. The scene data filter allows us to select the relevant parts of the information from the grid cell's memory relative to a target's state. We evaluate and compare two versions of our method with the Linear and several existing LSTM-based methods on five crowded video sequences from the UCY [1] and ETH [2] datasets. The results show that our method reduces the location displacement errors compared to related methods and specifically about 80% reduction compared to social interaction methods.

##### Abstract (translated by Google)
我们开发了一种人体运动轨迹预测系统，该系统在静态拥挤场景中的预测过程中结合了场景信息（Scene-LSTM）以及人体运动轨迹（行人运动LSTM）。我们叠加一个两级网格结构（场景被划分为网格单元，每个网格单元由场景LSTM建模，进一步划分为更小的子网格以获得更精细的空间粒度）并探索网格单元中出现的常见人类轨迹（例如，右转或左转转到走出小巷的人行道上;或站在公共汽车/火车站停下来）。两个耦合的LSTM网络，行人运动LSTM（每个目标一个）和相应的场景LSTM（每个网格单元一个）被同时训练以预测下一个运动。我们表明这种共同的路径信息极大地影响了对未来运动的预测。我们进一步设计了一个场景数据滤波器，它保存了重要的非线性运动信息场景数据过滤器允许我们从网格单元的内存中选择相对于目标状态的信息的相关部分。我们评估和比较我们的方法的两个版本与线性和几个现有的基于LSTM的方法对来自UCY [1]和ETH [2]数据集的五个拥挤视频序列。结果表明，与相关方法相比，我们的方法减少了位置偏移误差，特别是与社交互动方法相比减少了约80％。

##### URL
[http://arxiv.org/abs/1808.04018](http://arxiv.org/abs/1808.04018)

##### PDF
[http://arxiv.org/pdf/1808.04018](http://arxiv.org/pdf/1808.04018)

