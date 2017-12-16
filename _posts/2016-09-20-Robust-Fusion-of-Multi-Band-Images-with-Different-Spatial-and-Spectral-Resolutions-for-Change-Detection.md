---
layout: post
title: "Robust Fusion of Multi-Band Images with Different Spatial and Spectral Resolutions for Change Detection"
date: 2016-09-20 10:04:04
categories: arXiv_CV
tags: arXiv_CV Sparse Detection
author: Vinicius Ferraris, Nicolas Dobigeon, Qi Wei, Marie Chabert
mathjax: true
---

* content
{:toc}

##### Abstract
Archetypal scenarios for change detection generally consider two images acquired through sensors of the same modality. However, in some specific cases such as emergency situations, the only images available may be those acquired through different kinds of sensors. More precisely, this paper addresses the problem of detecting changes between two multi-band optical images characterized by different spatial and spectral resolutions. This sensor dissimilarity introduces additional issues in the context of operational change detection. To alleviate these issues, classical change detection methods are applied after independent preprocessing steps (e.g., resampling) used to get the same spatial and spectral resolutions for the pair of observed images. Nevertheless, these preprocessing steps tend to throw away relevant information. Conversely, in this paper, we propose a method that more effectively uses the available information by modeling the two observed images as spatial and spectral versions of two (unobserved) latent images characterized by the same high spatial and high spectral resolutions. As they cover the same scene, these latent images are expected to be globally similar except for possible changes in sparse spatial locations. Thus, the change detection task is envisioned through a robust multi-band image fusion method which enforces the differences between the estimated latent images to be spatially sparse. This robust fusion problem is formulated as an inverse problem which is iteratively solved using an efficient block-coordinate descent algorithm. The proposed method is applied to real panchormatic/multispectral and hyperspectral images with simulated realistic changes. A comparison with state-of-the-art change detection methods evidences the accuracy of the proposed strategy.

##### Abstract (translated by Google)
变化检测的原型场景通常考虑通过相同形式的传感器获取的两个图像。但是，在某些特殊情况下，例如紧急情况下，唯一可用的图像可能是通过不同类型的传感器获得的图像。更准确地说，本文讨论了检测两个不同空间和光谱分辨率的多波段光学图像之间的变化的问题。这种传感器的不相似性在操作变化检测的上下文中引入了额外的问题。为了减轻这些问题，在经过独立的预处理步骤（例如重采样）之后应用经典变化检测方法来获得观察图像对的相同空间和光谱分辨率。尽管如此，这些预处理步骤倾向于丢弃相关信息。相反，在本文中，我们提出了一种更有效地利用可用信息的方法，通过将两个观察图像建模为具有相同高空间和高光谱分辨率的两个（未观察的）潜像的空间和谱图版本。由于它们覆盖相同的场景，除了可能的稀疏空间位置​​的变化之外，这些潜像预期将是全局相似的。因此，通过稳健的多频带图像融合方法设想变化检测任务，所述方法强制估计的潜像之间的差异在空间上是稀疏的。这个稳健的融合问题被表述为一个反问题，它使用一个有效的块坐标下降算法迭代求解。将该方法应用于模拟真实变化的实际泛光/多光谱和高光谱图像。与最先进的变化检测方法进行比较证明了所提出的策略的准确性。

##### URL
[https://arxiv.org/abs/1609.06076](https://arxiv.org/abs/1609.06076)

##### PDF
[https://arxiv.org/pdf/1609.06076](https://arxiv.org/pdf/1609.06076)

