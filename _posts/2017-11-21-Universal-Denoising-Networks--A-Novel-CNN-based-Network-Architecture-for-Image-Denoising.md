---
layout: post
title: "Universal Denoising Networks : A Novel CNN-based Network Architecture for Image Denoising"
date: 2017-11-21 14:36:14
categories: arXiv_CV
tags: arXiv_CV CNN
author: Stamatios Lefkimmiatis
mathjax: true
---

* content
{:toc}

##### Abstract
We design a novel network architecture for learning discriminative image models that are employed to efficiently tackle the problem of grayscale and color image denoising. Based on the proposed architecture, we introduce two different variants. The first network involves convolutional layers as a core component, while the second one relies instead on non-local filtering layers and thus it is able to exploit the inherent non-local self-similarity property of natural images. As opposed to most of the existing neural networks, which require the training of a specific model for each considered noise level, the proposed networks are able to handle a wide range of different noise levels, while they are very robust when the noise degrading the latent image does not match the statistics of the one used during training. The latter argument is supported by results that we report on publicly available images corrupted by unknown noise and which we compare against solutions obtained by alternative state-of-the-art methods. At the same time the introduced networks achieve excellent results under additive white Gaussian noise (AWGN), which are comparable to the current state-of-the-art network, while they depend on a more shallow architecture with the number of trained parameters being one order of magnitude smaller. These properties make the proposed networks ideal candidates to serve as sub-solvers on restoration methods that deal with general inverse imaging problems such as deblurring, demosaicking, superresolution, etc.

##### Abstract (translated by Google)
我们设计了一种新颖的网络结构，用于学习有效解决灰度和彩色图像去噪问题的辨别图像模型。基于所提出的体系结构，我们介绍两种不同的变体。第一个网络以卷积层为核心，第二个网络依靠非局部过滤层，因此能够利用自然图像的固有非局部自相似性。与大多数现有的需要针对每个考虑的噪声水平训练特定模型的神经网络相反，所提出的网络能够处理各种不同的噪声水平，而当噪声降低潜在噪声图像与训练期间使用的统计数据不匹配。后一种观点得到了以下结果的支持：我们报告了公众可获得的图像受到未知噪声破坏的影响，并将其与通过替代的最新方法获得的解决方案进行比较。同时，引入的网络在加性高斯白噪声（AWGN）下可以达到很好的效果，这与当前最先进的网络是可比的，而它们依赖于更浅的结构，训练参数的数量是一个数量级更小。这些性质使得所提出的网络成为理想的候选者，可以作为处理一般逆向成像问题（例如去模糊，去马赛克，超分辨率等）的修复方法的子解算器。

##### URL
[https://arxiv.org/abs/1711.07807](https://arxiv.org/abs/1711.07807)

##### PDF
[https://arxiv.org/pdf/1711.07807](https://arxiv.org/pdf/1711.07807)

