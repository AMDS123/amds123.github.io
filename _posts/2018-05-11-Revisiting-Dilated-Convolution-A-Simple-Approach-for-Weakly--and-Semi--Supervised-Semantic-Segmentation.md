---
layout: post
title: "Revisiting Dilated Convolution: A Simple Approach for Weakly- and Semi- Supervised Semantic Segmentation"
date: 2018-05-11 19:53:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised CNN Semantic_Segmentation Classification
author: Yunchao Wei, Huaxin Xiao, Honghui Shi, Zequn Jie, Jiashi Feng, Thomas S. Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the remarkable progress, weakly supervised segmentation approaches are still inferior to their fully supervised counterparts. We obverse the performance gap mainly comes from their limitation on learning to produce high-quality dense object localization maps from image-level supervision. To mitigate such a gap, we revisit the dilated convolution [1] and reveal how it can be utilized in a novel way to effectively overcome this critical limitation of weakly supervised segmentation approaches. Specifically, we find that varying dilation rates can effectively enlarge the receptive fields of convolutional kernels and more importantly transfer the surrounding discriminative information to non-discriminative object regions, promoting the emergence of these regions in the object localization maps. Then, we design a generic classification network equipped with convolutional blocks of different dilated rates. It can produce dense and reliable object localization maps and effectively benefit both weakly- and semi- supervised semantic segmentation. Despite the apparent simplicity, our proposed approach obtains superior performance over state-of-the-arts. In particular, it achieves 60.8% and 67.6% mIoU scores on Pascal VOC 2012 test set in weakly- (only image-level labels are available) and semi- (1,464 segmentation masks are available) supervised settings, which are the new state-of-the-arts.

##### Abstract (translated by Google)
尽管取得了令人瞩目的进展，但监管不力的细分方法仍然逊于完全监督的细分方法。我们正面对表现差距主要来自他们对学习的限制，即从图像级监督中产生高质量的密集物体定位图。为了缓解这种差距，我们重新审视了扩张卷积[1]，并揭示了如何以一种新颖的方式利用它来有效地克服弱监督分割方法的这种关键限制。具体而言，我们发现不同的膨胀率可以有效地扩大卷积核的感受域，更重要的是将周围的判别信息转移到无差别的目标区域，促进这些区域在目标定位图中的出现。然后，我们设计一个通用分类网络，配备不同膨胀率的卷积分块。它可以产生密集而可靠的对象定位映射，并有效地受益于弱监督和半监督语义分割。尽管表面简单，我们提出的方法比现有技术获得更好的性能。尤其是，它在Pascal VOC 2012测试集中获得了60.8％和67.6％的mIoU分数（只有图像级标签可用）和半分割（1,464分割蒙版可用）监督设置，这是新的状态-艺术。

##### URL
[https://arxiv.org/abs/1805.04574](https://arxiv.org/abs/1805.04574)

##### PDF
[https://arxiv.org/pdf/1805.04574](https://arxiv.org/pdf/1805.04574)

