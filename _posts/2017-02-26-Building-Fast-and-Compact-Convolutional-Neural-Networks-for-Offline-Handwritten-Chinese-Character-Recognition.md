---
layout: post
title: "Building Fast and Compact Convolutional Neural Networks for Offline Handwritten Chinese Character Recognition"
date: 2017-02-26 02:13:20
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Xuefeng Xiao, Lianwen Jin, Yafeng Yang, Weixin Yang, Jun Sun, Tianhai Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Like other problems in computer vision, offline handwritten Chinese character recognition (HCCR) has achieved impressive results using convolutional neural network (CNN)-based methods. However, larger and deeper networks are needed to deliver state-of-the-art results in this domain. Such networks intuitively appear to incur high computational cost, and require the storage of a large number of parameters, which renders them unfeasible for deployment in portable devices. To solve this problem, we propose a Global Supervised Low-rank Expansion (GSLRE) method and an Adaptive Drop-weight (ADW) technique to solve the problems of speed and storage capacity. We design a nine-layer CNN for HCCR consisting of 3,755 classes, and devise an algorithm that can reduce the networks computational cost by nine times and compress the network to 1/18 of the original size of the baseline model, with only a 0.21% drop in accuracy. In tests, the proposed algorithm surpassed the best single-network performance reported thus far in the literature while requiring only 2.3 MB for storage. Furthermore, when integrated with our effective forward implementation, the recognition of an offline character image took only 9.7 ms on a CPU. Compared with the state-of-the-art CNN model for HCCR, our approach is approximately 30 times faster, yet 10 times more cost efficient.

##### Abstract (translated by Google)
像计算机视觉中的其他问题一样，离线手写汉字识别（HCCR）已经使用基于卷积神经网络（CNN）的方法取得了令人印象深刻的结果。然而，需要更大和更深的网络来提供这个领域的最新成果。这样的网络直观地看起来招致高计算成本，并且需要存储大量的参数，这使得它们不可用于便携式设备中的部署。为了解决这个问题，我们提出了全局监督低秩扩展（GSLRE）方法和自适应下降权重（ADW）技术来解决速度和存储容量的问题。我们设计了一个由9755个类组成的9层HCN CNN，并设计了一个算法，可以将网络计算成本降低9倍，并将网络压缩到基线模型原始大小的1/18，只有0.21％精度下降。在测试中，所提出的算法超过了迄今为止在文献中报道的最好的单网络性能，而仅需要2.3MB用于存储。而且，当与我们有效的前向实现相结合时，识别离线字符图像在CPU上只花费了9.7毫秒。与最先进的HCCR CNN模型相比，我们的方法快了大约30倍，而成本效率却高出了10倍。

##### URL
[https://arxiv.org/abs/1702.07975](https://arxiv.org/abs/1702.07975)

##### PDF
[https://arxiv.org/pdf/1702.07975](https://arxiv.org/pdf/1702.07975)

