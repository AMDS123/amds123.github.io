---
layout: post
title: "Multispectral image denoising with optimized vector non-local mean filter"
date: 2016-10-21 07:34:57
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Ahmed Ben Said, Rachid Hadjidj, Kamel Eddine Melkemi, Sebti Foufou
mathjax: true
---

* content
{:toc}

##### Abstract
Nowadays, many applications rely on images of high quality to ensure good performance in conducting their tasks. However, noise goes against this objective as it is an unavoidable issue in most applications. Therefore, it is essential to develop techniques to attenuate the impact of noise, while maintaining the integrity of relevant information in images. We propose in this work to extend the application of the Non-Local Means filter (NLM) to the vector case and apply it for denoising multispectral images. The objective is to benefit from the additional information brought by multispectral imaging systems. The NLM filter exploits the redundancy of information in an image to remove noise. A restored pixel is a weighted average of all pixels in the image. In our contribution, we propose an optimization framework where we dynamically fine tune the NLM filter parameters and attenuate its computational complexity by considering only pixels which are most similar to each other in computing a restored pixel. Filter parameters are optimized using Stein's Unbiased Risk Estimator (SURE) rather than using ad hoc means. Experiments have been conducted on multispectral images corrupted with additive white Gaussian noise and PSNR and similarity comparison with other approaches are provided to illustrate the efficiency of our approach in terms of both denoising performance and computation complexity.

##### Abstract (translated by Google)
如今，许多应用程序依靠高质量的图像来确保执行任务的良好性能。但是，噪音违背了这个目标，因为这在大多数应用中是不可避免的问题。因此，开发减少噪声影响的技术是十分必要的，同时保持图像中相关信息的完整性。我们在这项工作中提出将非局部均值滤波器（NLM）的应用扩展到矢量情况，并将其应用于去噪多光谱图像。目标是从多光谱成像系统带来的附加信息中受益。 NLM滤波器利用图像中信息的冗余来消除噪声。恢复的像素是图像中所有像素的加权平均值。在我们的贡献中，我们提出了一个优化框架，我们动态地微调NLM滤波器参数，并通过仅考虑在计算恢复的像素时彼此最相似的像素来减弱其计算复杂度。滤波器参数使用Stein的无偏风险评估器（SURE）进行优化，而不是使用临时手段。对加性高斯白噪声和PSNR的多光谱图像进行了实验，并与其他方法进行了相似性比较，以说明本文方法在降噪性能和计算复杂度方面的有效性。

##### URL
[https://arxiv.org/abs/1610.06688](https://arxiv.org/abs/1610.06688)

##### PDF
[https://arxiv.org/pdf/1610.06688](https://arxiv.org/pdf/1610.06688)

