---
layout: post
title: "Accurate Text Localization in Natural Image with Cascaded Convolutional Text Network"
date: 2016-03-31 00:16:31
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Tong He, Weilin Huang, Yu Qiao, Jian Yao
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new top-down pipeline for scene text detection. We propose a novel Cascaded Convolutional Text Network (CCTN) that joints two customized convolutional networks for coarse-to-fine text localization. The CCTN fast detects text regions roughly from a low-resolution image, and then accurately localizes text lines from each enlarged region. We cast previous character based detection into direct text region estimation, avoiding multiple bottom- up post-processing steps. It exhibits surprising robustness and discriminative power by considering whole text region as detection object which provides strong semantic information. We customize convolutional network by develop- ing rectangle convolutions and multiple in-network fusions. This enables it to handle multi-shape and multi-scale text efficiently. Furthermore, the CCTN is computationally efficient by sharing convolutional computations, and high-level property allows it to be invariant to various languages and multiple orientations. It achieves 0.84 and 0.86 F-measures on the ICDAR 2011 and ICDAR 2013, delivering substantial improvements over state-of-the-art results [23, 1].

##### Abstract (translated by Google)
我们为场景文本检测引入了一个新的自上而下的管道。我们提出了一种新颖的级联卷积文本网络（CCTN），它将两个定制的卷积网络连接起来，实现从粗到精的文本定位。 CCTN可以快速检测低分辨率图像中的文本区域，然后精确定位每个放大区域的文本行。我们将以前的基于字符的检测转换为直接的文本区域估计，避免了多重自底向上的后处理步骤。它将整个文本区域作为提供强大语义信息的检测对象，表现出令人惊讶的鲁棒性和判别力。我们通过开发矩形卷积和多重网内融合来定制卷积网络。这使得它能够有效地处理多形状和多尺度的文字。此外，CCTN通过共享卷积计算在计算上是高效的，并且高级属性允许其对于各种语言和多个方向是不变的。它在ICDAR 2011和ICDAR 2013上实现了0.84和0.86的F-measure，相对于最先进的结果提供了实质性的改进[23,1]。

##### URL
[https://arxiv.org/abs/1603.09423](https://arxiv.org/abs/1603.09423)

##### PDF
[https://arxiv.org/pdf/1603.09423](https://arxiv.org/pdf/1603.09423)

