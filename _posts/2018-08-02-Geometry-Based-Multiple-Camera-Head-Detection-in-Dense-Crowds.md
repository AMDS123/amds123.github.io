---
layout: post
title: "Geometry-Based Multiple Camera Head Detection in Dense Crowds"
date: 2018-08-02 15:23:47
categories: arXiv_CV
tags: arXiv_CV Optimization Detection
author: Nicola Pellican&#xf2;, Emanuel Aldea, Sylvie Le H&#xe9;garat-Mascle
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of head detection in crowded environments. Our detection is based entirely on the geometric consistency across cameras with overlapping fields of view, and no additional learning process is required. We propose a fully unsupervised method for inferring scene and camera geometry, in contrast to existing algorithms which require specific calibration procedures. Moreover, we avoid relying on the presence of body parts other than heads or on background subtraction, which have limited effectiveness under heavy clutter. We cast the head detection problem as a stereo MRF-based optimization of a dense pedestrian height map, and we introduce a constraint which aligns the height gradient according to the vertical vanishing point direction. We validate the method in an outdoor setting with varying pedestrian density levels. With only three views, our approach is able to detect simultaneously tens of heavily occluded pedestrians across a large, homogeneous area.

##### Abstract (translated by Google)
本文讨论了拥挤环境中的头部检测问题。我们的检测完全基于具有重叠视野的摄像机的几何一致性，并且不需要额外的学习过程。我们提出了一种用于推断场景和相机几何结构的完全无监督的方法，与现有的需要特定校准程序的算法相比。此外，我们避免依赖于头部以外的身体部位或背景扣除的存在，这在重杂波下的效果有限。我们将头部检测问题作为基于立体MRF的密集行人高度图的优化，并且引入了根据垂直消失点方向对齐高度梯度的约束。我们在室外环境中验证该方法，具有不同的行人密度水平。只有三个视图，我们的方法能够同时检测大型均匀区域内数十个严重遮挡的行人。

##### URL
[http://arxiv.org/abs/1808.00856](http://arxiv.org/abs/1808.00856)

##### PDF
[http://arxiv.org/pdf/1808.00856](http://arxiv.org/pdf/1808.00856)

