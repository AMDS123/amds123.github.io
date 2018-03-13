---
layout: post
title: "ShuffleSeg: Real-time Semantic Segmentation Network"
date: 2018-03-10 14:28:45
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Mostafa Gamal, Mennatullah Siam, Moemen Abdel-Razek
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time semantic segmentation is of significant importance for mobile and robotics related applications. We propose a computationally efficient segmentation network which we term as ShuffleSeg. The proposed architecture is based on grouped convolution and channel shuffling in its encoder for improving the performance. An ablation study of different decoding methods is compared including Skip architecture, UNet, and Dilation Frontend. Interesting insights on the speed and accuracy tradeoff is discussed. It is shown that skip architecture in the decoding method provides the best compromise for the goal of real-time performance, while it provides adequate accuracy by utilizing higher resolution feature maps for a more accurate segmentation. ShuffleSeg is evaluated on CityScapes and compared against the state of the art real-time segmentation networks. It achieves 2x GFLOPs reduction, while it provides on par mean intersection over union of 58.3% on CityScapes test set. ShuffleSeg runs at 15.7 frames per second on NVIDIA Jetson TX2, which makes it of great potential for real-time applications.

##### Abstract (translated by Google)
实时语义分割对于移动和机器人相关应用是非常重要的。我们提出一个计算有效的分割网络，我们称之为ShuffleSeg。所提出的架构基于其编码器中的分组卷积和信道混洗以提高性能。比较不同解码方法的消融研究，包括Skip体系结构，UNet和Dilation Frontend。讨论速度和准确性折衷的有趣见解。结果表明，解码方法中的跳跃架构为实时性能目标提供了最佳折衷方案，同时通过使用更高分辨率的特征映射来提供更准确的分割，从而提供足够的准确性。 ShuffleSeg在CityScapes上进行评估，并与最先进的实时分段网络进行比较。它实现了2倍的GFLOP减少，同时它在CityScapes测试集上提供了58.3％的联合平均交集。 NVIDIA®（英伟达™）Jetson TX2以每秒15.7帧的速度运行ShuffleSeg，这使其具有实时应用的巨大潜力。

##### URL
[https://arxiv.org/abs/1803.03816](https://arxiv.org/abs/1803.03816)

##### PDF
[https://arxiv.org/pdf/1803.03816](https://arxiv.org/pdf/1803.03816)

