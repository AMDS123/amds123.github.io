---
layout: post
title: "Fast Optical Flow using Dense Inverse Search"
date: 2016-03-11 10:55:07
categories: arXiv_CV
tags: arXiv_CV Tracking Detection Recognition
author: Till Kroeger, Radu Timofte, Dengxin Dai, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Most recent works in optical flow extraction focus on the accuracy and neglect the time complexity. However, in real-life visual applications, such as tracking, activity detection and recognition, the time complexity is critical. We propose a solution with very low time complexity and competitive accuracy for the computation of dense optical flow. It consists of three parts: 1) inverse search for patch correspondences; 2) dense displacement field creation through patch aggregation along multiple scales; 3) variational refinement. At the core of our Dense Inverse Search-based method (DIS) is the efficient search of correspondences inspired by the inverse compositional image alignment proposed by Baker and Matthews in 2001. DIS is competitive on standard optical flow benchmarks with large displacements. DIS runs at 300Hz up to 600Hz on a single CPU core, reaching the temporal resolution of human's biological vision system. It is order(s) of magnitude faster than state-of-the-art methods in the same range of accuracy, making DIS ideal for visual applications.

##### Abstract (translated by Google)
最近在光流提取方面的工作集中在精度上，而忽略了时间复杂度。然而，在实际的视觉应用中，例如跟踪，活动检测和识别，时间复杂性是至关重要的。我们提出了一个计算密集光流量具有非常低的时间复杂度和竞争精度的解决方案。它由三部分组成：1）反向查找补丁对应; 2）通过多尺度斑块聚集形成稠密位移场; 3）变化细化。我们的密集逆向搜索方法（DIS）的核心是对由Baker和Matthews在2001年提出的逆向组合图像对齐所启发的对应的高效搜索.DIS在具有大位移的标准光流基准上是有竞争力的。 DIS在单个CPU内核上以300Hz运行至600Hz，达到了人类生物视觉系统的时间分辨率。在相同的精度范围内，它的数量级要比最先进的方法快，使得DIS成为视觉应用的理想选择。

##### URL
[https://arxiv.org/abs/1603.03590](https://arxiv.org/abs/1603.03590)

##### PDF
[https://arxiv.org/pdf/1603.03590](https://arxiv.org/pdf/1603.03590)

