---
layout: post
title: "Parallel Structure from Motion from Local Increment to Global Averaging"
date: 2017-06-05 03:05:15
categories: arXiv_CV
tags: arXiv_CV
author: Siyu Zhu, Tianwei Shen, Lei Zhou, Runze Zhang, Jinglu Wang, Tian Fang, Long Quan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we tackle the accurate and consistent Structure from Motion (SfM) problem, in particular camera registration, far exceeding the memory of a single computer in parallel. Different from the previous methods which drastically simplify the parameters of SfM and sacrifice the accuracy of the final reconstruction, we try to preserve the connectivities among cameras by proposing a camera clustering algorithm to divide a large SfM problem into smaller sub-problems in terms of camera clusters with overlapping. We then exploit a hybrid formulation that applies the relative poses from local incremental SfM into a global motion averaging framework and produce accurate and consistent global camera poses. Our scalable formulation in terms of camera clusters is highly applicable to the whole SfM pipeline including track generation, local SfM, 3D point triangulation and bundle adjustment. We are even able to reconstruct the camera poses of a city-scale data-set containing more than one million high-resolution images with superior accuracy and robustness evaluated on benchmark, Internet, and sequential data-sets.

##### Abstract (translated by Google)
在本文中，我们解决了精确和一致的运动结构（SfM）问题，尤其是相机注册，远远超过了单个计算机的并行存储。与以前的方法大大简化了SfM的参数，牺牲了最终重建的准确性不同，我们试图通过提出一种摄像机聚类算法来将摄像机之间的连接性分开，从而将大的SfM问题分解成更小的子摄像机问题集群与重叠。然后，我们利用混合公式，将来自局部增量SfM的相对姿态应用到全局运动平均框架中，并产生准确一致的全局相机姿态。我们在相机群集方面的可扩展公式非常适用于整个SfM管道，包括轨道生成，局部SfM，3D点三角测量和束调整。我们甚至可以重建包含超过一百万张高分辨率图像的城市规模数据集的摄像机姿态，该图像具有基准，互联网和连续数据集的卓越准确性和鲁棒性。

##### URL
[https://arxiv.org/abs/1702.08601](https://arxiv.org/abs/1702.08601)

##### PDF
[https://arxiv.org/pdf/1702.08601](https://arxiv.org/pdf/1702.08601)

