---
layout: post
title: "LEGO: Learning Edge with Geometry all at Once by Watching Videos"
date: 2018-03-15 09:14:11
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN
author: Zhenheng Yang, Peng Wang, Yang Wang, Wei Xu, Ram Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to estimate 3D geometry in a single image by watching unlabeled videos via deep convolutional network is attracting significant attention. In this paper, we introduce a "3D as-smooth-as-possible (3D-ASAP)" priori inside the pipeline, which enables joint estimation of edges and 3D scene, yielding results with significant improvement in accuracy for fine detailed structures. Specifically, we define the 3D-ASAP priori by requiring that any two points recovered in 3D from an image should lie on an existing planar surface if no other cues provided. We design an unsupervised framework that Learns Edges and Geometry (depth, normal) all at Once (LEGO). The predicted edges are embedded into depth and surface normal smoothness terms, where pixels without edges in-between are constrained to satisfy the priori. In our framework, the predicted depths, normals and edges are forced to be consistent all the time. We conduct experiments on KITTI to evaluate our estimated geometry and CityScapes to perform edge evaluation. We show that in all of the tasks, i.e.depth, normal and edge, our algorithm vastly outperforms other state-of-the-art (SOTA) algorithms, demonstrating the benefits of our approach.

##### Abstract (translated by Google)
学习通过深卷积网络观察未标记的视频来估计单个图像中的3D几何形状正引起重大关注。在本文中，我们在流水线内部引入了一种“3D尽可能平滑（3D-ASAP）”技术，该技术能够对边缘和三维场景进行联合估计，从而获得精细细致结构精度显着提高的结果。具体来说，我们先定义3D-ASAP，如果没有提供其他提示，则要求3D中从图像中恢复的任何两点应位于现有平面上。我们设计了一个无人监督框架，一次完成学习边缘和几何（深度，正常）（LEGO）。预测边被嵌入到深度和表面法线平滑项中，其中没有边之间的像素被约束以满足先验。在我们的框架中，预测的深度，法线和边缘被迫始终保持一致。我们在KITTI上进行实验以评估我们估计的几何图形和城市景观以执行边缘评估。我们展示了在所有任务中，即深度，正常和边缘，我们的算法大大优于其他最先进的（SOTA）算法，证明了我们方法的好处。

##### URL
[https://arxiv.org/abs/1803.05648](https://arxiv.org/abs/1803.05648)

##### PDF
[https://arxiv.org/pdf/1803.05648](https://arxiv.org/pdf/1803.05648)

