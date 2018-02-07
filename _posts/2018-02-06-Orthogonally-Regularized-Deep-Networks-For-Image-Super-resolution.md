---
layout: post
title: "Orthogonally Regularized Deep Networks For Image Super-resolution"
date: 2018-02-06 15:57:49
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Inference Deep_Learning
author: Tiantong Guo, Hojjat S. Mousavi, Vishal Monga
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning methods, in particular trained Convolutional Neural Networks (CNNs) have recently been shown to produce compelling state-of-the-art results for single image Super-Resolution (SR). Invariably, a CNN is learned to map the low resolution (LR) image to its corresponding high resolution (HR) version in the spatial domain. Aiming for faster inference and more efficient solutions than solving the SR problem in the spatial domain, we propose a novel network structure for learning the SR mapping function in an image transform domain, specifically the Discrete Cosine Transform (DCT). As a first contribution, we show that DCT can be integrated into the network structure as a Convolutional DCT (CDCT) layer. We further extend the network to allow the CDCT layer to become trainable (i.e. optimizable). Because this layer represents an image transform, we enforce pairwise orthogonality constraints on the individual basis functions/filters. This Orthogonally Regularized Deep SR network (ORDSR) simplifies the SR task by taking advantage of image transform domain while adapting the design of transform basis to the training image set.

##### Abstract (translated by Google)
深度学习方法，特别是经过训练的卷积神经网络（CNN）最近已被证明能够产生引人注目的单幅图像超分辨率（SR）的最新技术结果。总而言之，CNN被学会将低分辨率（LR）图像映射到其在空间域中的相应的高分辨率（HR）版本。本文提出了一种新颖的网络结构，用于在图像变换域学习SR映射函数，具体为离散余弦变换（Discrete Cosine Transform，DCT），其目的是为了更快的推理和更有效的解决方案。作为第一个贡献，我们表明可以将DCT作为卷积DCT（CDCT）层集成到网络结构中。我们进一步扩展网络以允许CDCT层变得可训练（即可优化）。因为这个图层代表一个图像变换，所以我们在各个基本函数/过滤器上强制成对的正交性约束。该正交正则化Deep SR网络（ORDSR）利用图像变换域简化了SR任务，同时将变换基础设计与训练图像集合相匹配。

##### URL
[http://arxiv.org/abs/1802.02018](http://arxiv.org/abs/1802.02018)

##### PDF
[http://arxiv.org/pdf/1802.02018](http://arxiv.org/pdf/1802.02018)

