---
layout: post
title: "Class-specific image denoising using importance sampling"
date: 2017-06-21 14:11:29
categories: arXiv_CV
tags: arXiv_CV Face
author: Milad Niknejad, Jose M. Bioucas-Dias, Mario A. T. Figueiredo
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new image denoising method, tailored to specific classes of images, assuming that a dataset of clean images of the same class is available. Similarly to the non-local means (NLM) algorithm, the proposed method computes a weighted average of non-local patches, which we interpret under the importance sampling framework. This viewpoint introduces flexibility regarding the adopted priors, the noise statistics, and the computation of Bayesian estimates. The importance sampling viewpoint is exploited to approximate the minimum mean squared error (MMSE) patch estimates, using the true underlying prior on image patches. The estimates thus obtained converge to the true MMSE estimates, as the number of samples approaches infinity. Experimental results provide evidence that the proposed denoiser outperforms the state-of-the-art in the specific classes of face and text images.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的图像去噪方法，针对特定类别的图像，假设同一类的干净图像的数据集可用。与非局部均值（NLM）算法类似，所提出的方法计算非局部斑块的加权平均值，这是我们在重要性抽样框架下解释的。这个观点为采用的先验，噪声统计和贝叶斯估计的计算带来了灵活性。利用重要性抽样视点来逼近最小均方误差（MMSE）片段估计，使用图像片上的真正基础先验。随着样本数量接近无限，这样得到的估计收敛于真实的MMSE估计值。实验结果提供了证据表明，提出的去噪器在特定类别的面部和文本图像中的性能优于现有技术。

##### URL
[https://arxiv.org/abs/1706.06917](https://arxiv.org/abs/1706.06917)

##### PDF
[https://arxiv.org/pdf/1706.06917](https://arxiv.org/pdf/1706.06917)

