---
layout: post
title: "A New Low-Rank Tensor Model for Video Completion"
date: 2015-09-07 13:19:40
categories: arXiv_CV
tags: arXiv_CV Relation
author: Wenrui Hu, Dacheng Tao, Wensheng Zhang, Yuan Xie, Yehui Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new low-rank tensor model based on the circulant algebra, namely, twist tensor nuclear norm or t-TNN for short. The twist tensor denotes a 3-way tensor representation to laterally store 2D data slices in order. On one hand, t-TNN convexly relaxes the tensor multi-rank of the twist tensor in the Fourier domain, which allows an efficient computation using FFT. On the other, t-TNN is equal to the nuclear norm of block circulant matricization of the twist tensor in the original domain, which extends the traditional matrix nuclear norm in a block circulant way. We test the t-TNN model on a video completion application that aims to fill missing values and the experiment results validate its effectiveness, especially when dealing with video recorded by a non-stationary panning camera. The block circulant matricization of the twist tensor can be transformed into a circulant block representation with nuclear norm invariance. This representation, after transformation, exploits the horizontal translation relationship between the frames in a video, and endows the t-TNN model with a more powerful ability to reconstruct panning videos than the existing state-of-the-art low-rank models.

##### Abstract (translated by Google)
本文提出了一种新的基于循环代数的低秩张量模型，即扭曲张量核范数或简称t-TNN。扭曲张量表示按顺序横向存储2D数据切片的三维张量表示。一方面，t-TNN在傅里叶域中松弛地松弛了扭张量的张量多秩，从而可以使用FFT进行有效的计算。另一方面，t-TNN等于原始域扭曲张量的块循环矩阵的核范数，将传统的矩阵核范数扩展为块循环方式。我们在视频完成应用上测试t-TNN模型，旨在填补缺失值，实验结果验证其有效性，特别是在处理由非平稳的平移摄像机记录的视频时。扭转张量的块循环标定可以转化为具有核范数不变性的循环块表示。这种表示在转换之后利用了视频中帧之间的水平转换关系，并赋予t-TNN模型比现有的最先进的低级模型更强大的重构平移视频的能力。

##### URL
[https://arxiv.org/abs/1509.02027](https://arxiv.org/abs/1509.02027)

##### PDF
[https://arxiv.org/pdf/1509.02027](https://arxiv.org/pdf/1509.02027)

