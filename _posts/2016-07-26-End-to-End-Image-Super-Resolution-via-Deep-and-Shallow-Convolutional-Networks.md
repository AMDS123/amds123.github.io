---
layout: post
title: "End-to-End Image Super-Resolution via Deep and Shallow Convolutional Networks"
date: 2016-07-26 13:15:53
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Yifan Wang, Lijun Wang, Hongyu Wang, Peihua Li
mathjax: true
---

* content
{:toc}

##### Abstract
One impressive advantage of convolutional neural networks (CNNs) is their ability to automatically learn feature representation from raw pixels, eliminating the need for hand-designed procedures. However, recent methods for single image super-resolution (SR) fail to maintain this advantage. They utilize CNNs in two decoupled steps, i.e., first upsampling the low resolution (LR) image to the high resolution (HR) size with hand-designed techniques (e.g., bicubic interpolation), and then applying CNNs on the upsampled LR image to reconstruct HR results. In this paper, we seek an alternative and propose a new image SR method, which jointly learns the feature extraction, upsampling and HR reconstruction modules, yielding a completely end-to-end trainable deep CNN. As opposed to existing approaches, the proposed method conducts upsampling in the latent feature space with filters that are optimized for the task of image SR. In addition, the HR reconstruction is performed in a multi-scale manner to simultaneously incorporate both short- and long-range contextual information, ensuring more accurate restoration of HR images. To facilitate network training, a new training approach is designed, which jointly trains the proposed deep network with a relatively shallow network, leading to faster convergence and more superior performance. The proposed method is extensively evaluated on widely adopted data sets and improves the performance of state-of-the-art methods with a considerable margin. Moreover, in-depth ablation studies are conducted to verify the contribution of different network designs to image SR, providing additional insights for future research.

##### Abstract (translated by Google)
卷积神经网络（CNN）的一个令人印象深刻的优势是它们能够自动学习原始像素的特征表示，而不需要手工设计的程序。然而，最近的单幅图像超分辨率（SR）方法未能保持这一优势。它们以两个分离的步骤利用CNN，即首先用手工设计的技术（例如双三次插值）将低分辨率（LR）图像上采样到高分辨率（HR）尺寸，然后在上采样的LR图像上应用CNN以重建HR结果。在本文中，我们寻求一种替代方案，提出一种新的图像SR方法，它共同学习特征提取，上采样和HR重建模块，从而产生一个完全端到端的可训练的深度CNN。与现有方法相反，所提出的方法利用针对图像SR的任务优化的滤波器在潜在特征空间中进行上采样。此外，HR重建是以多尺度的方式进行的，以同时结合短程和长程的上下文信息，确保HR图像的更准确的恢复。为了便于网络训练，设计了一种新的训练方法，将所提出的深度网络与较浅的网络联合训练，导致更快的收敛性和更优越的性能。所提出的方法在广泛采用的数据集上进行了广泛的评估，并且相当大地提高了现有技术方法的性能。此外，进行深入的消融研究，以验证不同的网络设计对SR成像的贡献，为未来的研究提供更多的见解。

##### URL
[https://arxiv.org/abs/1607.07680](https://arxiv.org/abs/1607.07680)

##### PDF
[https://arxiv.org/pdf/1607.07680](https://arxiv.org/pdf/1607.07680)

