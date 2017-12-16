---
layout: post
title: "FINN: A Framework for Fast, Scalable Binarized Neural Network Inference"
date: 2016-12-01 22:19:47
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Image_Classification Optimization Inference Classification
author: Yaman Umuroglu, Nicholas J. Fraser, Giulio Gambardella, Michaela Blott, Philip Leong, Magnus Jahre, Kees Vissers
mathjax: true
---

* content
{:toc}

##### Abstract
Research has shown that convolutional neural networks contain significant redundancy, and high classification accuracy can be obtained even when weights and activations are reduced from floating point to binary values. In this paper, we present FINN, a framework for building fast and flexible FPGA accelerators using a flexible heterogeneous streaming architecture. By utilizing a novel set of optimizations that enable efficient mapping of binarized neural networks to hardware, we implement fully connected, convolutional and pooling layers, with per-layer compute resources being tailored to user-provided throughput requirements. On a ZC706 embedded FPGA platform drawing less than 25 W total system power, we demonstrate up to 12.3 million image classifications per second with 0.31 {\mu}s latency on the MNIST dataset with 95.8% accuracy, and 21906 image classifications per second with 283 {\mu}s latency on the CIFAR-10 and SVHN datasets with respectively 80.1% and 94.9% accuracy. To the best of our knowledge, ours are the fastest classification rates reported to date on these benchmarks.

##### Abstract (translated by Google)
研究表明，卷积神经网络具有显着的冗余性，即使权重和激活从浮点值减小到二进制值，也可以获得较高的分类精度。在本文中，我们将介绍FINN，这是一个使用灵活的异构流架构来构建快速和灵活的FPGA加速器的框架。通过利用一套新的优化方法，可以将二进制神经网络有效映射到硬件，我们实现了完全连接，卷积和合并层，每层计算资源都是根据用户提供的吞吐量要求量身定制的。在ZC706嵌入式FPGA平台上，总功耗低于25W，我们每秒演示高达1230万的图像分类，MNIST数据集上的延迟时间为0.31μs，准确率为95.8％，每秒图像分辨率为21906次，283次CIFAR-10和SVHN数据集的延迟时间分别为80.1％和94.9％。据我们所知，我们的这些基准是迄今为止报告的最快的分类率。

##### URL
[https://arxiv.org/abs/1612.07119](https://arxiv.org/abs/1612.07119)

##### PDF
[https://arxiv.org/pdf/1612.07119](https://arxiv.org/pdf/1612.07119)

