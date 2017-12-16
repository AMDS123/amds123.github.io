---
layout: post
title: "Artifact reduction for separable non-local means"
date: 2017-10-26 06:05:06
categories: arXiv_CV
tags: arXiv_CV
author: Sanjay Ghosh, Kunal N. Chaudhury
mathjax: true
---

* content
{:toc}

##### Abstract
It was recently demonstrated [J. Electron. Imaging, 25(2), 2016] that one can perform fast non-local means (NLM) denoising of one-dimensional signals using a method called lifting. The cost of lifting is independent of the patch length, which dramatically reduces the run-time for large patches. Unfortunately, it is difficult to directly extend lifting for non-local means denoising of images. To bypass this, the authors proposed a separable approximation in which the image rows and columns are filtered using lifting. The overall algorithm is significantly faster than NLM, and the results are comparable in terms of PSNR. However, the separable processing often produces vertical and horizontal stripes in the image. This problem was previously addressed by using a bilateral filter-based post-smoothing, which was effective in removing some of the stripes. In this letter, we demonstrate that stripes can be mitigated in the first place simply by involving the neighboring rows (or columns) in the filtering. In other words, we use a two-dimensional search (similar to NLM), while still using one-dimensional patches (as in the previous proposal). The novelty is in the observation that one can use lifting for performing two-dimensional searches. The proposed approach produces artifact-free images, whose quality and PSNR are comparable to NLM, while being significantly faster.

##### Abstract (translated by Google)
最近证明[J.电子。成像，25（2），2016]可以使用称为提升的方法对一维信号执行快速非局部均值（NLM）去噪。提升的成本与贴片长度无关，这大大减少了大贴片的运行时间。不幸的是，直接扩展非局部图像去噪是很困难的。为了绕过这一点，作者提出了一种可分离的近似方法，其中图像行和列使用提升进行滤波。整体算法比NLM快得多，并且结果在PSNR方面是可比较的。但是，可分离的处理常常在图像中产生垂直和水平的条纹。以前通过使用基于双边滤波器的后平滑处理解决了这个问题，这对于去除一些条纹是有效的。在这封信中，我们证明条纹可以通过在过滤中包含相邻行（或列）来简化。换句话说，我们使用二维搜索（类似于NLM），同时仍然使用一维补丁（如前面的提议）。新颖之处在于可以使用提升进行二维搜索的观察。所提出的方法产生无伪像的图像，其质量和PSNR与NLM相当，而显着更快。

##### URL
[https://arxiv.org/abs/1710.09552](https://arxiv.org/abs/1710.09552)

##### PDF
[https://arxiv.org/pdf/1710.09552](https://arxiv.org/pdf/1710.09552)

