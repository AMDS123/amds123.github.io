---
layout: post
title: "Convolutional Neural Networks for Non-iterative Reconstruction of Compressively Sensed Images"
date: 2017-08-17 00:18:44
categories: arXiv_CV
tags: arXiv_CV Adversarial Tracking CNN Object_Tracking Inference
author: Suhas Lohit, Kuldeep Kulkarni, Ronan Kerviche, Pavan Turaga, Amit Ashok
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional algorithms for compressive sensing recovery are computationally expensive and are ineffective at low measurement rates. In this work, we propose a data driven non-iterative algorithm to overcome the shortcomings of earlier iterative algorithms. Our solution, ReconNet, is a deep neural network, whose parameters are learned end-to-end to map block-wise compressive measurements of the scene to the desired image blocks. Reconstruction of an image becomes a simple forward pass through the network and can be done in real-time. We show empirically that our algorithm yields reconstructions with higher PSNRs compared to iterative algorithms at low measurement rates and in presence of measurement noise. We also propose a variant of ReconNet which uses adversarial loss in order to further improve reconstruction quality. We discuss how adding a fully connected layer to the existing ReconNet architecture allows for jointly learning the measurement matrix and the reconstruction algorithm in a single network. Experiments on real data obtained from a block compressive imager show that our networks are robust to unseen sensor noise. Finally, through an experiment in object tracking, we show that even at very low measurement rates, reconstructions using our algorithm possess rich semantic content that can be used for high level inference.

##### Abstract (translated by Google)
用于压缩感测恢复的传统算法在计算上是昂贵的并且在低测量速率下是无效的。在这项工作中，我们提出了一个数据驱动的非迭代算法来克服早期迭代算法的缺点。我们的解决方案ReconNet是一个深度神经网络，其参数是端到端学习的，以将场景的逐块压缩测量映射到期望的图像块。重建图像变成一个简单的向前通过网络，可以实时完成。我们经验地显示，我们的算法在较低的测量速率下以及在存在测量噪声的情况下与具有较高PSNR的迭代算法相比产生重构。我们还提出了ReconNet的一个变体，它使用对抗性损失来进一步提高重建质量。我们讨论如何在现有的ReconNet体系结构中增加一个完全连接的层，从而允许在单个网络中联合学习测量矩阵和重建算法。从块压缩成像器获得的实际数据的实验表明，我们的网络对于看不见的传感器噪声是鲁棒的。最后，通过对象跟踪的实验，我们发现即使在很低的测量速率下，使用我们的算法的重构也具有丰富的语义内容，可用于高层次的推断。

##### URL
[https://arxiv.org/abs/1708.04669](https://arxiv.org/abs/1708.04669)

##### PDF
[https://arxiv.org/pdf/1708.04669](https://arxiv.org/pdf/1708.04669)

