---
layout: post
title: "Image Denoising via Collaborative Dual-Domain Patch Filtering"
date: 2018-05-01 17:01:21
categories: arXiv_CV
tags: arXiv_CV Sparse Relation
author: Muzammil Behzad
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel image denoising algorithm exploiting features from both spatial as well as transformed domain. We implement intensity-invariance based improved grouping for collaborative support-agnostic sparse reconstruction. For collaboration firstly, we stack similar-structured patches via intensity-invariant correlation measure. The grouped patches collaborate to yield desirable sparse estimates for noise filtering. This is because similar patches share the same support in the transformed domain, such similar supports can be used as probabilities of active taps to refine the sparse estimates. This ultimately produces a very useful patch estimate thus increasing the quality of recovered image by discarding the noise-causing components. A region growing based spatially developed post-processor is then applied to further enhance the smooth regions by extracting the spatial domain features. We also extend our proposed method for denoising of color images. Comparison results with the state-of-the-art algorithms in terms of peak signal-to-noise ratio (PNSR) and structural similarity (SSIM) index from extensive experimentations via a broad range of scenarios demonstrate the superiority of our proposed algorithm.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的图像去噪算法，它利用空间和变换域的特征。我们实施基于强度不变性的改进分组，用于协作支持不可知稀疏重构。首先对于协作，我们通过强度不变相关度量来叠加类似结构的补丁。分组的补丁协作产生噪声过滤所需的稀疏估计。这是因为类似的补丁在变换的域中共享相同的支持，这种类似的支持可以用作活动抽头的概率来改进稀疏估计。这最终产生非常有用的补丁估计，从而通过丢弃引起噪声的组件来提高恢复的图像的质量。然后应用基于空间拓展的后处理器的区域增长，通过提取空间域特征来进一步增强平滑区域。我们还扩展了我们提出的用于去除彩色图像的方法。根据广泛的实验通过广泛的场景的峰值信噪比（PNSR）和结构相似性（SSIM）指数与最先进的算法的比较结果证明了我们提出的算法的优越性。

##### URL
[https://arxiv.org/abs/1805.00472](https://arxiv.org/abs/1805.00472)

##### PDF
[https://arxiv.org/pdf/1805.00472](https://arxiv.org/pdf/1805.00472)

