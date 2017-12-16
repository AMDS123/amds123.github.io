---
layout: post
title: "Image Denoising via Multi-scale Nonlinear Diffusion Models"
date: 2016-09-21 14:42:47
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention
author: Wensen Feng, Peng Qiao, Xuanyang Xi, Yunjin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Image denoising is a fundamental operation in image processing and holds considerable practical importance for various real-world applications. Arguably several thousands of papers are dedicated to image denoising. In the past decade, sate-of-the-art denoising algorithm have been clearly dominated by non-local patch-based methods, which explicitly exploit patch self-similarity within image. However, in recent two years, discriminatively trained local approaches have started to outperform previous non-local models and have been attracting increasing attentions due to the additional advantage of computational efficiency. Successful approaches include cascade of shrinkage fields (CSF) and trainable nonlinear reaction diffusion (TNRD). These two methods are built on filter response of linear filters of small size using feed forward architectures. Due to the locality inherent in local approaches, the CSF and TNRD model become less effective when noise level is high and consequently introduces some noise artifacts. In order to overcome this problem, in this paper we introduce a multi-scale strategy. To be specific, we build on our newly-developed TNRD model, adopting the multi-scale pyramid image representation to devise a multi-scale nonlinear diffusion process. As expected, all the parameters in the proposed multi-scale diffusion model, including the filters and the influence functions across scales, are learned from training data through a loss based approach. Numerical results on Gaussian and Poisson denoising substantiate that the exploited multi-scale strategy can successfully boost the performance of the original TNRD model with single scale. As a consequence, the resulting multi-scale diffusion models can significantly suppress the typical incorrect features for those noisy images with heavy noise.

##### Abstract (translated by Google)
图像去噪是图像处理中的一项基本操作，对于各种实际应用具有相当重要的实际意义。可以说数以千计的论文是致力于图像去噪。在过去的十年中，最先进的去噪算法已经明显地被非局部基于块的方法所主导，其明确地利用了图像内的块自相似性。然而，最近两年，差异训练的局部方法已经开始超越以前的非局部模型，并且由于计算效率的附加优势已经引起越来越多的关注。成功的方法包括级联收缩场（CSF）和可训练的非线性反应扩散（TNRD）。这两种方法建立在使用前馈体系结构的小尺寸线性滤波器的滤波器响应上。由于局部方法固有的局部性，当噪声水平高时，CSF和TNRD模型变得不那么有效，并且因此引入一些噪声伪像。为了克服这个问题，本文介绍了一个多尺度策略。具体来说，我们在我们新开发的TNRD模型的基础上，采用多尺度金字塔图像表示来设计多尺度非线性扩散过程。如预期的那样，所提出的多尺度扩散模型中的所有参数，包括过滤器和跨尺度的影响函数，都是通过基于损失的方法从训练数据中学习的。高斯和泊松去噪的数值结果证明，开发的多尺度策略能够成功地提高原始单尺度TNRD模型的性能。结果，由此产生的多尺度扩散模型可以显着地抑制噪声较大的噪声图像的典型不正确特征。

##### URL
[https://arxiv.org/abs/1609.06585](https://arxiv.org/abs/1609.06585)

##### PDF
[https://arxiv.org/pdf/1609.06585](https://arxiv.org/pdf/1609.06585)

