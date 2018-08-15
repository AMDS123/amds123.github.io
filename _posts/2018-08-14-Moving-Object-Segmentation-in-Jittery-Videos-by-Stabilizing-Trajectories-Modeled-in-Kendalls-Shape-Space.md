---
layout: post
title: "Moving Object Segmentation in Jittery Videos by Stabilizing Trajectories Modeled in Kendall's Shape Space"
date: 2018-08-14 06:41:21
categories: arXiv_CV
tags: arXiv_CV Sparse OCR Segmentation Optimization Quantitative
author: Geethu Miriam Jacob, Sukhendu Das
mathjax: true
---

* content
{:toc}

##### Abstract
Moving Object Segmentation is a challenging task for jittery/wobbly videos. For jittery videos, the non-smooth camera motion makes discrimination between foreground objects and background layers hard to solve. While most recent works for moving video object segmentation fail in this scenario, our method generates an accurate segmentation of a single moving object. The proposed method performs a sparse segmentation, where frame-wise labels are assigned only to trajectory coordinates, followed by the pixel-wise labeling of frames. The sparse segmentation involving stabilization and clustering of trajectories in a 3-stage iterative process. At the 1st stage, the trajectories are clustered using pairwise Procrustes distance as a cue for creating an affinity matrix. The 2nd stage performs a block-wise Procrustes analysis of the trajectories and estimates Frechet means (in Kendall's shape space) of the clusters. The Frechet means represent the average trajectories of the motion clusters. An optimization function has been formulated to stabilize the Frechet means, yielding stabilized trajectories at the 3rd stage. The accuracy of the motion clusters are iteratively refined, producing distinct groups of stabilized trajectories. Next, the labels obtained from the sparse segmentation are propagated for pixel-wise labeling of the frames, using a GraphCut based energy formulation. Use of Procrustes analysis and energy minimization in Kendall's shape space for moving object segmentation in jittery videos, is the novelty of this work. Second contribution comes from experiments performed on a dataset formed of 20 real-world natural jittery videos, with manually annotated ground truth. Experiments are done with controlled levels of artificial jitter on videos of SegTrack2 dataset. Qualitative and quantitative results indicate the superiority of the proposed method.

##### Abstract (translated by Google)
移动对象分割对于抖动/抖动视频来说是一项具有挑战性的任务。对于抖动的视频，非平滑的相机运动使前景物体和背景层之间的区分难以解决。虽然最近的移动视频对象分割工作在这种情况下失败，但我们的方法可以生成单个移动对象的准确分割。所提出的方法执行稀疏分割，其中逐帧标签仅被分配给轨迹坐标，随后是像素标记的帧。稀疏分割涉及在3阶段迭代过程中稳定和聚类轨迹。在第一阶段，使用成对Procrustes距离作为创建亲和度矩阵的提示来聚类轨迹。第二阶段对轨迹进行逐块Procrustes分析，并估计Frechet意味着（在Kendall的形状空间中）。 Frechet表示运动星团的平均轨迹。已经制定了优化函数来稳定Frechet装置，在第3阶段产生稳定的轨迹。迭代地细化运动星团的精度，产生不同的稳定轨迹组。接下来，使用基于GraphCut的能量公式，传播从稀疏分割获得的标签，用于帧的逐像素标记。在肯德尔的形状空间中使用Procrustes分析和能量最小化来在抖动视频中移动物体分割，这是这项工作的新颖之处。第二个贡献来自对由20个真实世界自然紧张视频组成的数据集进行的实验，其中包含手动注释的基本事实。在SegTrack2数据集的视频上使用受控水平的人工抖动完成实验。定性和定量结果表明了该方法的优越性。

##### URL
[http://arxiv.org/abs/1808.04551](http://arxiv.org/abs/1808.04551)

##### PDF
[http://arxiv.org/pdf/1808.04551](http://arxiv.org/pdf/1808.04551)

