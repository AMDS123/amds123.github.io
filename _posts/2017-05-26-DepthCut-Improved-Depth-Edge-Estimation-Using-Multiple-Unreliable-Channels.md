---
layout: post
title: "DepthCut: Improved Depth Edge Estimation Using Multiple Unreliable Channels"
date: 2017-05-26 14:21:54
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Quantitative
author: Paul Guerrero, Holger Winnemöller, Wilmot Li, Niloy J. Mitra
mathjax: true
---

* content
{:toc}

##### Abstract
In the context of scene understanding, a variety of methods exists to estimate different information channels from mono or stereo images, including disparity, depth, and normals. Although several advances have been reported in the recent years for these tasks, the estimated information is often imprecise particularly near depth discontinuities or creases. Studies have however shown that precisely such depth edges carry critical cues for the perception of shape, and play important roles in tasks like depth-based segmentation or foreground selection. Unfortunately, the currently extracted channels often carry conflicting signals, making it difficult for subsequent applications to effectively use them. In this paper, we focus on the problem of obtaining high-precision depth edges (i.e., depth contours and creases) by jointly analyzing such unreliable information channels. We propose DepthCut, a data-driven fusion of the channels using a convolutional neural network trained on a large dataset with known depth. The resulting depth edges can be used for segmentation, decomposing a scene into depth layers with relatively flat depth, or improving the accuracy of the depth estimate near depth edges by constraining its gradients to agree with these edges. Quantitatively, we compare against 15 variants of baselines and demonstrate that our depth edges result in an improved segmentation performance and an improved depth estimate near depth edges compared to data-agnostic channel fusion. Qualitatively, we demonstrate that the depth edges result in superior segmentation and depth orderings.

##### Abstract (translated by Google)
在场景理解的背景下，存在多种方法来估计来自单声道或立体声图像的不同信息通道，包括视差，深度和法线。虽然近年来已经报道了这些任务的若干进展，但估计的信息常常不准确，特别是在深度不连续或折痕附近。然而研究表明，正是这种深度边缘为形状的感知提供了关键线索，并在基于深度的分割或前景选择等任务中发挥重要作用。不幸的是，目前提取的频道往往带有冲突的信号，使后续应用难以有效地使用它们。在本文中，我们着重讨论通过共同分析这种不可靠信息通道来获得高精度深度边缘（即深度轮廓和折痕）的问题。我们建议DepthCut，一个数据驱动融合的渠道使用卷积神经网络训练的大型数据集已知深度。得到的深度边缘可用于分割，将场景分解为深度相对平坦的深度层，或者通过约束深度边缘与边缘一致来提高深度边缘附近的深度估计的精度。在数量上，我们与基线的15个变体进行比较，并证明我们的深度边缘导致改进的分割性能和与数据不可知的信道融合相比在深度边缘附近的改进的深度估计。定性地，我们证明深度边缘导致更好的分割和深度排序。

##### URL
[https://arxiv.org/abs/1705.07844](https://arxiv.org/abs/1705.07844)

##### PDF
[https://arxiv.org/pdf/1705.07844](https://arxiv.org/pdf/1705.07844)

