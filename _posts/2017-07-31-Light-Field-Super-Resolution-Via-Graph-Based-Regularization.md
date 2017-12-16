---
layout: post
title: "Light Field Super-Resolution Via Graph-Based Regularization"
date: 2017-07-31 17:17:15
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution
author: Mattia Rossi, Pascal Frossard
mathjax: true
---

* content
{:toc}

##### Abstract
Light field cameras capture the 3D information in a scene with a single exposure. This special feature makes light field cameras very appealing for a variety of applications: from post-capture refocus, to depth estimation and image-based rendering. However, light field cameras suffer by design from strong limitations in their spatial resolution, which should therefore be augmented by computational methods. On the one hand, off-the-shelf single-frame and multi-frame super-resolution algorithms are not ideal for light field data, as they do not consider its particular structure. On the other hand, the few super-resolution algorithms explicitly tailored for light field data exhibit significant limitations, such as the need to estimate an explicit disparity map at each view. In this work we propose a new light field super-resolution algorithm meant to address these limitations. We adopt a multi-frame alike super-resolution approach, where the complementary information in the different light field views is used to augment the spatial resolution of the whole light field. We show that coupling the multi-frame approach with a graph regularizer, that enforces the light field structure via nonlocal self similarities, permits to avoid the costly and challenging disparity estimation step for all the views. Extensive experiments show that the new algorithm compares favorably to the other state-of-the-art methods for light field super-resolution, both in terms of PSNR and visual quality.

##### Abstract (translated by Google)
光场照相机以单次曝光捕捉场景中的3D信息。这一特殊功能使得光场相机非常适合各种应用：从捕获后的重新聚焦，到深度估计和基于图像的渲染。然而，由于空间分辨率的限制，光场相机受到设计的限制，因此应该通过计算方法来增强光场相机的空间分辨率。一方面，现成的单帧和多帧超分辨算法对于光场数据并不理想，因为它们不考虑其特定的结构。另一方面，针对光场数据明确定制的少数超分辨率算法表现出明显的局限性，例如需要在每个视图处估计明确的视差图。在这项工作中，我们提出了一个新的光场超分辨率算法，旨在解决这些限制。我们采用多帧相似的超分辨率方法，其中不同的光场视图中的互补信息被用来增加整个光场的空间分辨率。我们表明，耦合多帧方法与图规则化器，通过非局部自相似性强制光场结构，允许避免所有视图的昂贵和具有挑战性的差异估计步骤。大量的实验表明，新算法在PSNR和视觉质量方面都优于其他最先进的光场超分辨率方法。

##### URL
[https://arxiv.org/abs/1701.02141](https://arxiv.org/abs/1701.02141)

##### PDF
[https://arxiv.org/pdf/1701.02141](https://arxiv.org/pdf/1701.02141)

