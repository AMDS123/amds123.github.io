---
layout: post
title: "GP-GAN: Towards Realistic High-Resolution Image Blending"
date: 2017-03-25 12:37:34
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN
author: Huikai Wu, Shuai Zheng, Junge Zhang, Kaiqi Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in generative adversarial networks (GANs) have shown promising potentials in conditional image generation. However, how to generate high-resolution images remains an open problem. In this paper, we aim at generating high-resolution well-blended images given composited copy-and-paste ones, i.e. realistic high-resolution image blending. To achieve this goal, we propose Gaussian-Poisson GAN (GP-GAN), a framework that combines the strengths of classical gradient-based approaches and GANs, which is the first work that explores the capability of GANs in high-resolution image blending task to the best of our knowledge. Particularly, we propose Gaussian-Poisson Equation to formulate the high-resolution image blending problem, which is a joint optimisation constrained by the gradient and colour information. Gradient filters can obtain gradient information. For generating the colour information, we propose Blending GAN to learn the mapping between the composited image and the well-blended one. Compared to the alternative methods, our approach can deliver high-resolution, realistic images with fewer bleedings and unpleasant artefacts. Experiments confirm that our approach achieves the state-of-the-art performance on Transient Attributes dataset. A user study on Amazon Mechanical Turk finds that majority of workers are in favour of the proposed approach.

##### Abstract (translated by Google)
生成对抗网络（GAN）的最新进展显示出有前景的条件图像生成的潜力。但是，如何生成高分辨率的图像仍然是一个悬而未决的问题。在本文中，我们的目标是生成高分辨率的混合图像，给出合成的复制和粘贴图像，即逼真的高分辨率图像混合。为了实现这一目标，我们提出了一个高斯 - 泊松GAN（GP-GAN）框架，该框架结合了经典的基于梯度的方法和GAN的优点，这是第一个研究GAN在高分辨率图像混合任务尽我们所知。特别地，我们提出了高斯 - 泊松方程来拟合高分辨率图像融合问题，这是一种由梯度和颜色信息约束的联合优化问题。渐变滤镜可以获取渐变信息。为了生成颜色信息，我们建议混合GAN来学习合成图像和混合图像之间的映射。与其他方法相比，我们的方法可以提供高分辨率，逼真的图像，更少的出血和不愉快的人工制品。实验证实，我们的方法在瞬态属性数据集上实现了最先进的性能。亚马逊Mechanical Turk的一项用户调查发现，大多数工人都赞成所提出的方法。

##### URL
[https://arxiv.org/abs/1703.07195](https://arxiv.org/abs/1703.07195)

##### PDF
[https://arxiv.org/pdf/1703.07195](https://arxiv.org/pdf/1703.07195)

