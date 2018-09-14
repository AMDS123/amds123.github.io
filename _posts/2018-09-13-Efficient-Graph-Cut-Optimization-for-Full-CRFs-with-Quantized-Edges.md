---
layout: post
title: "Efficient Graph Cut Optimization for Full CRFs with Quantized Edges"
date: 2018-09-13 14:46:23
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Segmentation Semantic_Segmentation Optimization Inference
author: Olga Veksler
mathjax: true
---

* content
{:toc}

##### Abstract
Fully connected pairwise Conditional Random Fields (Full-CRF) with Gaussian edge weights can achieve superior results compared to sparsely connected CRFs. However, traditional methods for Full-CRFs are too expensive. Previous work develops efficient approximate optimization based on mean field inference, which is a local optimization method and can be far from the optimum. We propose efficient and effective optimization based on graph cuts for Full-CRFs with quantized edge weights. To quantize edge weights, we partition the image into superpixels and assume that the weight of an edge between any two pixels depends only on the superpixels these pixels belong to. Our quantized edge CRF is an approximation to the Gaussian edge CRF, and gets closer to it as superpixel size decreases. Being an approximation, our model offers an intuition about the regularization properties of the Guassian edge Full-CRF. For efficient inference, we first consider the two-label case and develop an approximate method based on transforming the original problem into a smaller domain. Then we handle multi-label CRF by showing how to implement expansion moves. In both binary and multi-label cases, our solutions have significantly lower energy compared to that of mean field inference. We also show the effectiveness of our approach on semantic segmentation task.

##### Abstract (translated by Google)
与稀疏连接的CRF相比，具有高斯边缘权重的完全连接的成对条件随机场（Full-CRF）可以实现更好的结果。但是，Full-CRF的传统方法太昂贵了。以前的工作开发了基于平均场推理的有效近似优化，这是一种局部优化方法，可能远非最优。我们提出了基于具有量化边缘权重的全CRF的图切割的高效且有效的优化。为了量化边缘权重，我们将图像分割成超像素，并假设任何两个像素之间的边缘权重仅取决于这些像素所属的超像素。我们的量化边缘CRF是高斯边缘CRF的近似值，并且随着超像素尺寸减小而变得更接近它。作为近似，我们的模型提供了关于高斯边缘Full-CRF的正则化特性的直觉。为了有效推理，我们首先考虑双标签情况，并基于将原始问题转换为较小的域来开发近似方法。然后我们通过展示如何实现扩展移动来处理多标签CRF。在二元和多标签情况下，与平均场推断相比，我们的解决方案具有显着更低的能量。我们还展示了我们的方法在语义分割任务中的有效性。

##### URL
[http://arxiv.org/abs/1809.04995](http://arxiv.org/abs/1809.04995)

##### PDF
[http://arxiv.org/pdf/1809.04995](http://arxiv.org/pdf/1809.04995)

