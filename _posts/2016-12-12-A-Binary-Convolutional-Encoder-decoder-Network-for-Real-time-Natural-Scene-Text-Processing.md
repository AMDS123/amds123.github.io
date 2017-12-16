---
layout: post
title: "A Binary Convolutional Encoder-decoder Network for Real-time Natural Scene Text Processing"
date: 2016-12-12 11:48:00
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Zichuan Liu, Yixing Li, Fengbo Ren, Hao Yu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we develop a binary convolutional encoder-decoder network (B-CEDNet) for natural scene text processing (NSTP). It converts a text image to a class-distinguished salience map that reveals the categorical, spatial and morphological information of characters. The existing solutions are either memory consuming or run-time consuming that cannot be applied to real-time applications on resource-constrained devices such as advanced driver assistance systems. The developed network can process multiple regions containing characters by one-off forward operation, and is trained to have binary weights and binary feature maps, which lead to both remarkable inference run-time speedup and memory usage reduction. By training with over 200, 000 synthesis scene text images (size of $32\times128$), it can achieve $90\%$ and $91\%$ pixel-wise accuracy on ICDAR-03 and ICDAR-13 datasets. It only consumes $4.59\ ms$ inference run-time realized on GPU with a small network size of 2.14 MB, which is up to $8\times$ faster and $96\%$ smaller than it full-precision version.

##### Abstract (translated by Google)
在本文中，我们开发了用于自然场景文本处理（NSTP）的二元卷积编码器 - 解码器网络（B-CEDNet）。它将文本图像转换为类别显着的显示图，显示字符的分类，空间和形态信息。现有解决方案要么耗费内存，要么耗费运行时间，无法应用于资源受限设备（如高级驾驶员辅助系统）上的实时应用程序。所开发的网络可以通过一次性正向操作处理包含字符的多个区域，并且训练得到二进制权重和二进制特征映射，这导致显着的推理运行时加速和内存使用减少。通过对超过200,000个合成场景文本图像（大小为32×128×$）的训练，ICDAR-03和ICDAR-13数据集的精度可以达到90％和91％。它只消耗4.59美元/ ms $的推理运行时间，在2.14MB的小型网络上实现，这比它的全精度版本高出了$ 8 / times $和$ 96 \％$。

##### URL
[https://arxiv.org/abs/1612.03630](https://arxiv.org/abs/1612.03630)

##### PDF
[https://arxiv.org/pdf/1612.03630](https://arxiv.org/pdf/1612.03630)

