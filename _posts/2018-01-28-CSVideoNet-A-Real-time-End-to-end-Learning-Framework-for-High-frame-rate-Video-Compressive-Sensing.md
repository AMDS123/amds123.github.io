---
layout: post
title: "CSVideoNet: A Real-time End-to-end Learning Framework for High-frame-rate Video Compressive Sensing"
date: 2018-01-28 04:32:43
categories: arXiv_CV
tags: arXiv_CV Optimization RNN
author: Kai Xu, Fengbo Ren
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the real-time encoding-decoding problem for high-frame-rate video compressive sensing (CS). Unlike prior works that perform reconstruction using iterative optimization-based approaches, we propose a non-iterative model, named "CSVideoNet". CSVideoNet directly learns the inverse mapping of CS and reconstructs the original input in a single forward propagation. To overcome the limitations of existing CS cameras, we propose a multi-rate CNN and a synthesizing RNN to improve the trade-off between compression ratio (CR) and spatial-temporal resolution of the reconstructed videos. The experiment results demonstrate that CSVideoNet significantly outperforms the state-of-the-art approaches. With no pre/post-processing, we achieve 25dB PSNR recovery quality at 100x CR, with a frame rate of 125 fps on a Titan X GPU. Due to the feedforward and high-data-concurrency natures of CSVideoNet, it can take advantage of GPU acceleration to achieve three orders of magnitude speed-up over conventional iterative-based approaches. We share the source code at https://github.com/PSCLab-ASU/CSVideoNet.

##### Abstract (translated by Google)
本文针对高帧率视频压缩感知（CS）的实时编解码问题。与以前使用基于迭代优化的方法执行重构的工作不同，我们提出了一个名为“CSVideoNet”的非迭代模型。 CSVideoNet直接学习CS的逆映射，并在一次正向传播中重建原始输入。为了克服现有CS摄像机的局限性，提出了一种多速率CNN和一种合成RNN，以改善重建视频的压缩比（CR）与时空分辨率之间的折衷。实验结果表明，CSVideoNet明显优于最先进的方法。在没有预处理/后处理的情况下，我们在100x CR处获得25dB的PSNR恢复质量，在Titan X GPU上的帧频为125 fps。由于CSVideoNet的前馈和高数据并发性，它可以利用GPU加速比传统的基于迭代的方法实现三个数量级的加速。我们在https://github.com/PSCLab-ASU/CSVideoNet共享源代码。

##### URL
[http://arxiv.org/abs/1612.05203](http://arxiv.org/abs/1612.05203)

##### PDF
[http://arxiv.org/pdf/1612.05203](http://arxiv.org/pdf/1612.05203)

