---
layout: post
title: "Enabling Sparse Winograd Convolution by Native Pruning"
date: 2017-10-13 18:10:39
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Sheng Li, Jongsoo Park, Ping Tak Peter Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Sparse methods and the use of Winograd convolutions are two orthogonal approaches, each of which significantly accelerates convolution computations in modern CNNs. Sparse Winograd merges these two and thus has the potential to offer a combined performance benefit. Nevertheless, training convolution layers so that the resulting Winograd kernels are sparse has not hitherto been very successful. By introducing a Winograd layer in place of a standard convolution layer, we can learn and prune Winograd coefficients "natively" and obtain sparsity level beyond 90% with only 0.1% accuracy loss with AlexNet on ImageNet dataset. Furthermore, we present a sparse Winograd convolution algorithm and implementation that exploits the sparsity, achieving up to 31.7 effective TFLOP/s in 32-bit precision on a latest Intel Xeon CPU, which corresponds to a 5.4x speedup over a state-of-the-art dense convolution implementation.

##### Abstract (translated by Google)
稀疏方法和Winograd卷积的使用是两个正交的方法，每个方法都显着加速了现代CNN中的卷积计算。稀疏Winograd合并这两个，因此有潜力提供综合性能的好处。尽管如此，训练卷积层以使得Winograd内核稀​​疏并不是迄今为止非常成功的。通过引入Winograd层代替标准的卷积图层，我们可以“自然地”学习和修剪Winograd系数，获得超过90％的稀疏性水平，而ImageNet数据集上的AlexNet只有0.1％的准确性损失。此外，我们提出了一个稀疏的Winograd卷积算法和利用稀疏性的实现，在最新的Intel Xeon CPU上以32位精度实现了高达31.7的有效TFLOP / s，相当于5.4x的加速比-art密集卷积实现。

##### URL
[https://arxiv.org/abs/1702.08597](https://arxiv.org/abs/1702.08597)

##### PDF
[https://arxiv.org/pdf/1702.08597](https://arxiv.org/pdf/1702.08597)

