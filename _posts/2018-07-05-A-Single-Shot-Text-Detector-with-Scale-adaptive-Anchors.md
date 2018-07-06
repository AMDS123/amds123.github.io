---
layout: post
title: "A Single Shot Text Detector with Scale-adaptive Anchors"
date: 2018-07-05 07:48:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Qi Yuan, Bingwang Zhang, Haojie Li, Zhihui Wang, Zhongxuan Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Currently, most top-performing text detection networks tend to employ fixed-size anchor boxes to guide the search for text instances. They usually rely on a large amount of anchors with different scales to discover texts in scene images, thus leading to high computational cost. In this paper, we propose an end-to-end box-based text detector with scale-adaptive anchors, which can dynamically adjust the scales of anchors according to the sizes of underlying texts by introducing an additional scale regression layer. The proposed scale-adaptive anchors allow us to use a few number of anchors to handle multi-scale texts and therefore significantly improve the computational efficiency. Moreover, compared to discrete scales used in previous methods, the learned continuous scales are more reliable, especially for small texts detection. Additionally, we propose Anchor convolution to better exploit necessary feature information by dynamically adjusting the sizes of receptive fields according to the learned scales. Extensive experiments demonstrate that the proposed detector is fast, taking only $0.28$ second per image, while outperforming most state-of-the-art methods in accuracy.

##### Abstract (translated by Google)
目前，大多数表现最佳的文本检测网络倾向于使用固定大小的锚箱来指导搜索文本实例。它们通常依赖于具有不同尺度的大量锚来发现场景图像中的文本，因此导致高计算成本。在本文中，我们提出了一种具有尺度自适应锚点的端到端基于盒子的文本检测器，它可以通过引入额外的比例回归层，根据基础文本的大小动态调整锚点的比例。所提出的尺度自适应锚点允许我们使用少量锚点来处理多尺度文本，因此显着提高了计算效率。此外，与先前方法中使用的离散尺度相比，所学习的连续尺度更可靠，尤其对于小文本检测。此外，我们建议使用Anchor卷积来更好地利用必要的特征信息，方法是根据学习的尺度动态调整感受野的大小。大量实验表明，所提出的探测器速度很快，每张图像只需0.28美元一秒，同时在精度方面优于大多数最先进的方法。

##### URL
[http://arxiv.org/abs/1807.01884](http://arxiv.org/abs/1807.01884)

##### PDF
[http://arxiv.org/pdf/1807.01884](http://arxiv.org/pdf/1807.01884)

