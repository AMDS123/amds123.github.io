---
layout: post
title: "Amortised MAP Inference for Image Super-resolution"
date: 2017-02-21 13:08:24
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN CNN Inference
author: Casper Kaae Sønderby, Jose Caballero, Lucas Theis, Wenzhe Shi, Ferenc Huszár
mathjax: true
---

* content
{:toc}

##### Abstract
Image super-resolution (SR) is an underdetermined inverse problem, where a large number of plausible high-resolution images can explain the same downsampled image. Most current single image SR methods use empirical risk minimisation, often with a pixel-wise mean squared error (MSE) loss. However, the outputs from such methods tend to be blurry, over-smoothed and generally appear implausible. A more desirable approach would employ Maximum a Posteriori (MAP) inference, preferring solutions that always have a high probability under the image prior, and thus appear more plausible. Direct MAP estimation for SR is non-trivial, as it requires us to build a model for the image prior from samples. Furthermore, MAP inference is often performed via optimisation-based iterative algorithms which don't compare well with the efficiency of neural-network-based alternatives. Here we introduce new methods for amortised MAP inference whereby we calculate the MAP estimate directly using a convolutional neural network. We first introduce a novel neural network architecture that performs a projection to the affine subspace of valid SR solutions ensuring that the high resolution output of the network is always consistent with the low resolution input. We show that, using this architecture, the amortised MAP inference problem reduces to minimising the cross-entropy between two distributions, similar to training generative models. We propose three methods to solve this optimisation problem: (1) Generative Adversarial Networks (GAN) (2) denoiser-guided SR which backpropagates gradient-estimates from denoising to train the network, and (3) a baseline method using a maximum-likelihood-trained image prior. Our experiments show that the GAN based approach performs best on real image data. Lastly, we establish a connection between GANs and amortised variational inference as in e.g. variational autoencoders.

##### Abstract (translated by Google)
图像超分辨率（SR）是欠定的反演问题，其中大量合理的高分辨率图像可以解释相同的下采样图像。大多数当前的单幅图像SR方法使用经验风险最小化，通常具有像素方均误差（MSE）损失。然而，这些方法的输出往往是模糊的，过度平滑的，而且通常看起来不合理。更理想的方法将采用最大后验（MAP）推断，更喜欢在图像之前总是具有高概率的解决方案，因此似乎更合理。 SR的直接MAP估计是非平凡的，因为它要求我们在样本之前为图像建立一个模型。此外，MAP推理通常通过基于优化的迭代算法来执行，这与基于神经网络的替代方案的效率不能很好地相比。在这里，我们介绍一种新的分期付款的MAP推断方法，我们直接使用卷积神经网络来计算MAP估计。我们首先介绍一种新的神经网络架构，对有效的SR解决方案的仿射子空间进行投影，确保网络的高分辨率输出始终与低分辨率输入保持一致。我们证明，使用这种架构，摊销MAP推理问题减少到最小化两个分布之间的交叉熵，类似于训练生成模型。我们提出了三种方法来解决这个优化问题：（1）生成对抗网络（GAN）（2）降噪器引导的SR反向传播梯度估计从消噪到训练网络，和（3）基线方法使用最大似然之前训练的图像。我们的实验表明，基于GAN的方法在实际图像数据上表现最好。最后，我们建立了GAN和摊销变分推理之间的联系，例如，变分自动编码器。

##### URL
[https://arxiv.org/abs/1610.04490](https://arxiv.org/abs/1610.04490)

##### PDF
[https://arxiv.org/pdf/1610.04490](https://arxiv.org/pdf/1610.04490)

