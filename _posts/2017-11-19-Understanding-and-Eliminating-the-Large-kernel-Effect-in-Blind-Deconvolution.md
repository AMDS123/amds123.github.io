---
layout: post
title: "Understanding and Eliminating the Large-kernel Effect in Blind Deconvolution"
date: 2017-11-19 16:10:03
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge Optimization
author: Li Si-Yao, Qian Yin, Ping Guo
mathjax: true
---

* content
{:toc}

##### Abstract
Blind deconvolution consists of recovering a clear version of an observed blurry image without specific knowledge of the degradation kernel. The kernel size, however, is a required hyper-parameter that defines the range of the support domain. In this study, we experimentally and theoretically show how large kernel sizes introduce noises to expected zeros in the kernel and yield inferior results. We explain this effect by demonstrating that sizeable kernels lower the squares cost in optimization. We also prove that this effect persists with a probability of one for noisy images. Using 1D simulation, we quantify the increment of error of estimated kernel with its size. To eliminate this effect, we propose a low-rank based penalty that reflects structural information of the kernel. Compared to the generic $\ell_\alpha$, our penalty can respond to even a small amount of random noise in the kernel. Our regularization reduces the noise and efficiently enhances the success rate of large kernel sizes. We also compare our method to state-of-art approaches and test it using real-world images.

##### Abstract (translated by Google)
盲解卷积包括恢复观察到的模糊图像的清晰版本，而没有降级内核的特定知识。但是，内核大小是定义支持域范围所需的超参数。在这个研究中，我们通过实验和理论的方式展示了大的内核大小如何给内核中的期望的零点带来噪声，并且产生较差的结果。我们通过证明大的内核在优化中降低平方成本来解释这个影响。我们还证明，对于噪声图像，这种效果持续一个概率。使用一维模拟，我们量化估计核的误差增量与其大小。为了消除这种影响，我们提出一个反映内核结构信息的基于低秩的惩罚。与通用的$ \ ell_ \ alpha $相比，我们的惩罚可以响应内核中的一小部分随机噪声。我们的正则化降低了噪音，有效地提高了大粒径的成功率。我们还将我们的方法与最先进的方法进行比较，并使用真实世界的图像进行测试。

##### URL
[https://arxiv.org/abs/1706.01797](https://arxiv.org/abs/1706.01797)

##### PDF
[https://arxiv.org/pdf/1706.01797](https://arxiv.org/pdf/1706.01797)

