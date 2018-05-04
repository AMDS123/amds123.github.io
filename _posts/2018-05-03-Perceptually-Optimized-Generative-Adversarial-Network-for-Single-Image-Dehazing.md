---
layout: post
title: "Perceptually Optimized Generative Adversarial Network for Single Image Dehazing"
date: 2018-05-03 02:00:33
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization Deep_Learning
author: Yixin Du, Xin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Existing approaches towards single image dehazing including both model-based and learning-based heavily rely on the estimation of so-called transmission maps. Despite its conceptual simplicity, using transmission maps as an intermediate step often makes it more difficult to optimize the perceptual quality of reconstructed images. To overcome this weakness, we propose a direct deep learning approach toward image dehazing bypassing the step of transmission map estimation and facilitating end-to-end perceptual optimization. Our technical contributions are mainly three-fold. First, based on the analogy between dehazing and denoising, we propose to directly learn a nonlinear mapping from the space of degraded images to that of haze-free ones via recursive deep residual learning; Second, inspired by the success of generative adversarial networks (GAN), we propose to optimize the perceptual quality of dehazed images by introducing a discriminator and a loss function adaptive to hazy conditions; Third, we propose to remove notorious halo-like artifacts at large scene depth discontinuities by a novel application of guided filtering. Extensive experimental results have shown that the subjective qualities of dehazed images by the proposed perceptually optimized GAN (POGAN) are often more favorable than those by existing state-of-the-art approaches especially when hazy condition varies.

##### Abstract (translated by Google)
包括基于模型和基于学习的单一图像去雾的现有方法严重依赖于对所谓的透射图的估计。尽管概念简单，但使用传输图作为中间步骤通常会使重建图像的感知质量优化变得更加困难。为了克服这个弱点，我们提出了一种直接的图像去雾的深度学习方法，绕过了传输图估计的步骤，并促进了端到端的感知优化。我们的技术贡献主要有三重。首先，基于去雾和去噪之间的类比，我们提出通过递归深度残差学习直接学习从退化图像空间到无雾图像空间的非线性映射;其次，受到生成对抗网络（GAN）的成功启发，我们提出通过引入适用于模糊条件的鉴别器和损失函数来优化去雾图像的感知质量;第三，我们建议通过引导滤波的新颖应用去除在大场景深度不连续处出现臭名昭着的类晕现象。广泛的实验结果表明，所提出的感知优化的GAN（POGAN）所提供的去雾图像的主观质量通常比现有技术方法更有利，特别是当模糊条件变化时。

##### URL
[http://arxiv.org/abs/1805.01084](http://arxiv.org/abs/1805.01084)

##### PDF
[http://arxiv.org/pdf/1805.01084](http://arxiv.org/pdf/1805.01084)

