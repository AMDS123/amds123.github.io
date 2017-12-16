---
layout: post
title: "MCMC Shape Sampling for Image Segmentation with Nonparametric Shape Priors"
date: 2016-11-11 15:37:06
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Ertunc Erdil, Sinan Yıldırım, Müjdat Çetin, Tolga Taşdizen
mathjax: true
---

* content
{:toc}

##### Abstract
Segmenting images of low quality or with missing data is a challenging problem. Integrating statistical prior information about the shapes to be segmented can improve the segmentation results significantly. Most shape-based segmentation algorithms optimize an energy functional and find a point estimate for the object to be segmented. This does not provide a measure of the degree of confidence in that result, neither does it provide a picture of other probable solutions based on the data and the priors. With a statistical view, addressing these issues would involve the problem of characterizing the posterior densities of the shapes of the objects to be segmented. For such characterization, we propose a Markov chain Monte Carlo (MCMC) sampling-based image segmentation algorithm that uses statistical shape priors. In addition to better characterization of the statistical structure of the problem, such an approach would also have the potential to address issues with getting stuck at local optima, suffered by existing shape-based segmentation methods. Our approach is able to characterize the posterior probability density in the space of shapes through its samples, and to return multiple solutions, potentially from different modes of a multimodal probability density, which would be encountered, e.g., in segmenting objects from multiple shape classes. We present promising results on a variety of data sets. We also provide an extension for segmenting shapes of objects with parts that can go through independent shape variations. This extension involves the use of local shape priors on object parts and provides robustness to limitations in shape training data size.

##### Abstract (translated by Google)
分割低质量图像或丢失数据是一个具有挑战性的问题。整合关于要分割的形状的统计先验信息可显着改善分割结果。大多数基于形状的分割算法优化了能量函数，并找到了要分割的对象的点估计。这并没有提供对结果信心程度的度量，也没有提供基于数据和先验的其他可能解决方案的图片。从统计角度来看，解决这些问题将涉及表征要分割的对象的形状的后密度的问题。对于这种表征，我们提出了一种基于马尔可夫链蒙特卡洛（MCMC）采样的图像分割算法，该算法使用统计形状先验。除了更好地表征问题的统计结构之外，这种方法还有可能解决现有的基于形状的分割方法所遭遇的局部最优化问题。我们的方法能够通过其样本表征形状空间中的后验概率密度，并且可能从多模概率密度的不同模式返回多个解，这将在例如从多个形状类中分割对象时遇到。我们对各种数据集提出了有希望的结果。我们还提供了一个可以通过独立形状变化来分割对象形状的扩展。该扩展涉及在对象部件上使用局部形状先验，并提供对形状训练数据大小的限制的鲁棒性。

##### URL
[https://arxiv.org/abs/1611.03749](https://arxiv.org/abs/1611.03749)

##### PDF
[https://arxiv.org/pdf/1611.03749](https://arxiv.org/pdf/1611.03749)

