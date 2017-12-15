---
layout: post
title: "A Gaussian Mixture MRF for Model-Based Iterative Reconstruction with Applications to Low-Dose X-ray CT"
date: 2016-06-13 21:33:07
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Ruoqiao Zhang, Dong Hye Ye, Debashish Pal, Jean-Baptiste Thibault, Ken D. Sauer, Charles A. Bouman
mathjax: true
---

* content
{:toc}

##### Abstract
Markov random fields (MRFs) have been widely used as prior models in various inverse problems such as tomographic reconstruction. While MRFs provide a simple and often effective way to model the spatial dependencies in images, they suffer from the fact that parameter estimation is difficult. In practice, this means that MRFs typically have very simple structure that cannot completely capture the subtle characteristics of complex images. In this paper, we present a novel Gaussian mixture Markov random field model (GM-MRF) that can be used as a very expressive prior model for inverse problems such as denoising and reconstruction. The GM-MRF forms a global image model by merging together individual Gaussian-mixture models (GMMs) for image patches. In addition, we present a novel analytical framework for computing MAP estimates using the GM-MRF prior model through the construction of surrogate functions that result in a sequence of quadratic optimizations. We also introduce a simple but effective method to adjust the GM-MRF so as to control the sharpness in low- and high-contrast regions of the reconstruction separately. We demonstrate the value of the model with experiments including image denoising and low-dose CT reconstruction.

##### Abstract (translated by Google)
马尔可夫随机场（MRF）已被广泛用作各种反演问题的先验模型，如断层重建。虽然MRF提供了一种简单而且经常有效的方法来模拟图像中的空间依赖性，但是它们遭受参数估计困难的事实。实际上，这意味着MRF通常具有非常简单的结构，不能完全捕捉复杂图像的细微特征。在本文中，我们提出了一个新的高斯混合马尔可夫随机场模型（GM-MRF），可以作为一个非常富有表现力的先验模型用于逆问题，如去噪和重构。 GM-MRF通过将用于图像块的各个高斯混合模型（GMM）合并在一起来形成全局图像模型。此外，我们提出了一个新的分析框架，通过构建代理函数，使用GM-MRF先验模型计算MAP估计，从而产生一系列二次优化。我们还介绍了一种简单而有效的方法来调整GM-MRF，从而分别控制重建的低对比度区域和高对比度区域的清晰度。我们用包括图像去噪和低剂量CT重建在内的实验来证明模型的价值。

##### URL
[https://arxiv.org/abs/1605.04006](https://arxiv.org/abs/1605.04006)

##### PDF
[https://arxiv.org/pdf/1605.04006](https://arxiv.org/pdf/1605.04006)

