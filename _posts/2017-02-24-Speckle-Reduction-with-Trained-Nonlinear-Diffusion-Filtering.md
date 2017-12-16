---
layout: post
title: "Speckle Reduction with Trained Nonlinear Diffusion Filtering"
date: 2017-02-24 07:34:31
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: Wensen Feng, Yunjin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Speckle reduction is a prerequisite for many image processing tasks in synthetic aperture radar (SAR) images, as well as all coherent images. In recent years, predominant state-of-the-art approaches for despeckling are usually based on nonlocal methods which mainly concentrate on achieving utmost image restoration quality, with relatively low computational efficiency. Therefore, in this study we aim to propose an efficient despeckling model with both high computational efficiency and high recovery quality. To this end, we exploit a newly-developed trainable nonlinear reaction diffusion(TNRD) framework which has proven a simple and effective model for various image restoration problems. {In the original TNRD applications, the diffusion network is usually derived based on the direct gradient descent scheme. However, this approach will encounter some problem for the task of multiplicative noise reduction exploited in this study. To solve this problem, we employed a new architecture derived from the proximal gradient descent method.} {Taking into account the speckle noise statistics, the diffusion process for the despeckling task is derived. We then retrain all the model parameters in the presence of speckle noise. Finally, optimized nonlinear diffusion filtering models are obtained, which are specialized for despeckling with various noise levels. Experimental results substantiate that the trained filtering models provide comparable or even better results than state-of-the-art nonlocal approaches. Meanwhile, our proposed model merely contains convolution of linear filters with an image, which offers high level parallelism on GPUs. As a consequence, for images of size $512 \times 512$, our GPU implementation takes less than 0.1 seconds to produce state-of-the-art despeckling performance.}

##### Abstract (translated by Google)
散斑减少是合成孔径雷达（SAR）图像中许多图像处理任务以及所有相干图像的先决条件。近年来，主要的最先进的去斑方法通常基于非局部方法，主要集中于实现最大的图像恢复质量，计算效率相对较低。因此，本研究旨在提出一种计算效率高，恢复质量高的高效去斑模型。为此，我们开发了一种新开发的可训练的非线性反应扩散（TNRD）框架，该框架证明了一个简单而有效的模型用于各种图像恢复问题。 {在最初的TNRD应用中，扩散网络通常是基于直接梯度下降方案。然而，这种方法将会遇到一些问题，在本研究中利用乘法降噪的任务。为了解决这个问题，我们采用了一种新的从近端梯度下降法得到的结构。} {考虑到散斑噪声统计，推导了散斑任务的扩散过程。然后，我们重新训练所有的模型参数在斑点噪声的存在。最后，得到了优化的非线性扩散滤波模型，专门用于各种噪声水平的去斑。实验结果证明，训练的过滤模型比现有技术的非局部方法提供可比较的甚至更好的结果。同时，我们提出的模型仅仅包含线性滤波器和图像的卷积，在GPU上提供高水​​平的并行性。因此，对于尺寸为$ 512 \ times 512 $的图像，我们的GPU实现不到0.1秒即可产生最新的去斑效果。

##### URL
[https://arxiv.org/abs/1702.07482](https://arxiv.org/abs/1702.07482)

##### PDF
[https://arxiv.org/pdf/1702.07482](https://arxiv.org/pdf/1702.07482)

