---
layout: post
title: "Blind Image Denoising via Dependent Dirichlet Process Tree"
date: 2016-01-13 02:44:36
categories: arXiv_CV
tags: arXiv_CV Inference
author: Fengyuan Zhu, Guangyong Chen, Jianye Hao, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing image denoising approaches assumed the noise to be homogeneous white Gaussian distributed with known intensity. However, in real noisy images, the noise models are usually unknown beforehand and can be much more complex. This paper addresses this problem and proposes a novel blind image denoising algorithm to recover the clean image from noisy one with the unknown noise model. To model the empirical noise of an image, our method introduces the mixture of Gaussian distribution, which is flexible enough to approximate different continuous distributions. The problem of blind image denoising is reformulated as a learning problem. The procedure is to first build a two-layer structural model for noisy patches and consider the clean ones as latent variable. To control the complexity of the noisy patch model, this work proposes a novel Bayesian nonparametric prior called "Dependent Dirichlet Process Tree" to build the model. Then, this study derives a variational inference algorithm to estimate model parameters and recover clean patches. We apply our method on synthesis and real noisy images with different noise models. Comparing with previous approaches, ours achieves better performance. The experimental results indicate the efficiency of the proposed algorithm to cope with practical image denoising tasks.

##### Abstract (translated by Google)
大多数现有的图像去噪方法都假设噪声是均匀的高斯分布，具有已知的强度。然而，在真实的噪声图像中，噪声模型通常是事先未知的，并且可能更为复杂。本文针对这一问题，提出了一种新的盲噪图像去噪算法，利用未知噪声模型从噪声图像中恢复出干净的图像。为了模拟图像的经验噪声，我们的方法引入了高斯分布的混合，其足够灵活以近似不同的连续分布。盲目去噪的问题被重新表述为学习问题。程序是首先建立一个噪声补丁的两层结构模型，并考虑干净的潜在变量。为了控制噪声补丁模型的复杂性，本文提出了一种新的贝叶斯非参数先验的“Dependent Dirichlet Process Tree”来建立模型。然后，本文推导了一种变分推理算法来估计模型参数，并恢复清洁块。我们将我们的方法应用于合成和具有不同噪声模型的真实噪声图像。与以前的方法相比，我们的性能更好。实验结果表明了该算法的有效性，以应付实际的图像去噪任务。

##### URL
[https://arxiv.org/abs/1601.03117](https://arxiv.org/abs/1601.03117)

##### PDF
[https://arxiv.org/pdf/1601.03117](https://arxiv.org/pdf/1601.03117)

