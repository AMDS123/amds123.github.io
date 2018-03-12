---
layout: post
title: "Deep Neural Network Compression with Single and Multiple Level Quantization"
date: 2018-03-06 01:47:52
categories: arXiv_AI
tags: arXiv_AI
author: Yuhui Xu, Yongzhuang Wang, Aojun Zhou, Weiyao Lin, Hongkai Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Network quantization is an effective solution to compress deep neural networks for practical usage. Existing network quantization methods cannot sufficiently exploit the depth information to generate low-bit compressed network. In this paper, we propose two novel network quantization approaches, single-level network quantization (SLQ) for high-bit quantization and multi-level network quantization (MLQ) for extremely low-bit quantization (ternary).We are the first to consider the network quantization from both width and depth level. In the width level, parameters are divided into two parts: one for quantization and the other for re-training to eliminate the quantization loss. SLQ leverages the distribution of the parameters to improve the width level. In the depth level, we introduce incremental layer compensation to quantize layers iteratively which decreases the quantization loss in each iteration. The proposed approaches are validated with extensive experiments based on the state-of-the-art neural networks including AlexNet, VGG-16, GoogleNet and ResNet-18. Both SLQ and MLQ achieve impressive results.

##### Abstract (translated by Google)
网络量化是对实际使用的深度神经网络进行压缩的有效解决方案。现有的网络量化方法不能充分利用深度信息来生成低位压缩网络。在本文中，我们提出了两种新的网络量化方法，用于高比特量化的单级网络量化（SLQ）和用于极低比特量化（三元）的多级网络量化（MLQ）。我们首先考虑从宽度和深度两个层面进行网络量化。在宽度级别，参数分为两部分：一部分用于量化，另一部分用于重新训练以消除量化损失。 SLQ利用参数的分布来提高宽度级别。在深度层面，我们引入增量层补偿来迭代地量化层，这减少了每次迭代中的量化损失。所提出的方法通过基于最先进的神经网络（包括AlexNet，VGG-16，GoogleNet和ResNet-18）的广泛实验进行验证。 SLQ和MLQ都取得了骄人的成绩。

##### URL
[http://arxiv.org/abs/1803.03289](http://arxiv.org/abs/1803.03289)

##### PDF
[http://arxiv.org/pdf/1803.03289](http://arxiv.org/pdf/1803.03289)

