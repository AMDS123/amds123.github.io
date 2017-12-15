---
layout: post
title: "Pairwise Quantization"
date: 2016-06-05 19:57:06
categories: arXiv_CV
tags: arXiv_CV
author: Artem Babenko, Relja Arandjelović, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the task of lossy compression of high-dimensional vectors through quantization. We propose the approach that learns quantization parameters by minimizing the distortion of scalar products and squared distances between pairs of points. This is in contrast to previous works that obtain these parameters through the minimization of the reconstruction error of individual points. The proposed approach proceeds by finding a linear transformation of the data that effectively reduces the minimization of the pairwise distortions to the minimization of individual reconstruction errors. After such transformation, any of the previously-proposed quantization approaches can be used. Despite the simplicity of this transformation, the experiments demonstrate that it achieves considerable reduction of the pairwise distortions compared to applying quantization directly to the untransformed data.

##### Abstract (translated by Google)
我们考虑通过量化来对高维向量进行有损压缩的任务。我们提出了通过最小化标量乘积的失真和点对之间距离的平方来学习量化参数的方法。这与之前通过最小化单个点的重建误差获得这些参数的作品形成对比。所提出的方法通过找到数据的线性变换来进行，这有效地减少了成对失真的最小化，以使个体重建误差最小化。在这种变换之后，可以使用任何先前提出的量化方法。尽管这种转换很简单，但实验表明，与将量化直接应用于未转换的数据相比，它实现了成对失真的相当大的减少。

##### URL
[https://arxiv.org/abs/1606.01550](https://arxiv.org/abs/1606.01550)

##### PDF
[https://arxiv.org/pdf/1606.01550](https://arxiv.org/pdf/1606.01550)

