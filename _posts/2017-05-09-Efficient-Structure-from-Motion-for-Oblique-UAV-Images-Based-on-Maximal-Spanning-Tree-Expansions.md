---
layout: post
title: "Efficient Structure from Motion for Oblique UAV Images Based on Maximal Spanning Tree Expansions"
date: 2017-05-09 07:22:23
categories: arXiv_CV
tags: arXiv_CV Relation
author: San Jiang, Wanshou Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
The primary contribution of this paper is an efficient Structure from Motion (SfM) solution for oblique unmanned aerial vehicle (UAV) images. First, an algorithm, considering spatial relationship constrains between image footprints, is designed for match pair selection with assistant of UAV flight control data and oblique camera mounting angles. Second, a topological connection network (TCN), represented by an undirected weighted graph, is constructed from initial match pairs, which encodes overlap area and intersection angle into edge weights. Then, an algorithm, termed MST-Expansion, is proposed to extract the match graph from the TCN where the TCN is firstly simplified by a maximum spanning tree (MST). By further analysis of local structure in the MST, expansion operations are performed on the nodes of the MST for match graph enhancement, which is achieved by introducing critical connections in two expansion directions. Finally, guided by the match graph, an efficient SfM solution is proposed, and its validation is verified through comprehensive analysis and comparison using three UAV datasets captured with different oblique multi-camera systems. Experiment results demonstrate that the efficiency of image matching is improved with a speedup ratio ranging from 19 to 35, and competitive orientation accuracy is achieved from both relative bundle adjustment (BA) without GCPs (Ground Control Points) and absolute BA with GCPs. At the same time, images in the three datasets are successfully oriented. For orientation of oblique UAV images, the proposed method can be a more efficient solution.

##### Abstract (translated by Google)
本文的主要贡献是针对倾斜无人机（UAV）图像的高效结构运动（SfM）解决方案。首先，针对无人机飞行控制数据辅助和倾斜摄像机安装角度，设计了考虑图像足迹间空间关系约束的算法，其次，由无向加权图表示的拓扑连接网络（TCN）由初始匹配对构成，其将重叠区域和交叉角度编码为边缘权重。然后，提出一种MST-Expansion算法从TCN中提取匹配图，TCN首先被最大生成树（MST）简化。通过对MST中的局部结构的进一步分析，在MST的节点上执行扩展操作以进行匹配图增强，这是通过引入两个扩展方向上的关键连接来实现的。最后，在匹配图的引导下，提出了一种高效的SfM解决方案，并通过综合分析和比较，采用不同倾斜多摄像机系统拍摄的三个无人机数据集，验证了其有效性。实验结果表明，图像匹配的效率在加速比为19〜35的情况下得到了提高，从GCPs（地面控制点）的相对束调整（BA）和GCP的绝对BA获得了竞争定位精度。同时，三个数据集中的图像都是成功定位的。为了定向倾斜的无人机图像，所提出的方法可以是更有效的解决方案。

##### URL
[https://arxiv.org/abs/1705.03212](https://arxiv.org/abs/1705.03212)

##### PDF
[https://arxiv.org/pdf/1705.03212](https://arxiv.org/pdf/1705.03212)

