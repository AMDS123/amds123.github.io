---
layout: post
title: "Pruned non-local means"
date: 2017-02-16 12:11:05
categories: arXiv_CV
tags: arXiv_CV
author: Sanjay Ghosh, Amit K. Mandal, Kunal N. Chaudhury
mathjax: true
---

* content
{:toc}

##### Abstract
In Non-Local Means (NLM), each pixel is denoised by performing a weighted averaging of its neighboring pixels, where the weights are computed using image patches. We demonstrate that the denoising performance of NLM can be improved by pruning the neighboring pixels, namely, by rejecting neighboring pixels whose weights are below a certain threshold $\lambda$. While pruning can potentially reduce pixel averaging in uniform-intensity regions, we demonstrate that there is generally an overall improvement in the denoising performance. In particular, the improvement comes from pixels situated close to edges and corners. The success of the proposed method strongly depends on the choice of the global threshold $\lambda$, which in turn depends on the noise level and the image characteristics. We show how Stein's unbiased estimator of the mean-squared error can be used to optimally tune $\lambda$, at a marginal computational overhead. We present some representative denoising results to demonstrate the superior performance of the proposed method over NLM and its variants.

##### Abstract (translated by Google)
在非局部均值（NLM）中，通过对其相邻像素执行加权平均来对每个像素进行去噪，其中使用图像块来计算权重。我们证明NLM的去噪性能可以通过修剪相邻像素来改善，即通过拒绝权重低于某个阈值$ \ lambda $的相邻像素。虽然修剪可能会降低均匀强度区域的像素均值，但我们证明去噪性能总体上有所提高。特别是，来自位于边缘和角落附近的像素的改进。所提出的方法的成功强烈依赖于全局阈值$ \ lambda $的选择，其依次取决于噪声水平和图像特征。我们展示了Stein的均方误差的无偏估计可以用来在边际计算开销下最优地调整$ \ lambda $。我们给出了一些有代表性的去噪结果，以证明所提出的方法优于NLM及其变体的优越性能。

##### URL
[https://arxiv.org/abs/1701.08280](https://arxiv.org/abs/1701.08280)

##### PDF
[https://arxiv.org/pdf/1701.08280](https://arxiv.org/pdf/1701.08280)

