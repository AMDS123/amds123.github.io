---
layout: post
title: "Accelerating the Super-Resolution Convolutional Neural Network"
date: 2016-08-01 09:44:41
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Chao Dong, Chen Change Loy, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
As a successful deep model applied in image super-resolution (SR), the Super-Resolution Convolutional Neural Network (SRCNN) has demonstrated superior performance to the previous hand-crafted models either in speed and restoration quality. However, the high computational cost still hinders it from practical usage that demands real-time performance (24 fps). In this paper, we aim at accelerating the current SRCNN, and propose a compact hourglass-shape CNN structure for faster and better SR. We re-design the SRCNN structure mainly in three aspects. First, we introduce a deconvolution layer at the end of the network, then the mapping is learned directly from the original low-resolution image (without interpolation) to the high-resolution one. Second, we reformulate the mapping layer by shrinking the input feature dimension before mapping and expanding back afterwards. Third, we adopt smaller filter sizes but more mapping layers. The proposed model achieves a speed up of more than 40 times with even superior restoration quality. Further, we present the parameter settings that can achieve real-time performance on a generic CPU while still maintaining good performance. A corresponding transfer strategy is also proposed for fast training and testing across different upscaling factors.

##### Abstract (translated by Google)
超分辨率卷积神经网络（SRCNN）作为一种成功应用于图像超分辨率（SR）的深度模型，在速度和恢复质量方面都表现出优于以往手工模型的性能。然而，高计算成本仍然阻碍了实际使用，要求实时性能（24 fps）。在本文中，我们的目标是加速现有的SRCNN，并提出一个紧凑的沙漏形CNN结构，以更快，更好的SR。我们重新设计SRCNN结构主要有三个方面。首先，在网络末端引入一个去卷积层，然后将原始低分辨率图像（无插值）直接映射到高分辨率图像。其次，通过缩小输入特征维度，然后进行映射和扩展，重新绘制映射层。第三，我们采用更小的过滤器尺寸，但更多的映射层。所提出的模型实现了超过40倍的加速，甚至具有优异的修复质量。此外，我们提供了可以在通用CPU上实现实时性能的参数设置，同时仍然保持良好的性能。还提出了相应的转移策略，用于在不同的放大因子上进行快速训练和测试。

##### URL
[https://arxiv.org/abs/1608.00367](https://arxiv.org/abs/1608.00367)

##### PDF
[https://arxiv.org/pdf/1608.00367](https://arxiv.org/pdf/1608.00367)

