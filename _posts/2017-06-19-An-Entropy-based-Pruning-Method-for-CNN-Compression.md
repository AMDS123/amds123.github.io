---
layout: post
title: "An Entropy-based Pruning Method for CNN Compression"
date: 2017-06-19 05:29:29
categories: arXiv_CV
tags: arXiv_CV
author: Jian-Hao Luo, Jianxin Wu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims to simultaneously accelerate and compress off-the-shelf CNN models via filter pruning strategy. The importance of each filter is evaluated by the proposed entropy-based method first. Then several unimportant filters are discarded to get a smaller CNN model. Finally, fine-tuning is adopted to recover its generalization ability which is damaged during filter pruning. Our method can reduce the size of intermediate activations, which would dominate most memory footprint during model training stage but is less concerned in previous compression methods. Experiments on the ILSVRC-12 benchmark demonstrate the effectiveness of our method. Compared with previous filter importance evaluation criteria, our entropy-based method obtains better performance. We achieve 3.3x speed-up and 16.64x compression on VGG-16, 1.54x acceleration and 1.47x compression on ResNet-50, both with about 1% top-5 accuracy decrease.

##### Abstract (translated by Google)
本文旨在通过滤波器修剪策略同时加速和压缩现成的CNN模型。首先通过提出的基于熵的方法评估每个滤波器的重要性。然后丢弃几个不重要的过滤器以获得更小的CNN模型。最后，采用微调来恢复滤波器修剪过程中损坏的泛化能力。我们的方法可以减小中间激活的大小，这将在模型训练阶段占据大部分内存占用，但是在之前的压缩方法中较少关注。 ILSVRC-12基准的实验证明了我们方法的有效性。与之前的过滤重要性评价标准相比，基于熵的方法取得了较好的性能。我们在VGG-16上实现3.3倍加速和16.64倍压缩，在ResNet-50上实现1.54倍加速和1.47倍压缩，两者的精度都降低了大约1％。

##### URL
[https://arxiv.org/abs/1706.05791](https://arxiv.org/abs/1706.05791)

##### PDF
[https://arxiv.org/pdf/1706.05791](https://arxiv.org/pdf/1706.05791)

