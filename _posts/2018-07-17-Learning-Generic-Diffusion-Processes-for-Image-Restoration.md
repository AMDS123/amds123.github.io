---
layout: post
title: "Learning Generic Diffusion Processes for Image Restoration"
date: 2018-07-17 04:21:29
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Peng Qiao, Yong Dou, Yunjin Chen, Wensen Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Image restoration problems are typical ill-posed problems where the regularization term plays an important role. The regularization term learned via generative approaches is easy to transfer to various image restoration, but offers inferior restoration quality compared with that learned via discriminative approaches. On the contrary, the regularization term learned via discriminative approaches are usually trained for a specific image restoration problem, and fail in the problem for which it is not trained. To address this issue, we propose a generic diffusion process (genericDP) to handle multiple Gaussian denoising problems based on the Trainable Non-linear Reaction Diffusion (TNRD) models. Instead of one model, which consists of a diffusion and a reaction term, for one Gaussian denoising problem in TNRD, we enforce multiple TNRD models to share one diffusion term. The trained genericDP model can provide both promising denoising performance and high training efficiency compared with the original TNRD models. We also transfer the trained diffusion term to non-blind deconvolution which is unseen in the training phase. Experiment results show that the trained diffusion term for multiple Gaussian denoising can be transferred to image non-blind deconvolution as an image prior and provide competitive performance.

##### Abstract (translated by Google)
图像恢复问题是典型的不适定问题，其中正则化项起着重要作用。通过生成方法学习的正则化术语很容易转移到各种图像恢复，但与通过判别方法学习的相比，提供较差的恢复质量。相反，通过判别方法学习的正则化术语通常针对特定的图像恢复问题进行训练，并且在未训练的问题中失败。为了解决这个问题，我们提出了一种通用扩散过程（genericDP）来处理基于可训练非线性反应扩散（TNRD）模型的多个高斯去噪问题。对于TNRD中的一个高斯去噪问题，我们强制使用多个TNRD模型来共享一个扩散项，而不是一个由扩散和反应项组成的模型。与原始TNRD模型相比，训练有素的genericDP模型可以提供有前途的去噪性能和高训练效率。我们还将训练好的扩散项转移到非盲去卷积，这在训练阶段是看不到的。实验结果表明，经过训练的多高斯去噪扩散项可以作为图像先验转移到图像非盲去卷积，并提供有竞争力的性能。

##### URL
[http://arxiv.org/abs/1807.06216](http://arxiv.org/abs/1807.06216)

##### PDF
[http://arxiv.org/pdf/1807.06216](http://arxiv.org/pdf/1807.06216)

