---
layout: post
title: "From Rank Estimation to Rank Approximation: Rank Residual Constraint for Image Denoising"
date: 2018-07-06 17:43:20
categories: arXiv_CV
tags: arXiv_CV Adversarial Sparse GAN Optimization Deep_Learning
author: Zhiyuan Zha, Xin Yuan, Tao Yue, Jiaotao Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by the recent advances of Generative Adversarial Networks (GAN) in deep learning, we propose a novel rank minimization approach, termed rank residual constraint (RRC), for image denoising in the optimization framework. Different from GAN, where a discriminative model is trained jointly with a generative model, in image denoising, since the labels are not available, we build an unsupervised mechanism, where two generative models are employed and jointly optimized. Specifically, by integrating the image nonlocal self-similarity prior with the proposed RRC model, we develop an iterative algorithm for image denoising. We first present a recursive based nonlocal means approach to obtain a good reference of the original image patch groups, and then the rank residual of image patch groups between this reference and the noisy image is minimized to achieve a better estimate of the desired image. In this manner, both the reference and the estimated image in each iteration are improved gradually and jointly; in the meantime, we progressively \emph{approximate} the underlying low-rank matrix (constructed by image patch groups) via minimizing the rank residual, which is different from existing low-rank based approaches that estimate the underlying low-rank matrix directly from the corrupted observation. We further provide a theoretical analysis on the feasibility of the proposed RRC model from the perspective of group-based sparse representation. Experimental results demonstrate that the proposed RRC model outperforms many state-of-the-art denoising methods.

##### Abstract (translated by Google)
受深度学习中生成对抗网络（GAN）的最新进展的启发，我们提出了一种新的秩最小化方法，称为秩残差约束（RRC），用于优化框架中的图像去噪。与GAN不同，其中判别模型与生成模型共同训练，在图像去噪中，由于标签不可用，我们建立了一种无监督机制，其中采用两种生成模型并联合优化。具体地，通过将​​图像非局部自相似性先验与所提出的RRC模型相结合，我们开发了用于图像去噪的迭代算法。我们首先提出基于递归的非局部均值方法以获得原始图像块组的良好参考，然后最小化该参考和噪声图像之间的图像块组的秩残差，以实现对期望图像的更好估计。以这种方式，每次迭代中的参考和估计图像都被逐渐地和共同地改进;与此同时，我们通过最小化秩残差逐步\逼近{近似}基础低秩矩阵（由图像补丁组构建），这与现有的基于低秩的方法不同，后者直接从下面估计潜在的低秩矩阵。腐败的观察。我们从基于群的稀疏表示的角度进一步提供了所提出的RRC模型的可行性的理论分析。实验结果表明，所提出的RRC模型优于许多现有技术的去噪方法。

##### URL
[http://arxiv.org/abs/1807.02504](http://arxiv.org/abs/1807.02504)

##### PDF
[http://arxiv.org/pdf/1807.02504](http://arxiv.org/pdf/1807.02504)

