---
layout: post
title: "Batch based Monocular SLAM for Egocentric Videos"
date: 2017-07-18 11:31:13
categories: arXiv_CV
tags: arXiv_CV Quantitative SLAM
author: Suvam Patra, Kartikeya Gupta, Faran Ahmad, Chetan Arora, Subhashis Banerjee
mathjax: true
---

* content
{:toc}

##### Abstract
Simultaneous Localization and Mapping (SLAM) from a monocular camera has been a well researched area. However, estimating camera pose and 3d geometry reliably for egocentric videos still remain a challenge. Some of the common causes of failures are dominant 3D rotations and low parallax between successive frames, resulting in unreliable pose and 3d estimates. For forward moving cameras, with no opportunities for loop closures, the drift leads to eventual failures for traditional feature based and direct SLAM techniques. We propose a novel batch mode structure from motion based technique for robust SLAM in such scenarios. In contrast to most of the existing techniques, we process frames in short batches, wherein we exploit short loop closures arising out of to-and-fro motion of wearer's head, and stabilize the egomotion estimates by 2D batch mode techniques such as motion averaging on pairwise epipolar results. Once pose estimates are obtained reliably over a batch, we refine the 3d estimate by triangulation and batch mode Bundle Adjustment (BA). Finally, we merge the batches using 3D correspondences and carry out a BA refinement post merging. We present both qualitative and quantitative comparison of our method on various public first and third person video datasets, to establish the robustness and accuracy of our algorithm over the state of the art.

##### Abstract (translated by Google)
单眼相机的同时定位和映射（SLAM）一直是一个很好的研究领域。然而，对于以自我为中心的视频可靠地估计相机姿态和三维几何结构仍然是一个挑战。一些常见的失败原因是连续帧之间的主要3D旋转和低视差，导致不可靠的姿态和3d估计。对于向前移动的摄像机，没有闭环的机会，漂移导致传统的基于特征和直接SLAM技术的最终失败。在这种情况下，我们提出了一种基于运动的，用于健壮SLAM的批处理模式结构。与大多数现有技术相比，我们短时间处理帧，其中我们利用由佩戴者头部的来回运动引起的短环闭合，并且通过2D批量模式技术稳定运动估计，例如运动平均成对的极线结果。一旦在一批中可靠地获得姿态估计，我们通过三角测量和批量模式束调整（BA）来改进三维估计。最后，我们将使用3D对应的批次进行合并，并进行合并后的BA精化。我们提出了定性和定量比较我们的方法在各种公共第一和第三人视频数据集，以建立我们的算法的稳健性和准确性在现有技术。

##### URL
[https://arxiv.org/abs/1707.05564](https://arxiv.org/abs/1707.05564)

##### PDF
[https://arxiv.org/pdf/1707.05564](https://arxiv.org/pdf/1707.05564)

