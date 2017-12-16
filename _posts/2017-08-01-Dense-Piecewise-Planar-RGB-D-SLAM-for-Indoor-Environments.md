---
layout: post
title: "Dense Piecewise Planar RGB-D SLAM for Indoor Environments"
date: 2017-08-01 21:07:14
categories: arXiv_CV
tags: arXiv_CV Optimization SLAM
author: Phi-Hung Le, Jana Kosecka
mathjax: true
---

* content
{:toc}

##### Abstract
The paper exploits weak Manhattan constraints to parse the structure of indoor environments from RGB-D video sequences in an online setting. We extend the previous approach for single view parsing of indoor scenes to video sequences and formulate the problem of recovering the floor plan of the environment as an optimal labeling problem solved using dynamic programming. The temporal continuity is enforced in a recursive setting, where labeling from previous frames is used as a prior term in the objective function. In addition to recovery of piecewise planar weak Manhattan structure of the extended environment, the orthogonality constraints are also exploited by visual odometry and pose graph optimization. This yields reliable estimates in the presence of large motions and absence of distinctive features to track. We evaluate our method on several challenging indoors sequences demonstrating accurate SLAM and dense mapping of low texture environments. On existing TUM benchmark we achieve competitive results with the alternative approaches which fail in our environments.

##### Abstract (translated by Google)
本文利用弱曼哈顿约束条件从在线环境中解析RGB-D视频序列的室内环境结构。我们将先前的室内场景单视点解析方法扩展为视频序列，并将动态规划解决的环境平面图恢复为最优标注问题。时间连续性在递归设置中被执行，其中来自先前帧的标记被用作目标函数中的先验项。除了恢复扩展环境的分段平面曼哈顿弱结构外，还通过视觉测距和姿态图优化来利用正交性约束。这就产生了可靠的估计值，并且没有明显的特征可以跟踪。我们评估我们的方法在几个具有挑战性的室内序列展示精确的SLAM和低纹理环境的密集映射。在现有的TUM基准测试中，我们通过在我们的环境中失败的替代方法实现了竞争结果。

##### URL
[https://arxiv.org/abs/1708.00514](https://arxiv.org/abs/1708.00514)

##### PDF
[https://arxiv.org/pdf/1708.00514](https://arxiv.org/pdf/1708.00514)

