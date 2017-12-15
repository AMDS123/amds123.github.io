---
layout: post
title: "Trainable Nonlinear Reaction Diffusion: A Flexible Framework for Fast and Effective Image Restoration"
date: 2016-08-20 04:48:54
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Inference
author: Yunjin Chen, Thomas Pock
mathjax: true
---

* content
{:toc}

##### Abstract
Image restoration is a long-standing problem in low-level computer vision with many interesting applications. We describe a flexible learning framework based on the concept of nonlinear reaction diffusion models for various image restoration problems. By embodying recent improvements in nonlinear diffusion models, we propose a dynamic nonlinear reaction diffusion model with time-dependent parameters (\ie, linear filters and influence functions). In contrast to previous nonlinear diffusion models, all the parameters, including the filters and the influence functions, are simultaneously learned from training data through a loss based approach. We call this approach TNRD -- \textit{Trainable Nonlinear Reaction Diffusion}. The TNRD approach is applicable for a variety of image restoration tasks by incorporating appropriate reaction force. We demonstrate its capabilities with three representative applications, Gaussian image denoising, single image super resolution and JPEG deblocking. Experiments show that our trained nonlinear diffusion models largely benefit from the training of the parameters and finally lead to the best reported performance on common test datasets for the tested applications. Our trained models preserve the structural simplicity of diffusion models and take only a small number of diffusion steps, thus are highly efficient. Moreover, they are also well-suited for parallel computation on GPUs, which makes the inference procedure extremely fast.

##### Abstract (translated by Google)
图像恢复是低级计算机视觉中一个长期存在的问题，有许多有趣的应用。我们描述了一个灵活的学习框架，基于非线性反应扩散模型的概念，为各种图像恢复问题。通过体现最近在非线性扩散模型中的改进，我们提出了一个具有时间相关参数（即线性滤波器和影响函数）的动态非线性反应扩散模型。与之前的非线性扩散模型相比，包括滤波器和影响函数在内的所有参数都是通过基于损失的方法同时从训练数据中获得的。我们称之为TNRD  -  \ textit {可训练的非线性反应扩散}。 TNRD方法适用于通过合适的反作用力进行各种图像恢复任务。我们用三个代表性的应用，高斯图像去噪，单图像超分辨率和JPEG去块技术展示了它的能力。实验表明，我们的训练非线性扩散模型很大程度上受益于参数的训练，并最终导致测试应用程序的常见测试数据集上报告的最佳性能。我们的训练模型保留了扩散模型的结构简单性，只需要少量的扩散步骤，因此非常高效。而且，它们也非常适合GPU上的并行计算，这使得推理过程非常快速。

##### URL
[https://arxiv.org/abs/1508.02848](https://arxiv.org/abs/1508.02848)

##### PDF
[https://arxiv.org/pdf/1508.02848](https://arxiv.org/pdf/1508.02848)

