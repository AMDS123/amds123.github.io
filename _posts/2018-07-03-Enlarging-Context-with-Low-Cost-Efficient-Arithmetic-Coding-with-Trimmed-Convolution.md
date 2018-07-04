---
layout: post
title: "Enlarging Context with Low Cost: Efficient Arithmetic Coding with Trimmed Convolution"
date: 2018-07-03 14:54:20
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Mu Li, Shuhang Gu, David Zhang, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
Arithmetic coding is an essential class of coding techniques. One key issue of arithmetic encoding method is to predict the probability of the current coding symbol from its context, i.e., the preceding encoded symbols, which usually can be executed by building a look-up table (LUT). However, the complexity of LUT increases exponentially with the length of context. Thus, such solutions are limited to modeling large context, which inevitably restricts the compression performance. Several recent deep neural network-based solutions have been developed to account for large context, but are still costly in computation. The inefficiency of the existing methods are mainly attributed to that probability prediction is performed independently for the neighboring symbols, which actually can be efficiently conducted by shared computation. To this end, we propose a trimmed convolutional network for arithmetic encoding (TCAE) to model large context while maintaining computational efficiency. As for trimmed convolution, the convolutional kernels are specially trimmed to respect the compression order and context dependency of the input symbols. Benefited from trimmed convolution, the probability prediction of all symbols can be efficiently performed in one single forward pass via a fully convolutional network. Furthermore, to speed up the decoding process, a slope TCAE model is presented to divide the codes from a 3D code map into several blocks and remove the dependency between the codes inner one block for parallel decoding, which can 60x speed up the decoding process. Experiments show that our TCAE and slope TCAE attain better compression ratio in lossless gray image compression, and can be adopted in CNN-based lossy image compression to achieve state-of-the-art rate-distortion performance with real-time encoding speed.

##### Abstract (translated by Google)
算术编码是一类必不可少的编码技术。算术编码方法的一个关键问题是预测当前编码符号来自其上下文的概率，即前面的编码符号，其通常可以通过构建查找表（LUT）来执行。然而，LUT的复杂性随着上下文的长度呈指数增长。因此，这种解决方案仅限于建模大的上下文，这不可避免地限制了压缩性能。最近开发了几种基于深度神经网络的解决方案来解决大的背景，但计算成本仍然很高。现有方法的低效率主要归因于对于相邻符号独立地执行概率预测，其实际上可以通过共享计算有效地进行。为此，我们提出了一种用于算术编码的修剪卷积网络（TCAE），以在保持计算效率的同时对大型上下文进行建模。对于修剪卷积，卷积内核被特别修剪以尊重输入符号的压缩顺序和上下文依赖性。受益于修剪的卷积，所有符号的概率预测可以通过完全卷积网络在单个前向通道中有效地执行。此外，为了加速解码过程，提出斜率TCAE模型以将代码从3D代码映射分成几个块，并消除用于并行解码的内部一个代码之间的代码之间的依赖性，这可以使解码过程加速60倍。实验表明，我们的TCAE和斜率TCAE在无损灰度图像压缩中获得了更好的压缩比，并且可以在基于CNN的有损图像压缩中采用，以实现具有实时编码速度的最先进的速率 - 失真性能。

##### URL
[http://arxiv.org/abs/1801.04662](http://arxiv.org/abs/1801.04662)

##### PDF
[http://arxiv.org/pdf/1801.04662](http://arxiv.org/pdf/1801.04662)

