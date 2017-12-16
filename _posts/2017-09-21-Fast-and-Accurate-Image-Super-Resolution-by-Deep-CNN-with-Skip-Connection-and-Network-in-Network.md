---
layout: post
title: "Fast and Accurate Image Super Resolution by Deep CNN with Skip Connection and Network in Network"
date: 2017-09-21 22:22:55
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Jin Yamanaka, Shigesumi Kuwashima, Takio Kurita
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a highly efficient and faster Single Image Super-Resolution (SISR) model with Deep Convolutional neural networks (Deep CNN). Deep CNN have recently shown that they have a significant reconstruction performance on single-image super-resolution. Current trend is using deeper CNN layers to improve performance. However, deep models demand larger computation resources and is not suitable for network edge devices like mobile, tablet and IoT devices. Our model achieves state of the art reconstruction performance with at least 10 times lower calculation cost by Deep CNN with Residual Net, Skip Connection and Network in Network (DCSCN). A combination of Deep CNNs and Skip connection layers is used as a feature extractor for image features on both local and global area. Parallelized 1x1 CNNs, like the one called Network in Network, is also used for image reconstruction. That structure reduces the dimensions of the previous layer's output for faster computation with less information loss, and make it possible to process original images directly. Also we optimize the number of layers and filters of each CNN to significantly reduce the calculation cost. Thus, the proposed algorithm not only achieves the state of the art performance but also achieves faster and efficient computation. Code is available at this https URL

##### Abstract (translated by Google)
我们提出了一个高效，快速的深度卷积神经网络（Deep CNN）的单图像超分辨率（SISR）模型。最近CNN深度显示，它们在单幅图像超分辨率方面具有显着的重建性能。目前的趋势是使用更深的CNN层来提高性能。但是，深度模型需要较大的计算资源，不适用于移动，平板电脑和物联网设备等网络边缘设备。我们的模型通过深度CNN与剩余网络，跳过连接和网络网络（DCSCN），实现了最先进的重构性能，其计算成本至少降低了10倍。 Deep CNN和Skip连接层的组合被用作本地和全局区域的图像特征的特征提取器。并行化的1x1 CNN，如网络中的网络，也用于图像重建。这种结构减少了前一层输出的尺寸，加快了计算速度，减少了信息损失，使得直接处理原始图像成为可能。我们还优化每个CNN的层数和滤波器数量，以显着降低计算成本。因此，所提出的算法不仅达到了最新的性能水平，而且实现了更快，更高效的计算。代码可在此https网址获得

##### URL
[https://arxiv.org/abs/1707.05425](https://arxiv.org/abs/1707.05425)

##### PDF
[https://arxiv.org/pdf/1707.05425](https://arxiv.org/pdf/1707.05425)

