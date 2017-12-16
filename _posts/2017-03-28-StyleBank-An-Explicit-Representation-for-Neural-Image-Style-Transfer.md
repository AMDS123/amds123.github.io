---
layout: post
title: "StyleBank: An Explicit Representation for Neural Image Style Transfer"
date: 2017-03-28 09:10:10
categories: arXiv_CV
tags: arXiv_CV Style_Transfer Embedding
author: Dongdong Chen, Lu Yuan, Jing Liao, Nenghai Yu, Gang Hua
mathjax: true
---

* content
{:toc}

##### Abstract
We propose StyleBank, which is composed of multiple convolution filter banks and each filter bank explicitly represents one style, for neural image style transfer. To transfer an image to a specific style, the corresponding filter bank is operated on top of the intermediate feature embedding produced by a single auto-encoder. The StyleBank and the auto-encoder are jointly learnt, where the learning is conducted in such a way that the auto-encoder does not encode any style information thanks to the flexibility introduced by the explicit filter bank representation. It also enables us to conduct incremental learning to add a new image style by learning a new filter bank while holding the auto-encoder fixed. The explicit style representation along with the flexible network design enables us to fuse styles at not only the image level, but also the region level. Our method is the first style transfer network that links back to traditional texton mapping methods, and hence provides new understanding on neural style transfer. Our method is easy to train, runs in real-time, and produces results that qualitatively better or at least comparable to existing methods.

##### Abstract (translated by Google)
我们提出由多个卷积滤波器组组成的StyleBank，每个滤波器组明确代表一种风格，用于神经图像风格的转移。为了将图像转换为特定的样式，相应的滤波器组在由单个自动编码器产生的中间特征嵌入之上操作。 StyleBank和自动编码器是共同学习的，其中学习以这样的方式进行，即自动编码器由于显式滤波器组表示引入的灵活性而不编码任何样式信息。它还使我们能够进行增量学习，通过学习新的滤波器组来增加新的图像样式，同时保持固定的自动编码器。明确的风格表现以及灵活的网络设计使我们不仅能够在形象层面融合风格，而且能够融合区域层面的风格。我们的方法是连接到传统的纹理映射方法的第一个样式转移网络，因此提供了神经风格转移的新的认识。我们的方法很容易培训，实时运行，并产生质量更好或至少可与现有方法相媲美的结果。

##### URL
[https://arxiv.org/abs/1703.09210](https://arxiv.org/abs/1703.09210)

##### PDF
[https://arxiv.org/pdf/1703.09210](https://arxiv.org/pdf/1703.09210)

