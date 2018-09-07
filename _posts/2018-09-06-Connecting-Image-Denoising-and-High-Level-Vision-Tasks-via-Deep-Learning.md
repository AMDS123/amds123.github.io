---
layout: post
title: "Connecting Image Denoising and High-Level Vision Tasks via Deep Learning"
date: 2018-09-06 05:13:22
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Ding Liu, Bihan Wen, Jianbo Jiao, Xianming Liu, Zhangyang Wang, Thomas S. Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Image denoising and high-level vision tasks are usually handled independently in the conventional practice of computer vision, and their connection is fragile. In this paper, we cope with the two jointly and explore the mutual influence between them with the focus on two questions, namely (1) how image denoising can help improving high-level vision tasks, and (2) how the semantic information from high-level vision tasks can be used to guide image denoising. First for image denoising we propose a convolutional neural network in which convolutions are conducted in various spatial resolutions via downsampling and upsampling operations in order to fuse and exploit contextual information on different scales. Second we propose a deep neural network solution that cascades two modules for image denoising and various high-level tasks, respectively, and use the joint loss for updating only the denoising network via back-propagation. We experimentally show that on one hand, the proposed denoiser has the generality to overcome the performance degradation of different high-level vision tasks. On the other hand, with the guidance of high-level vision information, the denoising network produces more visually appealing results. Extensive experiments demonstrate the benefit of exploiting image semantics simultaneously for image denoising and high-level vision tasks via deep learning. The code is available online: https://github.com/Ding-Liu/DeepDenoising

##### Abstract (translated by Google)
图像去噪和高级视觉任务通常在计算机视觉的传统实践中独立处理，并且它们的连接是脆弱的。在本文中，我们共同应对这两者，探讨它们之间的相互影响，重点关注两个问题，即（1）图像去噪如何帮助改善高​​级视觉任务，以及（2）语义信息如何从高处获得级别视觉任务可用于指导图像去噪。首先，对于图像去噪，我们提出了一种卷积神经网络，其中通过下采样和上采样操作在各种空间分辨率下进行卷积，以融合和利用不同尺度的上下文信息。其次，我们提出了一种深度神经网络解决方案，它将两个模块分别级联用于图像去噪和各种高级任务，并使用联合损耗通过反向传播仅更新去噪网络。我们通过实验证明，一方面，所提出的降噪器具有克服不同高级视觉任务的性能退化的一般性。另一方面，在高级视觉信息的指导下，去噪网络产生更具视觉吸引力的结果。大量实验证明了通过深度学习同时利用图像语义进行图像去噪和高级视觉任务的好处。该代码可在线获取：https：//github.com/Ding-Liu/DeepDenoising

##### URL
[http://arxiv.org/abs/1809.01826](http://arxiv.org/abs/1809.01826)

##### PDF
[http://arxiv.org/pdf/1809.01826](http://arxiv.org/pdf/1809.01826)

