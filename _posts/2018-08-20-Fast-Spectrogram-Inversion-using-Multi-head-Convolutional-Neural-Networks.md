---
layout: post
title: "Fast Spectrogram Inversion using Multi-head Convolutional Neural Networks"
date: 2018-08-20 23:19:48
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition CNN Recognition
author: Sercan O. Arik, Heewoo Jun, Gregory Diamos
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the multi-head convolutional neural network (MCNN) architecture for waveform synthesis from spectrograms. Nonlinear interpolation in MCNN is employed with transposed convolution layers in parallel heads. MCNN achieves more than an order of magnitude higher compute intensity than commonly-used iterative algorithms like Griffin-Lim, yielding efficient utilization for modern multi-core processors, and very fast (more than 300x real-time) waveform synthesis. For training of MCNN, we use a large-scale speech recognition dataset and losses defined on waveforms that are related to perceptual audio quality. We demonstrate that MCNN constitutes a very promising approach for high-quality speech synthesis, without any iterative algorithms or autoregression in computations.

##### Abstract (translated by Google)
我们提出了用于从频谱图进行波形合成的多头卷积神经网络（MCNN）架构。 MCNN中的非线性插值用于并行头中的转置卷积层。 MCNN的计算强度比Griffin-Lim等常用迭代算法高出一个数量级，可以有效地利用现代多核处理器，并且可以实现非常快速（超过300倍的实时）波形合成。对于MCNN的训练，我们使用大规模语音识别数据集和在与感知音频质量相关的波形上定义的损失。我们证明了MCNN构成了一种非常有前途的高质量语音合成方法，无需任何迭代算法或计算中的自回归。

##### URL
[http://arxiv.org/abs/1808.06719](http://arxiv.org/abs/1808.06719)

##### PDF
[http://arxiv.org/pdf/1808.06719](http://arxiv.org/pdf/1808.06719)

