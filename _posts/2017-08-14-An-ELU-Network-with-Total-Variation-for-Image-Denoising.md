---
layout: post
title: "An ELU Network with Total Variation for Image Denoising"
date: 2017-08-14 20:47:35
categories: arXiv_CV
tags: arXiv_CV CNN
author: Tianyang Wang, Zhengrui Qin, Michelle Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel convolutional neural network (CNN) for image denoising, which uses exponential linear unit (ELU) as the activation function. We investigate the suitability by analyzing ELU's connection with trainable nonlinear reaction diffusion model (TNRD) and residual denoising. On the other hand, batch normalization (BN) is indispensable for residual denoising and convergence purpose. However, direct stacking of BN and ELU degrades the performance of CNN. To mitigate this issue, we design an innovative combination of activation layer and normalization layer to exploit and leverage the ELU network, and discuss the corresponding rationale. Moreover, inspired by the fact that minimizing total variation (TV) can be applied to image denoising, we propose a TV regularized L2 loss to evaluate the training effect during the iterations. Finally, we conduct extensive experiments, showing that our model outperforms some recent and popular approaches on Gaussian denoising with specific or randomized noise levels for both gray and color images.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的用于图像去噪的卷积神经网络（CNN），它使用指数线性单元（ELU）作为激活函数。我们通过分析ELU与可训练非线性反应扩散模型（TNRD）和残余去噪的联系来研究适用性。另一方面，批量归一化（BN）是残差去噪和汇聚目的所不可或缺的。然而，BN和ELU的直接堆叠降低了CNN的性能。为了缓解这个问题，我们设计了激活层和规范化层的创新组合来利用和利用ELU网络，并讨论相应的基本原理。此外，从最小化总变差（TV）可应用于图像去噪的角度出发，我们提出了一个TV正则化的L2损失评估迭代过程中的训练效果。最后，我们进行了大量的实验，表明我们的模型比灰度和彩色图像具有特定或随机噪声水平的高斯去噪方法优于最近的和普遍使用的方法。

##### URL
[https://arxiv.org/abs/1708.04317](https://arxiv.org/abs/1708.04317)

##### PDF
[https://arxiv.org/pdf/1708.04317](https://arxiv.org/pdf/1708.04317)

