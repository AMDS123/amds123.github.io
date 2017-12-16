---
layout: post
title: "Working hard to know your neighbor's margins: Local descriptor learning loss"
date: 2017-11-05 14:03:14
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Anastasiya Mishchuk, Dmytro Mishkin, Filip Radenovic, Jiri Matas
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel loss for learning local feature descriptors which is inspired by the Lowe's matching criterion for SIFT. We show that the proposed loss that maximizes the distance between the closest positive and closest negative patch in the batch is better than complex regularization methods; it works well for both shallow and deep convolution network architectures. Applying the novel loss to the L2Net CNN architecture results in a compact descriptor -- it has the same dimensionality as SIFT (128) that shows state-of-art performance in wide baseline stereo, patch verification and instance retrieval benchmarks. It is fast, computing a descriptor takes about 1 millisecond on a low-end GPU.

##### Abstract (translated by Google)
我们引入了一个新颖的学习局部特征描述符的损失，它受到了SIFT的Lowe匹配准则的启发。我们表明，提出的损失，最大的距离之间的最接近的正面和最接近的负面补丁在批次比复杂正则化方法好;它适用于浅层和深层卷积网络体系结构。在L2Net CNN体系结构中应用这种新颖的损失会产生一个紧凑的描述符 - 它具有与SIFT（128）相同的维度，能够在宽基线立体声，补丁验证和实例检索基准测试中显示最新的性能。计算描述符的速度很快，在低端GPU上需要大约1毫秒。

##### URL
[https://arxiv.org/abs/1705.10872](https://arxiv.org/abs/1705.10872)

##### PDF
[https://arxiv.org/pdf/1705.10872](https://arxiv.org/pdf/1705.10872)

