---
layout: post
title: "Hashing with binary autoencoders"
date: 2015-01-05 03:49:02
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Optimization
author: Miguel Á. Carreira-Perpiñán, Ramin Raziperchikolaei
mathjax: true
---

* content
{:toc}

##### Abstract
An attractive approach for fast search in image databases is binary hashing, where each high-dimensional, real-valued image is mapped onto a low-dimensional, binary vector and the search is done in this binary space. Finding the optimal hash function is difficult because it involves binary constraints, and most approaches approximate the optimization by relaxing the constraints and then binarizing the result. Here, we focus on the binary autoencoder model, which seeks to reconstruct an image from the binary code produced by the hash function. We show that the optimization can be simplified with the method of auxiliary coordinates. This reformulates the optimization as alternating two easier steps: one that learns the encoder and decoder separately, and one that optimizes the code for each image. Image retrieval experiments, using precision/recall and a measure of code utilization, show the resulting hash function outperforms or is competitive with state-of-the-art methods for binary hashing.

##### Abstract (translated by Google)
在图像数据库中快速搜索的一个有吸引力的方法是二进制散列，其中每个高维实值图像被映射到一个低维的二进制向量，并且在这个二进制空间中进行搜索。寻找最佳散列函数是困难的，因为它涉及到二元约束，大多数方法通过放宽约束然后二值化结果来近似优化。在这里，我们专注于二元自动编码器模型，该模型试图从哈希函数产生的二进制代码重构图像。我们表明，可以用辅助坐标的方法来简化优化。这将优化重新形成为交替两个更简单的步骤：分别学习编码器和解码器，以及优化每个图像的代码的步骤。图像检索实验，使用精度/召回率和代码利用率的措施，显示结果散列函数优于或与二进制散列的最先进的方法竞争。

##### URL
[https://arxiv.org/abs/1501.00756](https://arxiv.org/abs/1501.00756)

##### PDF
[https://arxiv.org/pdf/1501.00756](https://arxiv.org/pdf/1501.00756)

