---
layout: post
title: "Efficient Trimmed Convolutional Arithmetic Encoding for Lossless Image Compression"
date: 2018-01-15 04:28:32
categories: arXiv_CV
tags: arXiv_CV CNN RNN Prediction
author: Mu Li, Shuhang Gu, David Zhang, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
Arithmetic encoding is an essential class of coding techniques which have been widely used in various data compression systems and exhibited promising performance. One key issue of arithmetic encoding method is to predict the probability of the current symbol to be encoded from its context, i.e., the preceding encoded symbols, which usually can be executed by building a look-up table (LUT). However, the complexity of LUT increases exponentially with the length of context. Thus, such solutions are limited in modeling large context, which inevitably restricts the compression performance. Several recent convolutional neural network (CNN) and recurrent neural network (RNN)-based solutions have been developed to account for large context, but are still costly in computation. The inefficiency of the existing methods are mainly attributed to that probability prediction is performed independently for the neighboring symbols, which actually can be efficiently conducted by shared computation. To this end, we propose a trimmed convolutional network for arithmetic encoding (TCAE) to model large context while maintaining computational efficiency. As for trimmed convolution, the convolutional kernels are specially trimmed to respect the compression order and context dependency of the input symbols. Benefited from trimmed convolution, the probability prediction of all symbols can be efficiently performed in one single forward pass via a fully convolutional network. Experiments show that our TCAE attains better compression ratio in lossless gray image compression, and can be adopted in CNN-based lossy image compression to achieve state-of-the-art rate-distortion performance with real-time encoding speed.

##### Abstract (translated by Google)
算术编码是一种重要的编码技术，被广泛应用于各种数据压缩系统，展现了良好的性能。算术编码方法的一个关键问题是预测当前符号从其上下文（即前面的编码符号）被编码的概率，这通常可以通过建立查找表（LUT）来执行。然而，LUT的复杂度随着上下文的长度呈指数级增长。因此，这种解决方案在建模大背景下受到限制，这不可避免地限制了压缩性能。最近几个卷积神经网络（CNN）和基于递归神经网络（RNN）的解决方案已经被开发出来以解决大背景，但是计算仍然是昂贵的。现有方法的低效性主要是由于相邻符号独立执行概率预测，实际上可以通过共享计算有效地进行。为此，我们提出了一个修剪卷积网络算术编码（TCAE）来模拟大环境，同时保持计算效率。至于修剪卷积，卷积核被特别修剪以符合输入符号的压缩顺序和上下文依赖性。受益于修剪卷积，所有符号的概率预测可以通过完全卷积网络在单个正向通道中有效执行。实验表明，我们的TCAE在无损灰度图像压缩方面获得了较好的压缩比，可以在基于CNN的有损图像压缩中采用，以达到实时编码速率的最新码率失真性能。

##### URL
[https://arxiv.org/abs/1801.04662](https://arxiv.org/abs/1801.04662)

##### PDF
[https://arxiv.org/pdf/1801.04662](https://arxiv.org/pdf/1801.04662)

